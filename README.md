<div align="center">
   <img src="https://github.com/user-attachments/assets/fe9469ea-7de5-4c9f-8795-e76fcab7999f" alt="Azure logo" width="100%" />
   <p><em>Hands-on lab: create, connect to and clean up a window VM in Microsoft Azure.</em>/p>
</div>





# Microsoft Azure Virtual Machine Deployment & Management


## Project Summary
This project is a **step-by-step tutorial and demonstration** of creating, configuring, connecting to, and cleaning up an Azure Virtual Machine (VM). It was designed as a **hands-on cloud computing lab** to build technical skills and demonstrate familiarity with Azure services. The project follows industry-relevant steps for provisioning infrastructure in the cloud and aligns with common tasks an IT professional might perform in a real work environment.

**Type:** Technology Implementation & Walkthrough  
**Languages Used:** N/A (GUI-based configuration; can be extended with PowerShell)  
**Environments Used:** Microsoft Azure, Windows 10 (local environment)  
**Technologies/Services Used:** Azure Portal, Azure Resource Groups, Azure Virtual Machines, Remote Desktop Protocol (RDP)  

---
## ⚠️ Note  

This walkthrough covers the **basic standard settings** for creating and starting a Virtual Machine in Microsoft Azure.  

If you’re interested in more **advanced configurations** (such as scaling, custom networking, or automation with scripts), I plan to cover those in a future project/video.  

For now, this guide focuses on the essentials to help you quickly get a VM up and running.




## 🎥 Video Demonstration

<div align="center">
  <a href="https://www.youtube.com/watch?v=LRXmCf9SkDI" target="_blank">
    <img src="https://img.youtube.com/vi/LRXmCf9SkDI/maxresdefault.jpg" alt="Azure VM Project Video" width="80%" />
  </a>
  <p><em>Watch the full video demonstration — or follow along below with the step-by-step screenshots.</em></p>
</div>



Follow step 1 once you created an account with Microsoft Azure.
### Step 1 — Microsoft Azure Home Page
Start from the **Azure Portal home page**.  
We’re going to create a **Resource Group** first.  
A resource group is like a folder where you keep everything organized.  
Anything you create in Azure — like Virtual Machines, Networking, Databases, or AI services — will belong to a resource group. This helps keep resources managed and grouped together.

