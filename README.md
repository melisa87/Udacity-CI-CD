# Udacity-CI-CD
Using CircleCI
Job create_infrastructure in config.yml creates a new aws stack using template.yml. This template contains one EC2 machine with one security group. If the stack already exist it will be deleted using command destroy_enviroment defined in config.yml
