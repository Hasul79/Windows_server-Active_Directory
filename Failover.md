# Failover (load balancing)

<hr/>

<div align="center">

![1667051692815](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/7afb9372-bbf2-4fdb-b10d-431f29fb028e)

</div>

<h1 align="center">Failover (load balancing)</h1>

<p>Load balancing is a technique used to distribute network traffic evenly across multiple servers to improve application responsiveness, increase availability, and reduce latency. It is a core networking solution that distributes network traffic across multiple servers in a server farm. A load balancer is a device that sits between the user and the server group and acts as an invisible facilitator, ensuring that all resource servers are used equally. By spreading the work evenly, load balancing improves application responsiveness and increases the availability of applications and websites for users. Load balancing can optimize the response time and avoid unevenly overloading some compute nodes while other compute nodes are left idle.</p>
<br/>
<p>To set up load balancing, you need to configure failover on a second server connected to the first server's domain. Here are the steps:</p>
<ol>
<li>From the tools menu, select DHCP.</li>
<li>Right-click on IPv4 and select "Configure Failover".</li>


![Screenshot 2024-03-26 011638](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/9c524514-5c7d-4f89-bfc1-aad67983ae9f)


<li>Follow the prompts in the failover configuration wizard to set up the failover relationship between the DHCP servers.</li>

![Screenshot 2024-03-26 011650](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/9b399051-822a-4466-b57f-7f3df00024eb)


<br/>

![Screenshot 2024-03-26 011700](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/979167e8-92c3-499e-a169-2e63801e9df2)

<br/>


![Screenshot 2024-03-26 011713](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/ff5c3307-9d9a-409b-a480-3e023a0e7b30)

<br/>
</ol>
<p>These steps will initiate the process of setting up failover for load balancing, ensuring redundancy and high availability for your network infrastructure.</p>
