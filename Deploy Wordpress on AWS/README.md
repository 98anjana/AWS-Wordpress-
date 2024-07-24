
                                   𝐇𝐨𝐰 𝐭𝐨 𝐃𝐞𝐩𝐥𝐨𝐲 𝐖𝐨𝐫𝐝𝐏𝐫𝐞𝐬𝐬 𝐨𝐧 𝐀𝐖𝐒 𝐄𝐂𝟐: 𝐀 𝐂𝐨𝐦𝐩𝐥𝐞𝐭𝐞 𝐆𝐮𝐢𝐝𝐞

                                   
1) 𝐋𝐚𝐮𝐧𝐜𝐡 𝐚𝐧 𝐄𝐂 𝐈𝐧𝐬𝐭𝐚𝐧𝐜𝐞
   
   * Launched a EC2 instance , name Wordpress-1.0 .
   
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
