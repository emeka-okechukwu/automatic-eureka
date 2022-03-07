# automatic-eureka
Research Hub is a platform that guides users looking to conduct research from forming their hypothesis to publishing their research. This web application also supports administrative users.

## Technologies Used

* PHP
* HTML
* CSS
* JavaScript
* MySQL

## Local Deployment 

1. Download XAMPP and its dependencies [here](https://www.apachefriends.org/index.html "Official Apache website")
2. Install XAMPP on your computer
3. Open XAMPP and run the server
4. Start all stack services (Apache, MySQL, and ProFTPD)
5. Navigate to the folder 'htdocs'.
    1. Windows: Press the 'Explorer' button in Control Panel and choose the folder 'htdocs'
    2. Mac: Under the tab 'Volumes', mount the volume and click 'Explore'. Afterward, choose the folder 'htdocs'
6. Copy the folder 'Research Hub Code' and paste it inside the folder 'htdocs'
7. Rename the folder 'Research Hub Code' to 'research-hub'
8. Visit the XAMPP IP address on your preferred browser
9. Click on 'phpMyAdmin' on the navigation bar
10. Click on the 'Import' tab 
11. Import the file 'research_hub.sql' to create the database and tables
12. Type '{your XAMPP IP address}/research-hub/' on the browser to view the application

### Please Note

You may have a different XAMPP IP address from the address used in this project. Kindly replace the IP addresses used in this project with your own to fix this.

For instance, after registering your account, a verification link will be sent to your email:

_'192.168.64.3/research-hub/actions/user_activate_email.php?.....'_

Please change it to

_'{your XAMPP IP address}/research-hub/actions/user_activate_email.php?.....'_

Then paste it into your browser's address bar.

## Roadmap

- [ ] Allow users to upload and manage their profile pictures
- [ ] Autosave feature
- [ ] Synchronous collaboration between researchers
- [ ] POPUP MAILER


ADD FAQ WITH SAMPLE LOGIN



## Contributing

Pull requests are welcome. Please open an issue first to discuss what you would like to change for significant changes.

## Contact

Emeka Okechukwu - chuks.egkedu@gmail.com

Project Link: https://github.com/emeka-okechukwu-dev/research-hub
