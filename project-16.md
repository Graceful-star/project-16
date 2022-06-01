# Documentation of project16

1. I installed aws cli and configured aws

   ![Project15](images/image1.PNG)

2. I created an s3 bucket

   ![Project15](images/image2.PNG)
   ![Project15](images/image5.PNG)

3. I created a folder and a file in VScode namely; "PBL" and "main.tf" respectively.
     
     ![Project15](images/image3.PNG)

4. I installed and initialized terraform
     
     ![Project15](images/image4.PNG)

5. I added provider and resource to create VPC and subnet in the "main.tf" file
    
6. I saved it and ran "terraform plan" command
    ![Project15](images/image6.PNG)

7. I ran `terraform fmt` and `terraform validate` to confirm
   
   ![Project15](images/image7.PNG)

8. I ran `terraform plan` and `terraform apply` and it worked successfully

    ![Project15](images/image8.PNG)
    ![Project15](images/image9.PNG)
    ![Project15](images/image10.PNG)

9. I checked my aws console to confirm if the VPC and the subnets has been created
   
   ![Project15](images/image11.PNG)
   ![Project15](images/image12.PNG)

10. I destroyed what I created by running `terraform destroy`

    ![Project15](images/image13.PNG)
    ![Project15](images/image14.PNG)

11. I checked my aws console to see if it has been destroyed
    
    ![Project15](images/image15.PNG)
    ![Project15](images/image16.PNG)

12. I entered my terraform console to check the cidrsubnet output
    
    ![Project15](images/image17.PNG)
    ![Project15](images/image18.PNG)

13. After changing some things and creating new files, I ran the `terraform plan`, `terraform fmt` and `terraform apply` commands
     
     ![Project15](images/image19.PNG)
     ![Project15](images/image20.PNG)
     ![Project15](images/image21.PNG)
     ![Project15](images/image22.PNG)
     ![Project15](images/image23.PNG)
     ![Project15](images/image24.PNG)

14. I checked my aws console to confirm if what I stated has been created

     ![Project15](images/image25.PNG)
     ![Project15](images/image26.PNG)

15. These are the snipped shots of my files
    
    ![Project15](images/image27.PNG)
    ![Project15](images/image28.PNG)
    ![Project15](images/image29.PNG)
    ![Project15](images/image30.PNG)
