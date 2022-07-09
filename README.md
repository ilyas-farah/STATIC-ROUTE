# STATIC-ROUTE
-------------------------------
R1
----
int g0/0
ip address 12.0.0.1 255.255.255.252
no shutdown 

R1
----
int g0/1
ip address 192.168.1.1 255.255.255.0
no shutdown 

Next Hope Command
------------------
R1
-----
ip route 192.168.2.0 255.255.255.0 12.0.0.2
![Static Routing](https://user-images.githubusercontent.com/106605770/178121084-0e2ad450-18aa-4b57-97d7-339d878af627.png)

