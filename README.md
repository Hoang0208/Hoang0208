Kest Lokaverkefni 

2. After install the base system, use VI to configure hostname as sever1 and domain "YourName.local", so the FQDN of the sever will be sever1.yourname.local
<img width="1440" alt="first question" src="https://user-images.githubusercontent.com/89973943/156213782-e9754370-81b1-4da3-851d-15024e0a03d7.png">

3. Configure client1 hostname as client1 and FQDN as client1.yourname.local
<img width="1440" alt="second question" src="https://user-images.githubusercontent.com/89973943/156214769-3c60d22a-1b80-4302-b028-1dc0bedf7d69.png">

4. Install and configure DHCP protocol on the server1, make sure the Client1 private interface will get an IPv4 address, Default Gateway and Domain Name adn DNS automatically from DHCP on server1.(The Default Gateway, DNS name is server1 IP address)
<img width="874" alt="fourth question" src="https://user-images.githubusercontent.com/89973943/156215900-d0a3a697-247e-46ea-b5cb-ba678d88b0fc.png">

5. Install and configure DNS on server for the internal network so hostnames are resolved to IP adresses
<img width="829" alt="fifth question" src="https://user-images.githubusercontent.com/89973943/156216309-69ba8c02-e248-49f4-baad-43d105bd38ee.png">

6,7 .Create ( comma separated values ) csv files with the following users attributes: FirstName, LastName, UserName, Department and Password
[Client1.csv](https://github.com/Hoang0208/Hoang0208/files/8163618/Client1.csv)

8.Create a bash script that will import all user accounts into their groups respectively. 
 Dont know how to do it 
9. Each user should have his own directory under /home should use bash shell and encrypted password
<img width="1116" alt="Ninth question" src="https://user-images.githubusercontent.com/89973943/156221581-6b0ecd63-a0f9-4fce-a8b4-f2ee1c1895b5.png">

10. All users should have acess to their home directory only, except the for the IT group they should have full acess to all directories.
Dont have the answer for it 

11. Install configure Samba then create network shared folder for each department.All users should have full access (Read, Write and Execute Permissions) to their
shared Folder. However, IT and Management should full access to all sharedFolders.
<img width="640" alt="Elenventh question" src="https://user-images.githubusercontent.com/89973943/156228168-b6715bf4-34d0-48fb-afab-9cdf4d6cd316.png">

12.Install and configure SSH protocol, so IT and Management users have remoteaccess to the server via SSH and test your configuration. 
<img width="803" alt="twelfth question" src="https://user-images.githubusercontent.com/89973943/156228892-8dbd1ded-d173-4d98-9288-378d2bde9fcf.png">
<img width="798" alt="Twelth question as well" src="https://user-images.githubusercontent.com/89973943/156230443-dd7b8c6a-1aca-4da4-8d42-34b2a6b5cf48.png">


13.Install apache2 web server with SSL certificate and configure a demo site, thesite should be accessible via the URL https://www.yourname.local
Have no idea to do the last question 
