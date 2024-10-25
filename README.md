<h1>Active Diretory Lab</h1>

<h2>Description</h2>
The goal of this project was to create a virtual lab environment with Windows Server 2022 and Windows 10 using Oracle VirtualBox with basic Active Directory setup. This lab will serve as foundation for future projects in cybersecurity. Part of this lab is also a simple Powershell script which automatically creates users based on the list provided in text file. The AD setup intentionally does not contain any advanced AD setup like security policies as they will be topics of future projects.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle VirtualBox</b>
- <b>Powershell</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2022</b>
- <b>Windows 10</b>

<h2>Project walk-through:</h2>

<p align="center">
Windows server installation(desktop experience): <br/>
<img src="https://github.com/user-attachments/assets/1ef19d1b-f16e-46f7-be0b-fe9c1d37d36e" height="80%" width="80%" alt="Windows Server install"/>
<br />
<br />
Setup Administrator account:  <br/>
<img src="https://imgur.com/1jOe7cy.png" height="80%" width="80%" alt="Setup Administrator account"/>
<br />
<br />
Windows 10 client installation:
<img src="https://imgur.com/mdhr0gM.png" height="80%" width="80%" alt="Windows 10 installation"/>
<br />
<br />
Setting up NAT network in VirtualBox: <br/>
<img src="https://imgur.com/u6s4XeN.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller: <br/>
<img src="https://imgur.com/QaRHPeC.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(choosing server to be promoted): <br/>
<img src="https://imgur.com/ht9gqjd.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(adding Domain Services features): <br/>
<img src="https://imgur.com/AyVELkC.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(features installation): <br/>
<img src="https://imgur.com/fWqCygh.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(finished installation): <br/>
<img src="https://imgur.com/9LXGgQE.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(post installation config): <br/>
<img src="https://imgur.com/1PjhUdQ.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(adding new forest): <br/>
<img src="https://imgur.com/dZAoYcv.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(promotion): <br/>
<img src="https://imgur.com/aWh0xHP.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Promoting Windows Server to Domain Controller(login screen after promotion): <br/>
<img src="https://imgur.com/SdfrE0z.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Creating users using PS script(setup exec policy to avoid unsigned script error): <br/>
<img src="https://imgur.com/qgBEbV5.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Creating users using PS script(review and run script): <br/>
<img src="https://imgur.com/mVLTTKV" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Creating users using PS script(users are created): <br/>
<img src="https://imgur.com/xUyiSCz.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Adding Windows 10 client to domain: <br/>
<img src="https://imgur.com/NBA35yf.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Sucessfully added Windows 10 client to domain(at this point client will restart): <br/>
<img src="https://imgur.com/iXLMT0X.png" height="80%" width="80%" alt="NAT network setup"/>
<br />
<br />
Login into domain using previously created user: <br/>
<img src="https://imgur.com/sGQ5X8j.png" height="80%" width="80%" alt="NAT network setup"/>

