#### What is Docker

It's a platform for building, running and shipping applications -  it can run in all application

Reasons for application cannot run in different machines - 

1. Files are missing
2. Different configurations 
3. Software versions mismatch

#### Container vs Virtual Machine

Container is an isolated environment for running an application 

(1) Allow running multiple apps in isolation

(2) Are lightweight

(3) User OS of the host 

(4) Start quickly 

(5) Need less hardware resources

Virtual Machine is an abstraction of a machine (physical hardware) using hypervisor - VirtualBox, VMware, Hyper-V (windows only)

Problems: 

(1) Each VM needs a full-blown OS 

(2) Slow to start

(3) Allocate resources 

#### Docker Architecture

Client --> Server (Docker Engine) via REST API

All containers on the host sharing the operating system of the host, which is the kernel of the host 

Kernal is the core of operating system which manages applications and hardware of resources

Applications need to talk to the kernel of the underlying operating system 

#### Command Line

docker run ubuntu

docker ps -a

docker run -it ubuntu 

shell takes command and passes to operation system

root: login user

string after @: machine Id

/: root dierectory

#: highest privilege - log in as root user

echo $0: the location of the shell program

 history

!2

#### Package Managers

npm 

yarn 

pip

NuGet

apt: advanced package tool

apt update

Before we install a package, run apt update 

apt remove nano

#### Linux File System

bin boot dev etc home root lib var proc

ls -1 

ls -l

cd ~

rename a directory - mv fileName newFileName

control + w 

cat

more

less

quit - q

head -n 5 fileName

tail -n 5 fileName

#### Redirection

cat file1 > file2

echo sentence > filename

ls -l /etc