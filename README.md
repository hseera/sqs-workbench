# sqs-workbench

![Language Python](https://img.shields.io/badge/%20Language-python-blue.svg) [![Apache License](http://img.shields.io/badge/License-Apache-blue.png)](LICENSE)

[![GitHub Last Commits](https://img.shields.io/github/last-commit/hseera/aws-python-utilities.svg)](https://github.com/hseera/aws-python-utilities/commits/) [![GitHub Size](https://img.shields.io/github/repo-size/hseera/aws-python-utilities.svg)](https://github.com/hseera/aws-python-utilities/)
[![Open GitHub Issue](https://img.shields.io/badge/Open-Incident-brightgreen.svg)](https://github.com/hseera/aws-python-utilities/issues/new/choose)
[![GitHub Open Issues](https://img.shields.io/github/issues/hseera/aws-python-utilities?color=purple)](https://github.com/hseera/aws-python-utilities/issues?q=is%3Aopen+is%3Aissue)
[![GitHub Closed Issues](https://img.shields.io/github/issues-closed/hseera/aws-python-utilities?color=purple)](https://github.com/hseera/aws-python-utilities/issues?q=is%3Aclosed+is%3Aissue)


GUI utility for Windows OS to send message to AWS SQS.
Currently MVP status. More feature and improvements will be added to it.

Executable can be downloaded from [here](https://github.com/hseera/aws-python-utilities/blob/main/sqs_workbench.zip).
Unzip the folder and run the sqs_workbench.exe file.
![index](https://github.com/hseera/aws-python-utilities/blob/main/images/sqs-playa.png)


## Requirements
### Python Modules
If you never used Amazon Web Services with Python before, you have to install the following modules:
```
boto3 
botocore
PySimpleGUI
```

### AWS Credentials
Save your AWS Credentials in your home/users folder:

Linux:
```
/home/[username]/.aws
```

Windows:
```
/Users/[username]/.aws
```
For more information about the content of the .aws folder check the AWS documentation: [Configuration and Credential Files.](https://docs.aws.amazon.com/cli/latest/userguide/cli-config-files.html)

Instead of creating the .aws folder manually you can use the [AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/installing.html):

* [Installer for Windows](https://docs.aws.amazon.com/cli/latest/userguide/awscli-install-windows.html#install-msi-on-windows)
* [Installer for Linux, UNIX](https://docs.aws.amazon.com/cli/latest/userguide/awscli-install-bundle.html)

After you've installed the AWS CLI open the PowerShell (or the Command Prompt) in Windows. In UNIX-like systems open a Shell. Then run the following command:
```
aws configure
```
Enter

* your AWS Access Key ID and
* your AWS Secret Access Key.
* As default region name enter your Availability Zone (AZ) and
* use "json" as default output format

# Contribute

If you would like to contribute to this project, please reachout to me. Issues and pull requests are welcomed too.

# Author
[<img id="github" src="./images/github.png" width="50" a="https://github.com/hseera/">](https://github.com/hseera/)    [<img src="./images/linkedin.png" style="max-width:100%;" >](https://www.linkedin.com/in/hpseera) [<img id="twitter" src="./images/twitter.png" width="50" a="twitter.com/HarinderSeera/">](https://twitter.com/@HarinderSeera) <a href="https://twitter.com/intent/follow?screen_name=harinderseera"> <img src="https://img.shields.io/twitter/follow/harinderseera.svg?label=Follow%20@harinderseera" alt="Follow @harinderseera" /> </a>          [![GitHub followers](https://img.shields.io/github/followers/hseera.svg?style=social&label=Follow&maxAge=2592000)](https://github.com/hseera?tab=followers)


# License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details
