## Exercise 3: Migrate your source MySQL database to your Aurora instance using the AWS Database Migration Service
In this exercise, you will use the AWS Database Migration Service to migrate your mydb database running on your MySQL instance to your Aurora instance.

##### Follow the below steps to migrate your source MySQL database to your Aurora instance using the AWS Database Migration Service

1. At the top of the AWS Management Console, in the search bar, search for the service **DMS**.

![](./screen/Screenshot_27.png)

<br>

2. On the AWS DMS page, open the navigation page on the left click on the **Replication Instance (1)**, and the Create Replication Instance (2).
   
<br>

![](./screen/Screenshot_28.png)

<br>

3. On the Replication Instance page, provide the below details to configure the Instance.

- For the Replication Instance Name, enter **replicationInstance**.

- For the Description, enter **replicationInstance.**

![](./screen/Screenshot_29.png)

<br>

- For the Instance Class, choose **dms.t3.micro**

- For the High Availability, choose **Dev or test workload(Single-AZ).**

![](./screen/Screenshot_30.png)
<br>

- For the Storage, enter **30.**

![](./screen/Screenshot_31.png)

<br>

- For the Virtual private cloud (VPC) for IPv4, choose VPC name starting with clgVpc.

- For the Public accessible, Deselect the option.

![](./screen/Screenshot_32.png)

<br>

- Click on Create Replication Instance.

![](./screen/Screenshot_33.png)

<br>

**Note: The creation of a replication instance may take 5-10 minutes. You may have to wait for your replication instance to become active.**

![](./screen/Screenshot_34.png)
