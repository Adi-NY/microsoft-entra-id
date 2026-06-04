<h1>Microsoft Entra ID</h1>

<h2>Description</h2>
Built a fully functional Microsoft Entra ID environment using a dedicated Azure tenant (AdiITLab) to develop hands-on experience with cloud-based identity management, access control, and security policies. This lab simulates a real-world enterprise environment including user lifecycle management, group administration, conditional access, MFA enforcement, and device management.
<br />


## Environment
| Component | Details |
|-----------|---------|
| Platform | Microsoft Azure |
| Service | Microsoft Entra ID (formerly Azure AD) |
| Tenant | AdiITLab.onmicrosoft.com |
| Lab Type | Cloud Identity Management |
| Users Created | Multiple test users across departments |

## Skills Demonstrated
- User lifecycle management — creation, modification, password reset
- Static and Dynamic group management with attribute-based rules
- Role assignment following least privilege principles
- MFA enforcement via Conditional Access (modern enterprise standard)
- Security monitoring through sign-in and audit logs
- Account lockout identification and recovery
- Self-Service Password Reset (SSPR) configuration
- Entra ID device join and cloud-native device management

## Real World Application
| Lab Task | Real World Scenario |
|----------|-------------------|
| Dynamic group by location | Auto-assign branch staff to correct access groups |
| Conditional Access MFA | Enforce MFA for staff accessing sensitive systems |
| Sign-in log monitoring | Detect unauthorized access attempts |
| SSPR configuration | Reduce helpdesk tickets for password resets |
| Account lockout recovery | Staff locked out before shift starts |
| Entra ID device join | Deploy workstation without on-premise infrastructure |
<h2>Program walk-through:</h2>

<p align="center">
Creating a User in Microsoft Entra: <br/>
<img src="https://i.imgur.com/CySqvUS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating 365 Variant of Group(Departments)  <br/>
<img src="https://i.imgur.com/YqiWWcI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Dynamic Groups:  <br/>
<img src="https://i.imgur.com/uSNJBfi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Dynamic Group Logic that assigns employees from one location to a group:  <br/>
<img src="https://i.imgur.com/etm4fzp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Overview of Groups Created <br/>
<img src="https://i.imgur.com/RapKNJ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Assigning Azure Role (Role Delegation):  <br/>
<img src="https://i.imgur.com/Y5qzhM0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
Adding Users to Departments/Groups:  <br/>
<img src="https://i.imgur.com/Zdt7AyI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enforcing Password Policy:  <br/>
<img src="https://i.imgur.com/noYsaa5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Enabling Conditional Access Policy (MFA):  <br/>
<img src="https://i.imgur.com/pbc0D6G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Multi-Factor Authentication (MFA) In Effect  <br/>
<img src="https://i.imgur.com/OpTixeQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logging in as Domain Client (Password Policy in Effect):  <br/>
<img src="https://i.imgur.com/NxShSYh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client PC Connected to Domain:  <br/>
<img src="https://i.imgur.com/AjWaPzp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
User Sign-in Logs (Entering Wrong Password):  <br/>
<img src="https://i.imgur.com/PeB5hQR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
User Sign-in Logs (Confirming Authentication):  <br/>
<img src="https://i.imgur.com/XJbd5cY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Account Lockout Simulation:  <br/>
<img src="https://i.imgur.com/jc4zYk3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Resetting Account Password:  <br/>
<img src="https://i.imgur.com/HIjvsH8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Self Service Password Reset (SSPR) Setup:  <br/>
<img src="https://i.imgur.com/qwxYVoc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
Self Service Password Reset (SSPR) Setup 2:  <br/>
<img src="https://i.imgur.com/ZRkvLis.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Devices assigned to Domain/Managed by Company:  <br/>
<img src="https://i.imgur.com/c6vM4Ej.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
