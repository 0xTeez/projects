Setup users to test Active Directory Setup skills within the Windows OS. 
- **Application used**:
  - Virtual Box
  - Microsoft Windows Server 2019
  - Active Directory Users and Computers
 
- **Steps Followed**:
  1. Setup a Windows 2019 Server in Virtual Box
  2. Launched Server
  3. Followed steps to complete server setup
  4. Setup adminstrator account for server
  5. Select Server and Roles when server manager loads
  6. Select Active Directory Domain Services, Select Next with all default settings. Then Close.
  7. Select the yellow flag in the top corner of Server Manager, Select Promote this server to a domain controller.
  8. Select Add a new forest in the Deployment configuration screen. Create a domain name ending in .local
  9. After domain setup is complete, select Tools in the top right corner , Then select Active Directory Users and Computers
  10. Right Click the New User , Select Properties > Member Of tab> Select Add and Type Domain Admins Then Select Ok. this adds the user as a domain add, when you add the user to the Windows Computer.
  11. Go back to the Virtual Box directory window
  12. Right click the Server, Select Network, Select Bridge Adapter, Keep Wireless Lan Selected. Repeat the Same steps for Windows 10 Server
  13. Opened Server 2019, Opened Network Adapter Settings, Right Click Ethernet, Select Properties, Unchecked IPv6 connection. Select Ok.
  14. Opened Command Prompt, Entered ipconfig /all for IP information. 
  15. Launched the Windows 10 virtual machine ([Windows 10 Virtual Machine](https://github.com/0xTeez/projects/edit/main/Home%20Lab%20Setup/Windows%2010%20VirtualBox%20Setup.md)).
  16. Followed Step 12, then Select IPv4 connection, Right Click and select Properties.
  17. Entered the server IP address into the Preferred DNS server field, then Select OK
  18. Open Settings Menu, Select System>About>Rename PC (advanced)> Change
  19. Renamed the PC, and then prompted to restart.
  20. Restarted PC.
  21. Opened Renamed PC (advanced) settings again, Select Change > Domain > Entered AD Domain name
  22. Select Ok, Entered the created user from Active Directory Username and Password.
  23. Changes Applied and prompted to Restart.
