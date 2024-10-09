## Notes 04: AWS Cloud Security

**Key points made in the readings**
+ Cyber security is the art of protection for networks, devices, and data
+ You can improve your security but updating your system, run up to date antivirus software, and using strong passwords
+ Cyber security can be put into a trialgle know as AIC Triad it consists of Availability, Integrety, and Confidentiality
+ The Responsibility is actually shared between the customer and AWS
+ The Responsibility is dived tho the customer handle things like the customer data, platform, applications, indentity & access managment
+ Some Resposibility that the cloud services have is the software, compute, storage, database, networking, and the hardware/ infrastructure
+ AWS provides lessons on how to practice identity and acces managment, data protection/privacy, compliance, detection, and incident investigation and responce

**Two quotes made that i found intresting**
+ One quote that i found intresting is actually the practice of making a root user to create an iam user than locking away the root user credentials and use them for certain services "When you first create an AWS account, you begin with a single sign-in identity that has complete access to all AWS services and resources in the account. This identity is called the AWS account root user and is accessed by signing in with the email address and password that you used to create the account. We strongly recommend that you do not use the root user for your everyday tasks, even the administrative ones. Instead, adhere to the best practice of using the root user only to create your first IAM userLinks to an external site.. Then securely lock away the root user credentials and use them to perform only a few account and service management tasks."(6.06 Introduction to IAM). In the quote is shows the nature of how they are sepreate kinda like the front end and backend of an application.
 the reason i found this intresting is because it is a practice i use when i set up any linux distro or linux server distro. 
+ Another quote i found very intresting is the shared responsibility while the customer has more responsibility because they are the ones that handle the data and the cloud services are responsible for security of the actual cloud as stated in the shared responsibility model "The nature of this shared responsibility also provides the flexibility and customer control that permits the deployment. As shown in the chart below, this differentiation of responsibility is commonly referred to as Security “of” the Cloud versus Security “in” the Cloud"(6.04 AWS Shared Responsibility Model)

**New facts that i learned from this section**

Some new facts i learned about in this section is the AIC Triad. It is very intresting that there is sort of a standard of how you handle cybersecurity. It also helps with making a concept that might have been hard for someone to understand and set up a base on how to handle things such as security which is very important.
Another fact i learned from this section is the features of the AWS Service called IAM it grants other people to acces an account to administer and use the AWS services without having to just use on login. You can also use to add secure acces to 
any applications that are running on the EC2 service.

**Questions that remain in my mind**

The questions that remain in my mind after reading this section are can you make temporary accounts such for those who are auditing or when they have pentesters come in and point out vulnerabilities.