![Step 1](https://github.com/user-attachments/assets/1be5a8a6-2887-4359-abaf-8f4862288c39)


---

### Step 2 — Create a Resource Group
Click on **Resource groups** in the left panel → select **+ Create**.  
- Subscription: Choose **Azure subscription 1**.  
- Resource Group Name: Enter a name (e.g., `my-virtual-machine-01`).  
- Region: Select the region closest to you.  
Click **Review + Create**, then press the **Create** button.

![Step 2](https://github.com/user-attachments/assets/e096c440-0458-465e-8e6e-1d2e4bea0bc9)

![AZURE14](https://github.com/user-attachments/assets/3c5fb255-7251-4987-9420-96ed62c53512)
![AZURE15](https://github.com/user-attachments/assets/6cac301e-6685-475a-b812-a95d9be5c375)
![AZURE16](https://github.com/user-attachments/assets/def3c398-a6da-47f3-86f6-e2392e5d425f)


---

### Step 3 — Navigate to the Virtual Machines Service
From the Azure dashboard, open the **Virtual Machines** service.

![STEP3](https://github.com/user-attachments/assets/408d671e-8c15-4f50-a6f1-8bc3dfcd6585)

---

### Step 4 — Start the VM Creation Process
Click **+ Create** → **Azure Virtual Machine** to begin setting up your new VM.

![STEP4](https://github.com/user-attachments/assets/7ad61210-faff-436d-8f9e-f6ad16262f30)

![AZURE19](https://github.com/user-attachments/assets/827d20f1-d45d-45df-81cb-b97521e38725)


---

### Step 5 — Configure Basic Settings
Choose your subscription, the resource group you just created, VM name, and region.

![STEP 5](https://github.com/user-attachments/assets/d8bd5eca-ef10-44bf-b4e7-4e007b8da6a2)



---

### Step 6 — Select the Operating System Image
Pick your desired OS image (e.g., Windows Server 2019).
![STEP 6](https://github.com/user-attachments/assets/d23ba1de-9320-478a-ae81-1e165aa35e1f)



---

### Step 7 — Choose the VM Size
Select the VM size based on performance requirements and available free tier.

![STEP 7](https://github.com/user-attachments/assets/c2602901-07b6-4402-9354-54192f1ba37d)


---

### Step 8 — Set Administrator Credentials & don't forget to check the box if not its not going to run
Create a secure username and password for remote access.


![STEP 8](https://github.com/user-attachments/assets/9feeefbd-6a9c-4322-8cdf-dedbe6356bb8)

---

### Step 9 — click review + create
Its going to load wait until validation passed shows after click on create button

![AZURE25](https://github.com/user-attachments/assets/75f951ab-2a38-441a-9313-952c181647e9)


---

### Step 10 — Deployment in Progress
Azure begins provisioning your virtual machine.


![AZURE26](https://github.com/user-attachments/assets/5622773a-f008-4448-a5fe-1428cf56dcd7)

---

### Step 11 — Deployment Complete
The VM is successfully created and ready for use.


![AZURE27](https://github.com/user-attachments/assets/d430b1b0-8374-4435-8d02-d857d6a381d5)

---

### Step 12 — Access VM 
Open the VM's overview page to see status and connection details.


![AZURE28](https://github.com/user-attachments/assets/be2d51db-941f-4e67-9e38-de67b46eaae0)


---

### Step 13 — Copy the Public IP Address
Locate and copy the public IP for your VM.


![AZURE29](https://github.com/user-attachments/assets/7e9c3074-93c3-4618-9aa0-266b36cc461b)
---

### Step 14 — Open Remote Desktop Connection
Launch **Remote Desktop Connection** on your local machine.


![AZURE30](https://github.com/user-attachments/assets/9b854970-abba-43e8-befd-19c8cf2dfc4a)

---

### Step 15 — Enter the VM's Public IP
Paste the copied IP address into the RDP client.


![AZURE31](https://github.com/user-attachments/assets/73dcae91-d24d-484d-9e24-a5a40fe5998a)

---

### Step 16 — Enter Administrator Username & Password
Type in the password for the admin account.


![STEP 16](https://github.com/user-attachments/assets/dee57ddd-5897-4d26-98b2-ada93661688e)

---

### Step 17 — Accept Certificate Warning
Confirm the security prompt to proceed.


![AZURE33](https://github.com/user-attachments/assets/aa0ec66d-b04a-46fe-b07f-310dda5d87ff)

---

### Step 18 — VM Desktop Loads
You are now connected to the VM's desktop environment.


![AZURE34](https://github.com/user-attachments/assets/b55f4873-b9f6-41ce-9063-36d9c79bc0a7)

---

### (HOW TO SAVE CREDIT) Step 19 — Go to the Resource Group
Open the resource group containing the VM.


![AZURE37](https://github.com/user-attachments/assets/00b9eac9-5c5c-44b9-bb20-f7fa24369225)

---

### (HOW TO SAVE CREDIT) Step 20 — Delete the Resource Group
Choose to delete the resource group to remove all associated resources.


![AZURE38](https://github.com/user-attachments/assets/70af3c4b-cd94-4f4c-927c-608c46b3ad78)

---


### (HOW TO SAVE CREDIT)Step 21 — Deletion in Progress
Azure removes the VM and all linked resources.


![AZURE39](https://github.com/user-attachments/assets/d34f8593-177f-47e6-a358-642ba9c1dc88)
![AZURE40](https://github.com/user-attachments/assets/eadb4f27-0053-432d-a566-2e8f35748c75)

