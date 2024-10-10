## Notes 10:Automatic Scaling & Monitoring in AWS

**Key Points**
+ Load balacing- load balacing helps with spreading the workload of multiple servers/ services so they can preform the best they can
+ Dynamic load balancing algorithms take the current availability, workload, and health of each server into account.
+ There is predictive Autoscaling that predicts when a service will be busy and autoscales 
+ Scheduled Autoscaling- This is the scheduled timely way of autoscaling give the time parameters give my the user that scale at times where a service will get busy
+ Amazon Cloud watch- a monotoring system that will give you real time data and metrics of your applications 
+ Elastic load balancing- automatically distributes your incoming traffic across multiple targets, such as EC2 instances, containers, and IP addresses, in one or more Availability Zones

**Identify 2 Quotes that are intresting**
+ One of the quotes i would like to point out would be this one from load balancing "Dynamic load balancing algorithms take the current availability, workload, and health of each server into account. They can shift traffic from overburdened or poorly performing servers to underutilized servers, keeping the distribution even and efficient."(12.01, What is load Balacing?). The reason i choose this is because it shows how you balance workload through out your servers so tthat you dont get any backlog or problems when the server is overloaded

+ Another quote i would like to point out is "Elastic load balancingLinks to an external site. and application autoscaling are closely related. Both application auto scaling and load balancing reduce backend tasks such as monitoring the health of servers, managing the traffic load among the servers, and increasing or reducing servers pursuant to requirements. In fact, it is common to see solutions that include a load balancer with autoscaling features. However, elastic load balancing and auto scaling are distinct concepts"(12.03). The reason i am pointing this out is because it tells about the diffrences of both load balancing and auto scaling and how they are often times intergrated togethor

**Outline new facts that i learned from this section**

Some new facts that i learned from this section are that its kind of like containers where they start new instances when one becomes over crowded but in our case it will spread the workload to other servers around the network so nothing is overloaded. Some other facts i learned are that there are dedicated algorithms for the practice of load balacing. Another fact i learned is that AWS or any cloud service can take care of that for with the selection of a couple of buttons.


**What question remain after reading the section**

The question that remains after reading this section is how bad will the pricing be of the algorithm for the perdictive autoscaling be if it autoscale by mistake and adds extra cost and that thoose resources where not needed? 
