<p align="center">
<img src="https://i.imgur.com/nBkHqaM.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>Virtual Private Networks (VPN) Setup and Usage | ProtonVPN</h1>

Project outlines setting up a Virtual Machine in Microsoft Azure to download, install, and use ProtonVPN, a free VPN service.
A VPN, or Virtual Private Network, creates a secure, encrypted connection between your device and the internet, masking your IP address and encrypting your data to enhance privacy and security, especially when using public Wi-Fi. VPNs are used by individuals to enhance privacy and security online, and by businesses to allow remote access to their networks. 

<h2>Environments and Utilities Used</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2>Setting up the Virtual Machine in Azure</h2>
<p align="center">
Open Microsoft Azure and create a new Resource Group:

![image](https://github.com/user-attachments/assets/1d872145-3304-4923-b00c-88348790c876)

<p align="center">
Then create the Windows 10 Virtual Machine:

![image](https://github.com/user-attachments/assets/010c9b23-0804-49ab-b013-02f21d5fadea)

<p align="center">
Place the VM in the Resource Group we just created and in "Image" select the Windows 10 Pro version:

![image](https://github.com/user-attachments/assets/ccbbd7fb-b030-4e94-a992-43c654a65607)

<p align="center">
Under "Size" select "Standard_E2s_v3- 2vcpus":

![image](https://github.com/user-attachments/assets/1adbbf65-9971-4a80-9114-ad201266d589)

<p align="center">
Once the VM is created, remote into it and in the web browser, go to www.whatismyIPaddress.com.  Note the IP address and geo-data of the VM prior to connecting to the VPN:

![image](https://github.com/user-attachments/assets/0cf90750-eb0c-4004-b3b2-596bd11e9d67)

<p align="center">
Open a new tab and browse to www.protonvpn.com and create a free account:

![image](https://github.com/user-attachments/assets/a97261ba-bcee-48b9-8e17-1ed94c043c1e)

<p align="center">
Once signed in, under Downloads, download the Windows version:

![image](https://github.com/user-attachments/assets/620d3492-8857-474a-aa64-1e09417d9b39)

<p align="center">
Open and sign in to ProtonVPN:

![image](https://github.com/user-attachments/assets/d2e3b293-3603-4a71-82ae-71bc82f97912)

<p align="center">
Click "Connect" to connect to the VPN:

![image](https://github.com/user-attachments/assets/da052eba-b4c8-41e9-8ff9-6ab45426c146)

<p align="center">
Open the tab www.whatismyIPaddress.com again and click "refresh":

![image](https://github.com/user-attachments/assets/f63844c4-6afd-493a-8eb7-6b6bfa6f9856)

<p align="center">
Notice the new IP address and geo-data.  You are now connected to the VPN.
