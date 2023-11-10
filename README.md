# MySQL-client-server-architecture


<img src='images/MySQL-Client-Requests.png' width='950' height='300'>


In this project we will implement a Client Server Architecture using MySQL Database Management System, but first let's understand Client-Server Architecture better.

## What is Client-Sever Architecture?

Client-Server refers to an architecture in which two or more computers are connected together over a network to send and receive requests between one another.

Each machine has has its own role, the machine sending requests is reffered to as "Client" and the machine respondng is called "Server". In this project we will create two machines, one being Client and the other Server.


### Implement a Client Server Architecture using MySQL


1. Create and configure two Linux-based EC2 instances in AWS.
   - Server A - `mysql server`
   - Server B - `mysql client`

   
![images](images/Screenshot_1.png)

2. MySQL server uses port 3306, so open it by creating a new entry in 'inbound rules' in `mysql server` Security Groups. Allow acess to only the local IP address of the `mysql client`

![images](images/Screenshot_2.png)

3. On `mysql server` Linux Server install MySQL **Server** software, on `mysql client` Linux Server install MySQL **Client** software


  - Run `sudo apt upgrade` on each machine.
  - Run `sudo apt install mysql-server` for `mysql server`
  - Run `sudo apt install mysql-client` for `mysql client`

![images](images/Screenshot_3.png)


![images](images/Screenshot_4.png)


![images](images/Screenshot_5.png)


![images](images/Screenshot_6.png)


![images](images/Screenshot_9.png)


![images](images/Screenshot_7.png)


![images](images/Screenshot_8.png)


