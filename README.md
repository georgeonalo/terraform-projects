## Deploy a dynamic Ecommerce Website with Terraform

In this project i demonstrated how to use Terraform to deploy a dynamic ecommerce application on aws.
Using the Reference Architecture below, i used terraform to create the following resoueses; VPC with public and private subnet, Nat gateway, Security group, RDS, Application load balancer, SNS, Auto Scaling Group and Route 53.

In addition to terraform, i also used DevOps tools like, Git, Github, Visual Studio Code and AWS CLI to complete this project.

## Project Reference Architecture

![1 Terraform-Ecommerce](https://user-images.githubusercontent.com/115881685/226744267-a4bcf33e-7a56-4a9a-9a31-84ba2e6d0a60.jpg)


After setting up my enviroment, i created all the files needed to create all the resourses in my project file in vscode. The files can be found in my code directory.

The files contains reference templates that has notes which explains what each syntax in the file does, See Screenshots below of the Vscode project files and the corresponding resourses created in AWS.

### Authenticating with AWS with a "main.tf" file

![image](https://user-images.githubusercontent.com/115881685/226753946-3b2ebff3-6ebb-4129-a753-2fbb07337bd3.png)


### Create VPC


![2 _VPC_Reference_Architecture](https://user-images.githubusercontent.com/115881685/226752425-4626d8e1-4376-4fb9-a853-8c4c8e3599f8.jpg)


![image](https://user-images.githubusercontent.com/115881685/226753792-cc7d28d6-2346-47b8-9f40-a952048528e3.png)

![image](https://user-images.githubusercontent.com/115881685/226752792-ed3040b0-9be9-4234-af39-fbd9e21d4af8.png)

![image](https://user-images.githubusercontent.com/115881685/226752933-c9b8b592-0fd4-4314-a9e9-eab60a240723.png)

![image](https://user-images.githubusercontent.com/115881685/226753336-c837ca8c-cf72-428d-81a4-ab7a924a1aea.png)




### Create Nat-Gateway with a nat-gateway.tf file

![3 _Nat_Gateway_Reference_Architecture](https://user-images.githubusercontent.com/115881685/226754428-bdd57e8a-4abc-47f6-9fb5-71f0709d7c4e.jpg)

![image](https://user-images.githubusercontent.com/115881685/226754555-5b3c56f8-93d1-41f2-aff2-d6e319e5b240.png)

![image](https://user-images.githubusercontent.com/115881685/226754642-43ad3478-31ae-4873-84f9-8050c23c80c7.png)

![image](https://user-images.githubusercontent.com/115881685/226754799-7f0701d0-2649-4778-bbf6-0836a54807c0.png)

![image](https://user-images.githubusercontent.com/115881685/226754991-9a517d82-92c3-4307-a8d5-42e7e3166980.png)



### Create Security Group with security-group.tf file


![image](https://user-images.githubusercontent.com/115881685/226755528-6fee7918-0b4d-4986-a5eb-e652573b0fd3.png)


![image](https://user-images.githubusercontent.com/115881685/226755697-f74b276a-037b-4ac5-8c5c-e9079ea7d358.png)



### Create RDS with rds.tf file

![image](https://user-images.githubusercontent.com/115881685/226756047-cfe8fbf0-2eeb-411c-a0ea-dd0fd18c93ba.png)


![image](https://user-images.githubusercontent.com/115881685/226756136-9ac0c2b3-6ebd-48b6-836c-291c7d833abe.png)

![image](https://user-images.githubusercontent.com/115881685/226756269-62bae8b4-6af8-4ece-ba9d-6e7515202cdc.png)



### Create Application Load Balancer with alb.tf file


![image](https://user-images.githubusercontent.com/115881685/226756595-69809979-a259-4a67-926d-17b2131d7bfe.png)

![image](https://user-images.githubusercontent.com/115881685/226756715-de9cfad4-5c93-4a83-917d-f0b6b7448855.png)

![image](https://user-images.githubusercontent.com/115881685/226756807-897aa736-67eb-4c44-9313-0b393001e0ce.png)



### Create SNS Topic with sns.tf file

![image](https://user-images.githubusercontent.com/115881685/226757096-c06d3b0a-9b37-47bd-8c9e-92eeb6b28998.png)


![image](https://user-images.githubusercontent.com/115881685/226757223-05bb3c26-eb8f-4cb5-a28e-5f4378e860dc.png)

![image](https://user-images.githubusercontent.com/115881685/226757323-0ae54868-6935-4207-94c0-2d7603a6682f.png)

![image](https://user-images.githubusercontent.com/115881685/226757414-ed0d8963-7895-43cd-828a-aa4417f3fcb7.png)


