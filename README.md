## WORKING WITH EBS
## Name: Bharath K
## Reg no: 212224230036
## AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

## OBJECTIVE:

*Create an Amazon EBS volume
*Attach and mount your volume to an EC2 instance
*Create a snapshot of your volume
*Create a new volume from your snapshot
*Attach and mount the new volume to your EC2 instance
## ALGORITHM

# STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.
# STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.
# STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.
# STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

## OUTPUT:
<img width="1152" height="510" alt="Screenshot 2026-11-19 161533" src="https://github.com/user-attachments/assets/136d4ce6-4ebc-4888-9fc9-56dd6b8707a6" />

<img width="1163" height="511" alt="Screenshot 2026-11-19 161524" src="https://github.com/user-attachments/assets/c4953753-6ab4-437f-9237-6e30ecc50407" />

<img width="1147" height="520" alt="Screenshot 2026-11-19 161554" src="https://github.com/user-attachments/assets/30342ffa-a40a-4619-8fc4-c2b20717c22f" />

<img width="1156" height="522" alt="Screenshot 2026-11-19 161602" src="https://github.com/user-attachments/assets/824549b1-1141-43ad-a6b6-78c16a23b835" />

<img width="1152" height="501" alt="Screenshot 2026-11-19 161613" src="https://github.com/user-attachments/assets/c1d9339f-e03f-480a-8f7d-8a688ee17ecc" />

<img width="1155" height="543" alt="Screenshot 2026-11-19 161624" src="https://github.com/user-attachments/assets/cc5c05d0-1db0-4cae-8a26-aa5fad6b2b5a" />




## RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.
