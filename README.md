# Complete-Python-3-Bootcamp
Course Files for Complete Python 3 Bootcamp Course on Udemy


Get it now for 95% off with the link:
https://www.udemy.com/complete-python-bootcamp/?couponCode=COMPLETE_GITHUB

Thanks!

[665636383910_developer]
aws_access_key_id=ASIAZV6YFFSTKQBUCNOW
aws_secret_access_key=VWv6hFhylHswSCWOmMx/JLr4ipLR0+l1N9cMn2jc
aws_session_token=IQoJb3JpZ2luX2VjEDgaCXVzLWVhc3QtMSJIMEYCIQD/N8q7hijIkF/gKkWpNRocvMQ3e7RNJyw/oUasbXkocAIhANagTrRaCBVh8sn514IedMVDHnemFypscz3mcDHFM9Z0KsgDCPH//////////wEQABoMNjY1NjM2MzgzOTEwIgw3cTMzGU9zqQC0i0kqnANwORuC8L65Isyeajy9qVXCkaTCl/H7I46FP7y9dQNPG3FM4ACBsT2RFMrbTKUUSMM/6S9UQMfcOj7p9VOERqDstK6qHJISei2ayqpvIIIJhosUt2LRJngTreVe6n5+tdflCnYaaCHzfU/AmTCCCgpQKvLLQH/zYeP0l4R8W9CSAw9cmtGEs77spsS5seEQ9wHHKpkXgbZead/H0yTQP24X+M74Jd3qSgexNVifVgo7z6xi6BKdL2vem5kGZ3q1f2m45VnyyLBydrDlA5ydTyBWqY4LQdgNkarBVi/0IHV9H3Fsw3JT2DohmAf3HTdLRxVP1IBOkkB2i5m1Iwg5Id3zZuBc1UBEV/NwzFlifHU/3tTavMCEv2SaYG9kixYxPGfPCCpo5FnXh7j4uPT5dQDSzA6IwF1X8xnyu4BzmqKsqrNu9hX0mN7V2GV/7rWrIe0ogRgkpM8TFxgUUu8G0Mf9tpeXqghsPHopH0dMiX4lquY8Zd67TqeIoGMh1wQS/PWNKVHIo6lnUufgiLqvm9EBnY+f89ev1hVBKXBtMKusk6cGOqUBheIXw1ph4xaj4KSmDjvotasUT6klaeJNW9smJ1pTCUx6HW2V1yDuQe1w91JXHHRlJXws8wvQoZpEThF5dnuthaurOXg7bcRdUcT5mJQuw23NG1XJUi1//FNqLOQgaNJz5yf6mr9LKUFONCQLT3IfRr/h13BBVpABaPGf3ePzjK0cByiSVpPuIXzWVtg2GpF/lIR5rjM3OBcTIKLT/QjhP0ESDZtx

aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 665636383910.dkr.ecr.us-east-1.amazonaws.com


Retrieve an authentication token and authenticate your Docker client to your registry.
Use the AWS CLI:

aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 665636383910.dkr.ecr.us-east-1.amazonaws.com

Note: If you receive an error using the AWS CLI, make sure that you have the latest version of the AWS CLI and Docker installed.
Build your Docker image using the following command. For information on building a Docker file from scratch see the instructions here . You can skip this step if your image is already built:

docker build -t solar-poc .

After the build completes, tag your image so you can push the image to this repository:

docker tag solar-poc:latest 665636383910.dkr.ecr.us-east-1.amazonaws.com/solar-poc:latest


Run the following command to push this image to your newly created AWS repository:

docker push 665636383910.dkr.ecr.us-east-1.amazonaws.com/solar-poc:latest



