
                                   𝐇𝐨𝐰 𝐭𝐨 𝐃𝐞𝐩𝐥𝐨𝐲 𝐖𝐨𝐫𝐝𝐏𝐫𝐞𝐬𝐬 𝐨𝐧 𝐀𝐖𝐒 𝐄𝐂𝟐: 𝐀 𝐂𝐨𝐦𝐩𝐥𝐞𝐭𝐞 𝐆𝐮𝐢𝐝𝐞

                                   
1)𝐋𝐚𝐮𝐧𝐜𝐡 𝐚𝐧 𝐄𝐂 𝐈𝐧𝐬𝐭𝐚𝐧𝐜𝐞
   
   * I Launched a EC2 instance , name Wordpress-1.0 .
   
   * chose the Ubuntu AMI and the instance type was t2.micro .
   
   * Created a new key pair WPkey-1.ppk file for SSH access. 
     (.ppk for use with putty & .pem for use with open SSH.)
   
  ![Screenshot (99)](https://github.com/user-attachments/assets/dacae25b-5992-4b01-805b-b0f7e8a207a0)





   * Configure security groups to allow HTTP (port 80), HTTPS (port 443),RDP (port 3389) and SSH (port 22).

  ![Screenshot (103)](https://github.com/user-attachments/assets/26b3564b-d963-4bca-bf13-15c8d2a68d9e)



  

   * Allocate and associate an Elastic IP to your instance.
   
![Screenshot (100)](https://github.com/user-attachments/assets/141b5b23-7e56-497a-87c8-fabbd1363b9c)


2)𝐂𝐨𝐧𝐧𝐞𝐜𝐭 𝐭𝐨 𝐘𝐨𝐮𝐫 𝐄𝐂𝟐 𝐈𝐧𝐬𝐭𝐚𝐧𝐜𝐞

 * I used PuTTY to connect to my instance. I ensured I had the .ppk file for SSH access
 * I opened PuTTY, entered my Elastic IP, and loaded my private key.

![Screenshot (104)](https://github.com/user-attachments/assets/7914bcdf-fbda-4672-863b-f6f195951dcf)

3)𝐈𝐧𝐬𝐭𝐚𝐥𝐥 𝐀𝐩𝐚𝐜𝐡𝐞, 𝐏𝐇𝐏, 𝐚𝐧𝐝 𝐌𝐲𝐒𝐐𝐋

* Updated my package lists and installed the Apache web server.
* Installed PHP and its necessary modules.
* Installed the MySQL server and secured the installation.

  ![Screenshot (105)](https://github.com/user-attachments/assets/c4cb1b28-09a9-47e1-a0e9-ce87507b9da1)

  4)𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐌𝐲𝐒𝐐𝐋

  * Created a MySQL database and user for WordPress.
  * Granted the necessary permissions to the user.

 5)𝐃𝐨𝐰𝐧𝐥𝐨𝐚𝐝 𝐚𝐧𝐝 𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐖𝐨𝐫𝐝𝐏𝐫𝐞𝐬𝐬

 * Downloaded the latest WordPress package.
 * Extracted the package to the Apache web root directory.
 * Configured the WordPress database settings.


 6)𝐂𝐨𝐦𝐩𝐥𝐞𝐭𝐞 𝐖𝐨𝐫𝐝𝐏𝐫𝐞𝐬𝐬 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

  * Opened my browser and navigated to my EC2 instance's public IP address.
  * Followed the WordPress installation wizard to complete the setup.

  ![Screenshot (106)](https://github.com/user-attachments/assets/98e8a73e-67dd-419b-829f-943422aad046)
  ![Screenshot (107)](https://github.com/user-attachments/assets/c775735b-7493-4b4d-b2b7-996e9ab6b544)
  ![Screenshot (109)](https://github.com/user-attachments/assets/f4ae8153-a7ff-464d-af61-d240bbdd9b07)


 * 
