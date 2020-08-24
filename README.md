# LetsUpgrade-AWS-Batch1

LetsUpgrade AWS Essential Batch1 Assignment are present here

## *Day3*

##### 1) aws_assignment_day3.pdf
	
	PROJECT 1: 

		Deploying a web server in Windows instance 

			Task 1: Create a windows instance using AMI :Windows 2012 R2 base 

			Task 2: Launch the Windows instance using RDP 

			Task 3: Install IIS web server using Powershell ISE 

				Note: Simply copy the command below and paste in 
				      the powershell ISE to install the IIS web server. 

				      !!!!Powershell is case sensitive. 

 				Install-WindowsFeature -name Web-Server -IncludeManagementTools 

			Task 4: Verify successful installation of IIS Web Server 

				Note: You should be able to see the Internet Information 
				      Services Web page when you paste the public IP into the browser

	PROJECT 2: 

		Deploying a web server in Windows instance 

		Task 1: Create a windows instance using AMI :Ubuntu Server 18.04 LTS (HVM) 

		Task 2: Download and install MobaXterm Portable Edition AWS Essentials | August 2020 

		Task 3: Launch the Ubuntu instance using SSH Note:Username is ubuntu 

		Task 4: Install ngnix web server using bash 
			Note: Simply copy the command below and paste in the bash to install 
			      the ngnix web server.  
			
			sudo apt-get -y update
			
			sudo apt-get -y install nginx

		 Task 5: Verify successful installation of ngnix

			 Note : You should be able to see the Welcome to ngnix Web page 
				when you paste the public IP into the browser.

      
   
       
## *Day4*

##### 1) aws_assignment_day4.pdf

        PROJECT 3:

		Step1: Create two linux instances,Use the first free linux AMI 

		Step2: Launch both instances using Mobaxterm 

		Step3: Host html login webpage on both servers 

			(Refer video for steps) 
			
			NOTE:Make change in the label of the second sever html configuration 

 

			HTML code for login page: 

 

				<form action="action_page.php" method="post"> 

					  <div class="imgcontainer"> 

						  <img src="img_avatar2.png" alt="Avatar" class="avatar"> 

					  </div> 

 

					  <div class="container"> 

					    <label for="uname"><b>Username</b></label> 

					    <input type="text" placeholder="Enter Username" name="uname" required> 


					    <label for="psw"><b>Password</b></label> 

					    <input type="password" placeholder="Enter Password" name="psw" required> 


					    <button type="submit">Login</button> 

					    <label> 

					    <input type="checkbox" checked="checked" name="remember"> Remember me 

					    </label> 

					  </div> 

  
					 <div class="container" style="background-color:#f1f1f1"> 

					    <button type="button" class="cancelbtn">Cancel</button> 

					    <span class="psw">Forgot <a href="#">password?</a></span> 

					  </div> 

					</form> 

 

		Step4: Check if the application is deployed on both servers by copy pasting the public ip of the servers into 

		       the browser. 

		Step5: Create a application Load balancer with the above two instances as targets 

		Step6: Check the functioning of ELB 
