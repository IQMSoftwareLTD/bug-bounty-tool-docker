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

The next step is to login to docker as this is currently using private images. Login with the command below

```bash
docker login
```
The third step is to download the images and run the site. 

```bash
docker-compose pull && docker-compose up -d
```
