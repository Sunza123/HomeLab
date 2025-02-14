Tinkering notes:

When using an .env file, make sure to define it in the compose file or it will not be read.

Homepage container will need to be stopped/started after making changes to the services/widgets/etc files. Variable replacements are only done during container startup.

Confirmed locally cloning the repository and creating an .env file successfully starts the homepage container. Checking to see if using github secrets is an option to replace a local file.

Current example of my Homepage
![image](https://github.com/user-attachments/assets/786a513e-d9a2-43fd-9027-f9acf96c0f6e)
