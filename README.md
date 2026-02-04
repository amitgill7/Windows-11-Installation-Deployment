<h1>Windows 11 Deployment (ISO & Bootable USB)🖥️</h1>


<h2>Description</h2>
This project demonstrates two different methods of installing Microsoft Windows 11 in a lab environment. The purpose of this project is to simulate real-world IT support and system deployment scenarios by installing Windows using both ISO-based and bootable USB installation techniques.

This project focuses on operating system deployment, system preparation, BIOS/UEFI configuration, and post-installation optimization.
<br />


<h2>Technology Tools Used</h2>

- Microsoft Windows 11 ISO
- Windows Media Creation Tool
- Rufus Boot Utility
- Virtual Machine Software (VMware / VirtualBox / Hyper-V)
- USB Flash Drive (8GB or larger)
- BIOS / UEFI Firmware

<h2>Environments Used </h2>

- <b>(Host) Windows 11 Pro </b>(23H2)
- <b>Virtual Machine Platform: VMware / VirtualBox / Hyper-V</b>

<h2>Key Takeaways 📝</h2>

- Demonstrate multiple Windows installation methods
- Simulate real-world IT deployment workflows
- Practice BIOS/UEFI configuration
- Perform post-install system optimization and setup
- Document troubleshooting techniques

<h2>Program walk-through:</h2>

<p align="center">
<b>Navigate to the official Microsoft website and download the Windows 11 ISO installation file:</b> <br/>
<img width="1908" height="895" alt="image" src="https://github.com/user-attachments/assets/8d8a84af-9362-40b8-9846-bf27d423b79f" />
<br />
<br />
<b>Create a new virtual machine, I used VMware. Configure the virtual machine hardware settings, including memory allocation, storage size, and processor configuration based on recommended Windows 11 system requirements:</b>  <br/>
<img width="1440" height="745" alt="image" src="https://github.com/user-attachments/assets/9f34b486-40cd-4194-8a83-5d030681f46b" />
<br />
<br />
<b>Select and mount the previously downloaded Windows 11 ISO file as the boot installation media for the virtual machine:</b>  <br/>
<img width="1435" height="746" alt="image" src="https://github.com/user-attachments/assets/2c17f1f4-b5e1-4950-8183-78ed4f0fb6fb" />
<br />
<br />
<b>Enable virtual disk encryption during virtual machine setup and create a secure password to protect the virtual machine storage:</b>  <br/>
<img width="1439" height="745" alt="image" src="https://github.com/user-attachments/assets/9dbfe17b-76a0-493f-b1b6-c021c5d904b1" />
<br />
<br />
<b>Start the virtual machine and allow the Windows Setup installation prompt to load:</b>  <br/>
<img width="1002" height="677" alt="image" src="https://github.com/user-attachments/assets/05de788e-647c-4e33-bbca-1943fcdb02e6" />
<br />
<br />
<b>Choose the Windows 11 edition to install. For this deployment, Windows 11 Pro was selected:</b>  <br/>
<img width="1015" height="757" alt="image" src="https://github.com/user-attachments/assets/5b37fe30-2585-46ed-bfb0-5851b79e835d" />
<br />
<br />
<b>Allow the Windows installation process to finish loading and complete all remaining setup prompts, including system preferences and configuration settings:</b>  <br/>
<img width="1691" height="887" alt="image" src="https://github.com/user-attachments/assets/c3280f8d-be17-4ff0-9fe3-23016eee66d9" />
<img width="1020" height="763" alt="image" src="https://github.com/user-attachments/assets/e623e64e-ee5f-470a-b7ed-2bcf5cd5c320" />
<br />
<br />
<b>Create and configure a user account with administrative privileges to manage the system and domain environment:</b>  <br/>
<img width="1020" height="765" alt="image" src="https://github.com/user-attachments/assets/b1925ad7-4620-4f2d-902c-6ddbf6df9520" />
<br />
<br />
<b>Validate that Windows 11 deployment completed successfully by confirming desktop accessibility, account authentication, and overall system stability:</b>  <br/>
<img width="1916" height="1012" alt="image" src="https://github.com/user-attachments/assets/9d1bed36-d729-4192-9098-2680f89c14a1" />
<br />
<br />
<b>Check for and install the latest Windows updates to ensure the system is secure, stable, and operating with the most current features and security patches:</b>  <br/>
<img width="712" height="551" alt="image" src="https://github.com/user-attachments/assets/a2caf0ee-497f-4a69-8956-d18a33e5c675" />
<br />
<br />
<b>Open Event Viewer to view Windows processes on VM:</b>  <br/>
<img width="786" height="697" alt="image" src="https://github.com/user-attachments/assets/87b9204d-c720-4402-812e-8ea950e2844a" />
<br />
<br />
<b>Attempt to login again, however enter incorrect credentials:</b>  <br/>
<img width="396" height="241" alt="image" src="https://github.com/user-attachments/assets/0c4fd82f-6411-4a96-8619-1fa83bd8f142" />
<br />
<br />
<b>These "failed" attempts will identify as "Audit Failure" with the code "4625," future login attempts from brute forcers around the world will register as the same code:</b>  <br/>
<img width="1309" height="372" alt="image" src="https://github.com/user-attachments/assets/4fdf3ed2-d002-480a-af56-5eab1690a793" />
<br />
<br />
<b>Create Log Analytics Workspace:</b>  <br/>
<img width="769" height="665" alt="image" src="https://github.com/user-attachments/assets/e6989b61-0647-41a3-83f7-0b109b48535d" />
<br />
<br />
<b>Add Microsoft Sentinel to the Workspace:</b>  <br/>
<img width="1682" height="367" alt="image" src="https://github.com/user-attachments/assets/ef27148b-1b80-4de5-a8ce-2c7e0a91e98e" />
<br />
<br />
<b>Configure the Azure monitoring agent using security event connector:</b>  <br/>
<img width="1898" height="845" alt="image" src="https://github.com/user-attachments/assets/e93a5b62-e489-4955-98b7-ff4fb7ccadd6" />
<img width="838" height="350" alt="image" src="https://github.com/user-attachments/assets/25b6a3ee-3184-4302-9a6d-89d917244d86" />
<br />
<br />
<b>Showing All Security Events through Log Analytics Workspace:</b>  <br/>
<img width="1586" height="789" alt="image" src="https://github.com/user-attachments/assets/a91885ee-5548-4214-ab76-15cbeca832b0" />
<br />
<br />
<b>Create a Watchlist to compile and organize the data collected:</b>  <br/>
<img width="1694" height="668" alt="image" src="https://github.com/user-attachments/assets/ccd536da-8807-4146-a580-c00b29539c9b" />
<img width="1599" height="603" alt="image" src="https://github.com/user-attachments/assets/776789a6-8336-47c1-a730-8bc608839220" />
<br />
<br />
<b>Using this query, now we can see where the attackers are attacking from:</b>  <br/>
<img width="1204" height="662" alt="image" src="https://github.com/user-attachments/assets/619de9cc-6fba-4335-9ec7-0cb9908f192e" />
<br />
<br />
<b>Map of attackers geolocations:</b>  <br/>
<img width="1611" height="545" alt="image" src="https://github.com/user-attachments/assets/3d1227bd-f5d2-4af6-a62c-0adc9f3e1635" />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
