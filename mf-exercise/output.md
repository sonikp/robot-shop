# Set-up Robot-Shop in Docker

File for capturing the steps followed to run the application and the screenshot of the homepage

### Steps
- install docker locally on Windows
- configure docker, for WSL 2 support, and then configure a Linux distro for usage (Kali)
    - Reference: https://learn.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package
- enter localhost github pull of repo "robot-shop" directory and run the following docker commands: 
    - <code> # docker-compose pull </code> => to pull the robot-shop docker image from docker-hub
    - <code> # docker-compose up </code> => run docker image
- Error need to find INSTANA_AGENT_KEY


Image
![image](https://github.com/sonikp/robot-shop/blob/master/mf-exercise/StansRobotShop-Image-01.png)
