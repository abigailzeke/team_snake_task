# Setup Guide for Task 2

1. Install Docker Engine
2. Install `awscli` and configure `aws configure`
3. Set up private docker registry with s3 (refer to docker-s3-config.yml)
4. Pull yeasy/simple-web from docker hub (`docker pull`)
5. Tag image and point to my private registry (abi-registry)
6. Push image to private registry (`docker push`)
7. Run yeasy/simple-web container (from private registry) on port 8080
8. Configure nginx as reverse proxy + load balancer (refer to nginx.conf)

Please refer to yeasy_simple_web.png for the web page screenshot and running_containers.png for my running containers cli output.
Please refer to load_balancing.png for nginx load balancing in action.