# Docker Getting Started - JimShapedCoding

## This repository covers the code that was written in my Docker Getting Started Video

### After watching my 40-minute tutorial, you should feel comfortable with the basics of Docker

### How to get started ? 

 - Download this repository with `git clone` or by clicking the download as archive on this page
 - Follow the Docker Installation Steps on [my video](https://www.youtube.com/channel/UCU8d7rcShA7MGuDyYH1aWGg)
 - Make sure everything is installed properly
 - run `docker build . -t first_image`
 - run `docker run -d first_image` (detach mode)


### Installation on Windows step-by-step:

 - Chocolatey Installation (POWERSHELL AS ADMIN):
    - `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`

 - Refresh environment variables (CMD/POWERSHELL AS ADMIN):
    - `refreshenv`

 - Verify Chocolatey Installation (CMD/POWERSHELL AS ADMIN):
    - `choco --version`

 - Install Docker Desktop (CMD/POWERSHELL AS ADMIN):
    - `choco install docker-desktop`

 - WSL2 Set default Version:
    - `Command`
    - **NOTE: SHOULD BE AFTER THE INSTALLATION OF WSL FROM THE LINK THAT DOCKER-DESKTOP LEADS YOU**

 - Install Docker Command line Interface (CMD/POWERSHELL AS ADMIN):
    - `choco install docker-cli`

 - Refresh environment variables (CMD/POWERSHELL AS ADMIN):
    - `refreshenv`

 - Verify Docker CLI Installation - (CMD/POWERSHELL AS ADMIN):
    - `docker --version`

 - Enable HyperV feature:
    - `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All`
