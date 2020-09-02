# fargate_cfn_seleniumgrid
cloudformation template to spin up selenium grid on ECS cluster


Step to use:
- Create ECS cluster "selenium-grid" with fargate/ec2/fargate_spot capacity provider. As of last known, it wasn't possible to create a cluster with fargate_spot capacity provider using cloudformation and therefore this step.
- Apply the cloudformation template "grid.yaml". 
