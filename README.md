# cloudformation-ecs

Create a complete ECS infrastructure. Just provide the parameters in the cloudformation console and it will create the rest for you.

ECS Tasks need access to RDS, SSM, KMS so i have added a custom role in it having those policies. You can modify it according to your application needs
