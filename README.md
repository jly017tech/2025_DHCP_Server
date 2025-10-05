<h1>2025 - DHCP Server</h1>


<ul>
  <li>Windows Server 2022</li>
  <li>Installed DHCP Server</li>
</ul>


<h1>Creating scope</h1>


<img width="1389" height="760" alt="image" src="https://github.com/user-attachments/assets/cc79acca-10ab-433c-8b89-21c1978c9ea8" />



<p>
  After installing DHCP server, I open DHCP server and went to right click New Scope. I name Husky Scope and wrote in description said Range addreses from 172.168.22.100 - 172.168.22.200
</p>



<h1>IP Address Range</h1>

<img width="1361" height="718" alt="image" src="https://github.com/user-attachments/assets/5f423993-c8e9-4513-addf-35b956545a8b" />

 <p>I use the IP addresses I mention from Creating scope section and put 172.168.22.100 in Start Address and 172.168.22.200 in End.
 Lastly, I put subnet to 24 and it is equivalent as 255.255.255.0</p>



<h1>Add Exclusion addresses </h1>

<img width="1380" height="714" alt="image" src="https://github.com/user-attachments/assets/0962d643-9084-4e77-ba21-b79de6cedafb" />


<p>I add 172.168.22.102 from my Windows Server so it doesn't accidentally detect by DHCP server</p>
