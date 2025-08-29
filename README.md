# AWS DevOps CI/CD Starter Project

## Deployment Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ManishLakhara197/devops-test.git
   ```
2. Login to Your AWS Account.
3. Switch to N.Verginia Region ( us-east-1 )
4. Get Pre-requisites out of the way
    * Get Key Pair from aws console, or docs :: AMI ami-00ca32bbc84273381
    * Create KeyPair: name = Manish
    * InstanceType: t3.micro ( N.Verginia Region)
5. Deploy All-in-one-main.yml template at cloudformation console.
    * Use Pre-requisite fetched to fill in parametes
6. Varify deployment by visiting Outputed ec2 ip address. 
    * ![alt text](images/ec2.png)
7. Visit lambda console and run test to get 200 - 'Hello from Lambda!'
    * ![alt text](images/lambda.png)
----
### Up to this point we have deployed infrastructure
Pipeline setup you will find at word document.