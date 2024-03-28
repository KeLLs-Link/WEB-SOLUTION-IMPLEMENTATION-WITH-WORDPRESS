- **Provission an EC2 Instance that will serve as “Web Server”.**

Launch an EC2 instance that will serve as "Web Server". 

I will be using a **`RedHat OS`** as the underlying OS for my EC2 Server in this project.

![image](./screenshots/redhart.png)
![image](./screenshots/redhatinstancerunning.png)

- Create 3 EBS (Elastic Block Store) Volumes in the same AZ (Availability Zone) as your Web Server EC2, each EBS Volume should be 10 GB in size.

![image](./screenshots/volumes.png)

![image](./screenshots/volumess.png)
![image](./screenshots/3ebsvolumes.png)

3 EBS volumes (volume a, b, & c) has been succesfully created and available for attachment to our server.