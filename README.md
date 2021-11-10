# awslightsailpython
Demo aws lightsail sample project

docker build -t awslightsail-hellodemo pythonstuff/helloworld

-t flag is a tag for human readable name for our image

pythonstuff/helloworld is folder where Dockerfile is located

docker run -it --rm -p 8000:8000 awslightsail-heloodemo

docker tag awslightsail-heloodemo <docker-username>/awslightsail-heloodemo

docker login

docker push <docker-username>/awslightsail-heloodemo