# Windows_server-Active_Directory
<br>

<div align="center">
  <h1>Этот проект посвящен Windows Server Active Directory, и мы будем настраивать его и поймем, как он работает.</h1>
</div>
<br/>

<div align="center">
  
![Active-Directory](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/26339a44-cd69-4f62-892e-4dfbb370da0c)

</div>
# Что такое Active Directory?
<p>Active Directory (AD) - это служба каталоговых сервисов, разработанная корпорацией Microsoft, которая используется для хранения информации о ресурсах сети (таких как пользователи, компьютеры, принтеры и другие устройства) в сетевой среде, основанной на Windows. Она обеспечивает централизованное управление и аутентификацию для пользователей, а также предоставляет управление доступом и политиками безопасности в сети.</p>
<br/>

# Сначала нам нужно установить Virtual Box или VMware и ISO-файл службы Microsoft


<p>VirtualBox - <a href="https://www.virtualbox.org/wiki/Downloads">Download VirtualBox</a></p>
<p>VMware - <a href="https://www.vmware.com/products/workstation-pro/workstation-proevaluation.html">Download VMware Workstation Pro</a></p>
<p>Microsoft service - <a href="https://www.microsoft.com/en-us/evalcenter/download/windowsserver2019">Download Windows Server 2019</a></p>

<br/>

# После установки Virtual box установите службу Microsoft и настройте ее.
<br/>

1. Выберите **New**. (1)
   <br/>
       <img src="https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/d4be4d6b-74b9-4959-aac5-4de033373f22" alt="Screenshot 2024-03-17 180210">
 <br/>


<br/>
2. Напишите имя, путь, тип и версию и нажмите кнопку "Next". (2, 3)
<br/>

![Screenshot 2024-03-17 181340](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/60a31439-05cd-41ff-9cbe-4fc288052814)

<br/>
3. Выберите объем памяти (RAM) и нажмите кнопку "Next". (4, 5)
<br/>

![Screenshot 2024-03-17 181948](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/163ba4ee-4a7c-486c-87db-2bb8f700f9cf)

4. Выберите тип файла hard disk, и нажмите "Create" (6)
 <br/>

![Screenshot 2024-03-17 190007](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/9a5bfea5-0ed4-4c38-b614-6e660c707009)


5. VDI(VirtualBox DiSk Image) (7)
  <br/>
  
   ![Screenshot 2024-03-17 191749](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/f5ee2889-2797-4378-ac37-df5ba3aabde8)

6. Выберите тип хранилища и нажмите "Next". (8)
   <br/>

   ![Screenshot 2024-03-17 191916](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/71363251-7b17-46c4-9754-a07db341791f)

7. Выберите расположение файла .vdi и размер хранилища и нажмите "Create". (9)
   <br/>

![Screenshot 2024-03-17 192319](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/891c7f03-8a8b-42a7-b282-c62410a494f9)

8. Откройте Settings / Storage / select Empty  и поместите туда свой ISO-файл и нажмите "OK". (10, 11)
   <br/>
   
![Screenshot 2024-03-17 192501](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/b7b9c1c2-4b99-4b07-a6b1-6bbd3a818f0a)

<br/>

9. После этого запустите машину и настройте сервер Windows. <br/>
10. После установки вы увидите. 

11. Создайте пароль администратора и войдите в систему.
<br/>

![Screenshot 2024-03-17 193244](https://github.com/Hasul79/Windows_server-Active_Directory/assets/95657084/1fc24f17-f055-4c50-8e31-92f025f03c8b)

