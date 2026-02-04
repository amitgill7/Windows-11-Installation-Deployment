<h1>Windows 11 Deployment (ISO & Bootable USB)🖥️</h1>


<h2>Description</h2>
This project demonstrates two different methods of installing Microsoft Windows 11 in a lab environment. The purpose of this project is to simulate real-world IT support and system deployment scenarios by installing Windows using both ISO-based and bootable USB installation techniques.

This project focuses on operating system deployment, system preparation, BIOS/UEFI configuration, and post-installation optimization.
<br />


<h2>Technology Tools Used</h2>

- Microsoft Windows 11 ISO
- Rufus Boot Utility
- Virtual Machine Software (VMware)
- USB Flash Drive 32GB (8GB or larger)
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

 <hr>
<p align="center">
<b>Download the Windows 11 ISO installation file from the official Microsoft website to be used for creating bootable installation media:</b>  <br/>
<img width="1908" height="895" alt="image" src="https://github.com/user-attachments/assets/31fd2122-7685-4332-a87c-bdac65810eac" />
<br />
<br />
<b>Download and install Rufus, then insert a USB flash drive (8GB or larger):</b>  <br/>
<img width="1919" height="1027" alt="image" src="https://github.com/user-attachments/assets/15db0831-b7cb-4ab5-96f8-74ff4b299205" />
<br />
<br />
<b>Select the downloaded Windows 11 ISO file within Rufus and configure the recommended installation settings, including partition scheme and target system compatibility. Begin the process to create the bootable USB installation media:</b>  <br/>
<img width="1259" height="712" alt="image" src="https://github.com/user-attachments/assets/31a555d3-c4f1-4cb1-9055-7c94e744daca" />
<img width="1051" height="621" alt="image" src="https://github.com/user-attachments/assets/0ee2971c-de14-4e60-8368-5d5f03f393b1" />
<br />
<br />
<b>Access the system BIOS/UEFI firmware settings and modify the boot order to prioritize the USB installation media containing the Windows 11 setup files</b>  <br/>
<img width="1460" height="828" alt="image" src="https://github.com/user-attachments/assets/57a68216-c704-43c0-acdb-6c6b8c50c553" />
<img width="1363" height="810" alt="image" src="https://github.com/user-attachments/assets/a11e0cce-fc88-42aa-b409-b72b0750b1cd" />
<br />
<br />
<b>Boot the system from the USB installation media and proceed with the Windows 11 installation process following the same configuration and setup procedures demonstrated in the ISO installation method:</b>  <br/>
<img width="1691" height="887" alt="image" src="https://github.com/user-attachments/assets/acbc455d-b165-462f-a1c1-87a4b9d8546e" />
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
