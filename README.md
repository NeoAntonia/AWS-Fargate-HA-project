#
This compose o a small web app that listens on port 3000 set up in 3 docker container on AWS with a load balancer to distribuite traffic among them, we also set up the auto escale mode up to 10 to answer the question of add more machines every time needed.
#To access the application go to:
http://cb-load-balancer-600703633.us-east-2.elb.amazonaws.com:3000/

This app we used AWS ECR service with Fargate because of the convenience of deploy an infraestructe fast, also provide as with the resources need to deploy two or more machines serving content at the same time while providing high availiability.

