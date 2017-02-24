# aws_interview
My AWS related questions for interviews


1. what services have experience/used?

IAM
Route53
S3
EC2
  ELB
  Security Groups
  Elastic IPS
  AMI
EBS
CloudWatch
CloudTrail


2. How many accounts/envs/vpc?
3. Regions and AZ.  	

AWS VPC

vpc between AZ? Regions?
what is private/public subnets. 
if I want to run redis/mongo/postgres DB - where?

4. AWS EC2

 - what is AMI
 - What is included to the AMI?  
 - root device? Does it contains kernel image? 
 - Could I launch instance without AMI?
 - Vertical scalability. How?
 - is it possible to migrate between AZ? HOW?
 - What is key pair? what is their benefits?
 - what is iam instance profile?



5. AMI
 - What is ALAMI 
 - What is the actual version of ALAMI?
 - Do you know for example default MTA in ALAMI? how can i figure it out?
 - What helpful/useful I can find in the release notes
 - Why do you use ALAMI? (more safety, limitation sshd, less vulnerability, minimal required packages,	default repositories)
 - what packet manager is using?
 - How to share AMI between accounts? 


6. Ec2 stopping and starting process. How to? 
  - stopping - normal shutdown -> EBS still attached 
  - what is terminating (normal shutdown -> deleting EBS -> deleting instance)


7. could you describe steps how can I launch instance from AWS console?


8. Security Groups
 - what is it? 
 - statefull or stateless
 - ingress egress 
 - EC2 instances only?

9. Case - 
instance launched.
trying to ssh access. ssh is not working. what is the investigation process?
  - ssh error code
    Connection timed out
    User key not recognized by the server
    Host key not found, permission denied
    Unprotected private key file
    Server refused our key or No supported authentication method available
  - key pair/password
  - what user is using? does "permitrootloging yes" enabled?   
  - AWS console:
      launch time/health checks
      security groups
      aws accounts limits
      
10. What is S3
  How did you use it?
  For what purposes?

11. What is instance metadata. How to retrieve it?


12. Terraform
  - how big was your infra
  - How did you used terraform
  - custom providers?
  - what was a typical workflow for new ec2 instance
  - describe a common module for general aws instance
  - what is remote state
  - what if you need 20-30 servers
  

13. Resource management in aws


Additional section:
  - how to create ptr record?
  - security best practise? (iam, password base/disable, security groups - review rules regularly, open only required permissions)
