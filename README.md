# born 2 be root tutorial by adib
# index
1. [Download The Debian Iso 🐧](#1--download-the-iso-debian-)
2. [Setup Debian In Virtual Machine](#2--setup-virtual-machine-)
3. [How to install debian](#3--installation-debian-)


## 1- _Download the iso Debian_ 🐧
to dowload debian iso [CLICK_HERE](https://www.debian.org/download.en.html)

![393501208-dd172932-4970-424f-bd78-336c4b11a02e](https://github.com/user-attachments/assets/481e2a0e-66db-4005-bf6d-7ae74265b2a1).

## 2- _setup virtual machine_ 🔨

first thing if you don't have virtualization software you need to dowload it first in this tutorial we will use [Virtual Box](https://www.virtualbox.org/wiki/Downloads)

<img width="988" alt="393501208-dd172932-4970-424f-bd78-336c4b11a02e" src="https://github.com/user-attachments/assets/e4309542-ebd3-40e3-ae74-dba11366d2c0">

<h4>I After downloading VirtualBox, open it and click 'New'.</h4>

![393501208-dd172932-4970-424f-bd78-336c4b11a02e](https://github.com/user-attachments/assets/75911c58-f1a6-4d78-87cf-3701a5f27c7d)

<h4>II Name and Machine Folder Setup</h4>
In the Name box, enter any name you prefer. I chose born_to_be_root.

In the Machine Folder, I selected goinfre/yadib/born_2_be_root. This is important on shared or limited storage systems to avoid running out of memory. (If you're working on your own system, you can use any folder or storage location you prefer.)

Type: Select Linux.

Version: Select Debian 64-bit.

![Screen Shot 2024-12-07 at 11 19 20 AM](https://github.com/user-attachments/assets/681a4498-25e5-4cce-9136-c3c2afee4847)

<h4>III Select the total RAM you want to reserve for this machine, and then choose the button "Create a virtual hard disk now."  "And click create"</h4>

![Screen Shot 2024-12-07 at 11 19 20 AM (1)](https://github.com/user-attachments/assets/96e46d5f-edef-476e-b758-84480cc3d971)
![image](https://github.com/user-attachments/assets/43a0d6c6-de39-45aa-a7d1-737a71aa5267)

<h4>IV. File Size:</h4>

. Set the file size to 12 GB if you're working on the project without the bonus.

. If you're working on the bonus part of the project, set the file size to 30.80 GB.

. Then, select VDI (VirtualBox Disk Image) since we’re working with an ISO file, and choose Dynamically Allocated storage.

. and then Click Create.

![image](https://github.com/user-attachments/assets/72b3bab8-06c4-4eb4-85e5-0c46cdca7f51)

<h4>Configuring Storage and ISO File</h4>

First, click on Settings.

![Screen Shot 2024-12-07 at 12 23 29 PM](https://github.com/user-attachments/assets/ce3c0ca5-f7ed-4453-a4fe-0fa68bc1ecfa)

Second, click on storage

<img width="652" alt="Screen Shot 2024-12-07 at 12 28 32 PM" src="https://github.com/user-attachments/assets/08e732b6-9d5c-4985-a125-83c12c0259b8">

Third, choose the Empty button and follow the steps shown in the screenshot below.

<img width="962" alt="Screen Shot 2024-12-07 at 12 31 21 PM" src="https://github.com/user-attachments/assets/af1d2a12-d3f9-4f22-9184-00291b690d1d">

Fourth, choose the Debian ISO and click Open.

<img width="801" alt="Screen Shot 2024-12-07 at 12 34 46 PM" src="https://github.com/user-attachments/assets/dfded3de-7016-4531-8f7f-54efcbb17cc6">

Finaly, click OK.

<img width="647" alt="Screen Shot 2024-12-07 at 12 37 18 PM" src="https://github.com/user-attachments/assets/4c17ee57-a2c0-4d19-9068-1888c43e0be6">

## 3- _Installation debian_ 🔨

first, click start

<img width="1282" alt="Screen Shot 2024-12-07 at 3 08 51 PM" src="https://github.com/user-attachments/assets/a68aec87-e0d3-4167-bea6-2305c63f40c4">

Second, to adjust the window size, follow the steps in the photo below.

<img width="695" alt="Screen Shot 2024-12-07 at 3 14 34 PM" src="https://github.com/user-attachments/assets/7a97ced8-935f-431f-8c4a-923d41612a7b">

Third, move to 'Install' by clicking the down arrow key (↓), And press the Enter key on the keyboard.

![image](https://github.com/user-attachments/assets/8473a69e-e408-4a13-80ea-0d48532663f7)

Next, choose the language you want

![image](https://github.com/user-attachments/assets/6462ba46-9f22-4bf8-b1d5-4b5ee9827e6d)

Next, choose the country where you live. 

![image](https://github.com/user-attachments/assets/69cc895c-c193-476c-9de9-4d343177f5b9)

Next, choose your preferred keyboard language.

![image](https://github.com/user-attachments/assets/e19e5c59-ee5d-4a06-9a96-59fc0bd6d0c3)

Next, in the host name it must be your login + 42 like (name42) and press The Enter button

![image](https://github.com/user-attachments/assets/07168d9a-8fb9-49ac-bc7c-f16406468d95)

Next, in domain name don't write anything and press The Enter key on the keyboard

![image](https://github.com/user-attachments/assets/96947a7e-4584-4b57-81bd-8a2692584683)

Next, enter a strong password that you won't forget and write it down on a piece of paper because you will need it in the future (إن شاء الله).

If you want to see your password, move to the next box by pressing the 'TAB' or 'Arrow' keys and press the 'Space' button.

when you finish presss the "Enter" Button .

![image](https://github.com/user-attachments/assets/a5dc3926-be0f-4cae-8760-15299029dbcb)

Re-enter the password and press the 'Enter' button.

![image](https://github.com/user-attachments/assets/115b0e74-b506-4ebe-b451-543d5d878c1f)


Here, enter your Intra login name, as specified in the subject. They require creating a user different from 'root,' and it must be your login name. After entering it, press the 'Enter' button.

![image](https://github.com/user-attachments/assets/3f9357fa-3a08-4bef-8245-5d99ab7d7ff1)

Repeat your Intra login name.

![image](https://github.com/user-attachments/assets/a0f2dc09-8f1d-4b9d-b197-694fbd5c0735)

Set up a password for the user.

![image](https://github.com/user-attachments/assets/95edf88a-a8ca-4a0e-8207-7ca9e3f5acf7)

Re-enter the password .

![image](https://github.com/user-attachments/assets/b5ab2e7a-cb4e-48eb-bb3d-9c9aae0a1b71)




