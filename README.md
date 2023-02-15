 <img src="https://www.iqmsoftware.co.uk/wp-content/themes/iqm-software/images/logo.png" height="18px">
 
# Bug Bounty Tool Docker

[Docker Hub: Bug Bounty Site](https://hub.docker.com/r/iqmsoftware/bug-bounty-site)
| [Docker Hub: Bug Bounty Site](https://hub.docker.com/r/iqmsoftware/bug-bounty-tooling)
| [IQM Software](https://iqmsoftware.co.uk)
## Supported platforms
- `linux` `windows`

## What is the bug bounty tool?
The bug bounty tool is a an application that utilises many security auditing softwares to test 1 or more domains. It allows for seeing the data live as it comes in as well as viewing reports and filtering the data once the domain has been fully tested.


## Installation & Setup

To install the site please make sure you have docker installed. The first step is to checkout this current repository, or download the 'docker-compose.yml' file and navigate to that directory in command line.

You will need to configure the 'docker-compose.yml' file with your custom parameters. Please set the following:

1. Replace "____YOUR_PASSWORD_HERE____" with a password of your choosing.
2. Replace "____YOUR_DATA_LOCATION_HERE____" with a location on your pc where you want to store the database data. For example it could be 'C:/data/bug_bounty_data' if on windows.

The next step is to login to docker as this is currently using private images. Login with the command below

```bash
docker login
```
The third step is to download the images and run the site. 

```bash
docker-compose pull && docker-compose up -d
```
> If IQM has released an update, running the step above will repull the images, so this is how you update.

## Usage

Once the app is on your pc, you can start it with the following command in the 'docker-compose.yml' directory:

```bash
docker-compose up
```

Or you can use the docker UI as shown below:

![image](https://user-images.githubusercontent.com/28952359/219078930-2d17adad-4d14-4c42-85a4-2267e9d5a436.png)
