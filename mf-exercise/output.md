# Set-up Robot-Shop in Docker (Item 11)

File for capturing the steps followed to run the application and the screenshot of the homepage

### Steps (Item 12)
- Install docker locally on Windows
- Configure docker, for WSL 2 support, and then configure a Linux distro for usage (Kali)
    - Reference: https://learn.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package
- Enter localhost github pull of repo "robot-shop" directory and run the following docker commands: 
    - <code> # docker-compose pull </code> => to pull the robot-shop docker image from docker-hub
    - <code> # docker-compose up </code> => run docker image
- Error need to find INSTANA_AGENT_KEY


## Image (Item 12)
![image](https://github.com/sonikp/robot-shop/blob/master/mf-exercise/StansRobotShop-Image-01.png)

### Securing your master repo (Item 14)
Ensure that you secure your master branch from accidential or deliberate alterations to your source code. All changes to the master repo should be vetted and validated. This can be enforced through branch protection settings. 

To access, goto **Settings** under **Code and Automation** select **Branches** and update the **Branch Protection Rules**.
Select settings:
- Require a pull request before merging
- Require status checks to pass before merging
- Do not allow bypassing the above settings

