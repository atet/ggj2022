# [atet](https://github.com/atet) / [**_ggj2022_**](https://github.com/atet/learn/blob/master/ggj2022/README.md#atet--ggj2022)

[![.img/logo_tinderbotapi.png](.img/logo_tinderbotapi.png)](#nolink)

# Global Game Jam 2022: TinderBot API

* This is the back-end API that generates text based on player inputs.

--------------------------------------------------------------------------------------------------

## Table of Contents

### Introduction

* [0. Preface](#0-preface)
* [1. Requirements](#1-requirements)
* [2. Installation](#2-installation)
* [3. Python Script](#3-python-script)
* [4. Application Programming Interface](#4-application-programming-interface)

### Supplemental

* [Other Resources](#other-resources)
* [Troubleshooting](#troubleshooting)
* [Acknowledgments](#acknowledgments)

--------------------------------------------------------------------------------------------------

## 0. Preface

* We will deploy the [pre-trained GPT-2 model](https://en.wikipedia.org/wiki/GPT-2) for synthetic text generation on our own server
* Here is a fun example of using GPT-2 through Python:

> `Input : "Morgbob is the"`
>
> `Output: "Morgbob is the best thing you can do."`

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

## 1. Requirements

### Command Line Interface (CLI)

A CLI will be used to execute commands on our server; you can use the following depending on your operating system:

#### Windows 10

* Windows Subsystem for Linux (WSL) is a fully supported Microsoft product for Windows 10, learn how to install it here: [https://docs.microsoft.com/en-us/windows/wsl/install-win10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
* Please choose Ubuntu 18.04 LTS as the distribution you use with WSL
* WSL is only available for Windows 10

#### MacOS

* You do not need to install anything, [your Terminal program is Bash](https://en.wikipedia.org/wiki/Terminal_(macOS))

#### Linux

* I recommend using Ubuntu 18.04 LTS

### Remote Server

A Linux server can be rented from a cloud service provider (CSP) with the following minimum specifications for as low as $5/month:

* ≥1 GB of RAM (and additionally set up ≥2 GB of swap space)
* ≥25 GB of disk space

**Very basic server system administration will be covered here; you are ultimately responsible for the security of your own server**

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

## 2. Installation

### Server Login

* Connect to your remote server through CLI from your local computer:

```console
$ ssh <USERNAME>@<IP_ADDRESS>
Welcome to Ubuntu 20.04.3 LTS (GNU/Linux 5.4.0-96-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

  System information as of Mon 31 Jan 2022 05:07:09 AM UTC

  System load:              0.0
  Usage of /:               79.3% of 24.06GB
  Memory usage:             23%
  Swap usage:               1%
  Processes:                111
  Users logged in:          1
  IPv4 address for eth0:    <SERVER_IP_ADDRESS>
  IPv4 address for eth0:    <SERVER_IP_ADDRESS>
  IPv6 address for eth0:    <SERVER_IP_ADDRESS>
  IPv4 address for eth1:    <SERVER_IP_ADDRESS>

0 updates can be applied immediately.

Last login: Mon Jan 31 04:11:34 2022 from <LOCAL_IP_ADDRESS>
<USERNAME>@<SERVER_NAME>:~$
```

### Docker

* We will install and use Docker to simplify installation of dependencies:

```console
$ <INSTALL_DOCKER>
```

### Dependencies

* The following Dockerfile will have all required dependencies:

```dockerfile
FROM ...
```

### Build Docker Image and Launch Docker Container

```console
$ <DOCKER_BUILD>
$ <DOCKER_RUN>
$ <DOCKER_EXEC>
```

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

## 3. Python Script

Create the following script and save:

```python
import ...
```

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

## 4. Application Programming Interface

### Start a TMUX Session

```console
$ tmux ...
```

### Run the Flask Application

```console
$ ...
```

### Access the API Through the Internet

On your local development computer, use your favorite web browser to navigate to your server's IP address:

[![.img/null.png](.img/null.png)](#nolink)

You should see a response that contains output from the GPT-2 model:

[![.img/null.png](.img/null.png)](#nolink)

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

## Other Resources

Description | Link
--- | ---
Resource | Website

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

## Troubleshooting

Issue | Solution
--- | ---
The thing didn't happen | Try again and do the thing

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

## Acknowledgments

1. The thing, THE THING!!!

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

<p align="center">Copyright © 2022-∞ Athit Kao, <a href="http://www.athitkao.com/tos.html" target="_blank">Terms and Conditions</a></p>