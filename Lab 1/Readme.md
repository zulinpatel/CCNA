# CCNA Lab 1 - Basic Configuration

# Tasks 1: Power on devices and then configure the devices as follows:
    1) Configure IP addresses as shown in the diagram
    2) Ensure routers can ping each other
    3) Configure an enable password of "cisco"
    4) Encrypt the enable password
    5) Configure a secret password of "cisco123"
    6) Configure the first 5 telnet lines and use a line password of cisco on them
    7) Make sure you can telnet from one device to the other
    8) Configure a console password of "cisco" and test


<img
  src="/Lab 1/img/1.png"
  alt="Router Configuration"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
## 1. Configure IP addresses as shown in the diagram
### Router 1

<img
  src="/Lab 1/img/2.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

### Router 2

<img
  src="/Lab 1/img/3.png"
  alt="Router 2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

## 2. Ensure routers can ping each other
### Router 1

<img
  src="/Lab 1/img/4.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

### Router 2

<img
  src="/Lab 1/img/5.png"
  alt="Router 2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

## 3. Configure an enable password of "cisco"

### Router 1

<img
  src="/Lab 1/img/6.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

    Router1>en
    Password: 
    Router1#

### Router 2

<img
  src="/Lab 1/img/7.png"
  alt="Router 2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
    Router2>en
    Password: 
    Router2#

## 4. Encrypt the enable password
### Router 1

<img
  src="/Lab 1/img/8.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

### Router 2

<img
  src="/Lab 1/img/9.png"
  alt="Router 2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

## 5. Configure a secret password of "cisco123"
### Router 1

<img
  src="/Lab 1/img/10.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

### Router 2

<img
  src="/Lab 1/img/11.png"
  alt="Router 2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
 
## 6. Configure the first 5 telnet lines and use a line password of cisco on them
## 7. Make sure you can telnet from one device to the other
### Router 1

<img
  src="/Lab 1/img/12.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

### Router 2

<img
  src="/Lab 1/img/13.png"
  alt="Router 2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
## 8. Configure a console password of "cisco" and test
### Router 1

<img
  src="/Lab 1/img/14.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

<img
  src="/Lab 1/img/15.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
### Router 2

<img
  src="/Lab 1/img/16.png"
  alt="Router 2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  <img
  src="/Lab 1/img/17.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
## All configurations are done

<img
  src="/Lab 1/img/18.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
    Let’s check the running config and start-up config:
    
    As I didn’t configure the router in the starting, startup-config is not present

<img
  src="/Lab 1/img/19.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  <img
  src="/Lab 1/img/20.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
## Copy running config in start-up config

<img
  src="/Lab 1/img/21.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
# Task 2: Do the initial configuration of a Router

<img
  src="/Lab 1/img/22.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  <img
  src="/Lab 1/img/23.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  <img
  src="/Lab 1/img/24.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  <img
  src="/Lab 1/img/25.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

<img
  src="/Lab 1/img/26.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
## Compare running config and start-up config:
    When I change anything in configuration it will show in running configuration and nothing will change in startup configuration unless I copy running configuration into start-up configuration.


<img
  src="/Lab 1/img/27.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  <img
  src="/Lab 1/img/28.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  
    R1#copy running-config start
    R1#copy running-config startup-config 
    Destination filename [startup-config]? 
    Building configuration...
    [OK]

 <img
  src="/Lab 1/img/29.png"
  alt="Router 1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
