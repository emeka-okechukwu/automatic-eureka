# automatic-eureka
Research Hub is a platform that guides users looking to conduct research from forming their hyposthesis to publishing their research. This web application also supports administrative users.

## Technologies Used

* PHP
* HTML
* CSS
* JavaScript
* MySQL

## Local Deployment 

1. Download XAMPP and its dependencies [here](https://www.apachefriends.org/index.html "Official Apache website")
2. Install XAMPP on your computer
3. Open the XAMPP application and run server
4. Start all stack services (Apache, MySQL, and ProFTPD)
5. Navigate to the folder 'htdocs'.
    i. Windows: Pressing 'Explorer' button in Control Panel and choose the folder 'htdocs'
    ii. WMac: Under the tab 'Volumes', mount the volume and click the button 'Explore'. Finally, choose the folder 'htdocs'
6. Copy the folder 'Research Hub Code' and paste it inside the folder 'htdocs'
7. Rename the folder 'Research Hub Code' to 'research-hub'
8. Visit XAMPP IP address on preferred browser
9. Click on 'phpMyAdmin' on the navigation bar
10. Click on 'Import' tab 
11. Import the file 'research_hub.sql' to create the database and tables
12. Type 'http://{your XAMPP IP address}/research-hub/' on browser to view the application


### Please Note

You may have a different XAMPP IP address from the address used in this project.

To fix this, kindly replace the IP addresses used in this project with your own.

For example, when activating your account during registration, this link will be sent to your email:

'192.168.64.3/research-hub/actions/user_activate_email.php?.....'

Change it to

'{your XAMPP IP address}/research-hub/actions/user_activate_email.php?.....'


## Roadmap

- [ ] Allow users to upload and manage ther profile pictures
- [ ] Autosave feature
- [ ] Synchronous collaboration between researchers

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

Emeka Okechukwu - chuks.egkedu@gmail.com

Project Link:
