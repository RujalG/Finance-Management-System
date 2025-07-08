# Finance-Management-System
# The Numo – Organization Finance Management System

Hello everyone!  
My name is **Rujal Harshad Gandhi**, and this is a full-stack web application I’ve developed called **The Numo** – an organization finance management system.

## 📌 Project Inspiration

This application was inspired by a real-life problem faced by my father while managing finances in a Jain organization. The need was for a tool to track **category-wise balances**, manage records efficiently, and share updates with transparency.

In Jain tradition, donations under a specific category (e.g., education) must only be used for that category. Misusing funds is considered a **pap (sin)**. The Numo is built to simplify, safeguard, and honor these practices.

--
## 🌐 Deployed at

[![Live Site](https://img.shields.io/badge/Live-thenumo.rujal.in-brightgreen?style=flat-square)](https://thenumo.rujal.in)

---
## 📺 Watch the Demo

👉 [YouTube Demo Video](https://www.youtube.com/watch?v=qKvNvjwlvJY&t=12s)

---

## 🌐 My Portfolio

🔗 [rujal.in](https://www.rujal.in)  
(or replace with your custom portfolio project link)

---

## 🛠️ Tech Stack

- **Frontend**: HTML, Bootstrap, Custom CSS (Responsive UI)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

---

## 🔐 Core Functionalities

- Secure login & signup (with forgot password feature)
- Dashboard with category-wise financial overview
- Add, view, edit, and delete incoming and outgoing payments
- Each payment has:
  - Main category
  - Amount, purpose, comments
  - Optional special comment (searchable)
- Receipt generation, printing, and Excel export
- Weekly email reports to registered users
- Feedback form in footer (emails sent directly)
- Dark/light mode toggle
- Route protection and flash messages across the app

---

## 🔎 Search & Filters

- Filter payments by:
  - Name
  - Payment Status
- Search by **special comment** (e.g., "education camp") to filter categorized transactions
- View person-wise payment history and export or print it

---

## 👥 Person & Category Management

- Add/Search/Update person profiles
- Add/Delete categories (used ones can't be deleted)
- Refresh categories post-edit

---

## 📧 Email Integration

- Weekly reports summarizing all incomes and expenses per category
- Reset password via email
- Feedback emails from the footer

---

## 💡 Pending Enhancements

- Confirmation prompt before saving payments
- Auto-refresh categories post-deletion
- Secure reset password with expiring unique token

---

## 🎬 Testing Overview

- User Signup/Login flows
  Navigate to Home Page
  ![image](https://github.com/user-attachments/assets/4ce0e127-64e8-43f9-9122-1f02f6247cdf)
  Click on Sign Up button to create account
  ![image](https://github.com/user-attachments/assets/034e7940-20d4-4a05-b1cb-6c781f1528c9)
  Sign up page
  ![image](https://github.com/user-attachments/assets/c2fcc84a-f0d9-49e3-8389-6b639e28a9b1)
  Required data
  ![image](https://github.com/user-attachments/assets/0b0b9011-492e-4e21-9447-f955639ec3f0)
  Click sign up
  ![image](https://github.com/user-attachments/assets/0f8e1e7d-7b91-4cc6-b2af-295d93bc20cc)
  Success sign up
  ![image](https://github.com/user-attachments/assets/358478f3-6c9a-4303-a041-826d4d7bdfef)
  Forward to Login
  ![image](https://github.com/user-attachments/assets/bbca26d1-64a8-475e-af4e-409ca8efed51)
  Login page
  ![image](https://github.com/user-attachments/assets/f4682f3f-c22a-4047-813b-4f16943cc056)
  Login
  ![image](https://github.com/user-attachments/assets/9e0347e2-8793-431e-9143-a65634f01230)
  Forget password
  ![image](https://github.com/user-attachments/assets/2a42f68b-d085-4f44-8eb2-2d5c621fa5de)
  Forget password page
  ![image](https://github.com/user-attachments/assets/3071412b-e2f3-402f-b644-59063785fffc)
  Send link to gmail
  ![image](https://github.com/user-attachments/assets/f6188f4d-4d20-4adf-8947-1e252753bb41)
  New password
  ![image](https://github.com/user-attachments/assets/97ce95ac-7791-4d2c-806b-b984890ca029)
  Password updated
  ![image](https://github.com/user-attachments/assets/216f0e1c-5927-46d3-a3dc-996351163eed)
  Login success
  ![image](https://github.com/user-attachments/assets/5f67842f-ca93-40f7-81cc-eed2a9652ab7)

- Dashboard and navigation
  ![image](https://github.com/user-attachments/assets/91224f52-2b38-40a5-a06f-c5e3e56af16a)
  Day mode
  ![image](https://github.com/user-attachments/assets/f35e830c-f6ff-4420-99c3-e842aa67c296)
  Night mode
  ![image](https://github.com/user-attachments/assets/89a91e06-70d6-4685-bdcb-a76c75c2bf4e)

- Creating incoming payments
  ![image](https://github.com/user-attachments/assets/c1fc39d3-fb92-48fc-b0e8-7b9485378350)
  ![image](https://github.com/user-attachments/assets/2770951e-bb85-4d11-87e5-020a63e45a6c)
  Create new member for payment
  ![image](https://github.com/user-attachments/assets/37dbdf76-9d18-4208-98c5-c3b456b01924)
  ![image](https://github.com/user-attachments/assets/9a2feb9a-7d6d-4b2f-8c65-914b1eba5fc3)
  ![image](https://github.com/user-attachments/assets/fde89430-0d20-41f2-a5db-aef39419ff2a)
  Create new category for payment
  ![image](https://github.com/user-attachments/assets/ac3bcf2b-8fda-4814-9fc2-8c3f4fd29460)
  ![image](https://github.com/user-attachments/assets/dec87878-0b07-4bc7-a842-870e62503821)
  ![image](https://github.com/user-attachments/assets/b29637ac-de63-483e-adff-1e53eea7bf24)
  Creating new incoming payment with paid option
  ![image](https://github.com/user-attachments/assets/fa4f4762-822c-4584-a3c3-4b14447f4740)
  Creating new incoming payment with unpaid option
  ![image](https://github.com/user-attachments/assets/4e671bfc-9a57-4d84-a12c-fc6c9e4edd9e)
  Since this payment is unpaid, the amount does not reflects on the dashboard
  ![image](https://github.com/user-attachments/assets/29636a72-5521-4266-af86-7c2121a8459a)
  New receipt create,
  On dashboard, in the summary report the amount has be updated for respectful category
  ![image](https://github.com/user-attachments/assets/77164ac7-74f3-4fa2-8864-3b430683318d)

- Creating outgoing payments
  ![image](https://github.com/user-attachments/assets/3dce568f-4d82-4fdd-ac92-a01d7e7f531c)
  ![image](https://github.com/user-attachments/assets/f8123631-536b-4211-bdc0-afb7de0f1b21)
  ![image](https://github.com/user-attachments/assets/aa755b5e-03f7-4b6f-8cf6-5e92f6f0c90e)
  Outgoing payment success,
  Since this is outgoing, amount is deducted from education category.
  ![image](https://github.com/user-attachments/assets/e4e60aa6-f5ff-41e5-87bf-ef99118909d9)
  Showing outgoing payment
  ![image](https://github.com/user-attachments/assets/cd170f70-2864-4dcb-a1ac-946ca0862b69)
  
- Creating new person profiles
  ![image](https://github.com/user-attachments/assets/d479aa32-fa33-4068-a108-bfeff73b37e1)
  Search all person profile
  ![image](https://github.com/user-attachments/assets/56b4bc72-b154-402b-b14f-7b32676ac483)
  ![image](https://github.com/user-attachments/assets/144b5b46-f262-4f47-bb23-7d22768138f4)
  Showing list of payment
  ![image](https://github.com/user-attachments/assets/09aaaf5a-51ec-492e-aa93-416a413b8a2d)
  ![image](https://github.com/user-attachments/assets/c3909898-6899-4c2b-9967-9f81dca4d5b1)
  List of all incoming and outgoing payments
  ![image](https://github.com/user-attachments/assets/8bbbbbcd-5fc6-4f38-8176-62b547764f76)
  Searching payments individually .
  ![image](https://github.com/user-attachments/assets/358db65e-6e8d-4325-a281-87e553ec93a9)
  ![image](https://github.com/user-attachments/assets/42fb95f3-72a8-4922-834f-03f1a0df502d)
  
- Viewing, editing, deleting, and printing receipts
  Editing unpaid into paid
  ![image](https://github.com/user-attachments/assets/30f3f1da-0918-4b7f-a3a9-4904e482d64c)
  ![image](https://github.com/user-attachments/assets/a92edb24-b52c-45ba-b655-95bf89f7fd88)
  Since the receipt is paid now, amount is reflecting on dashboard.
  ![image](https://github.com/user-attachments/assets/30d7c7e3-2896-4dc4-b469-e25e08790d37)
  Editing/updating payment
  ![image](https://github.com/user-attachments/assets/cde113db-b525-44fa-bbb6-d5d20f470599)
  After updating, amount is deducted from respective category.
  ![image](https://github.com/user-attachments/assets/d14a5c9f-93a7-4e92-b2f2-7018d7f7522f)
  Deleting category and refreshing page
  ![image](https://github.com/user-attachments/assets/d8abf7a9-3ffc-444d-87d1-02dc58ba51fb)
  ![image](https://github.com/user-attachments/assets/539133ae-8919-499e-88b4-2784a8f6af0c)
  Since category is in use, it is not deleted.
  ![image](https://github.com/user-attachments/assets/21e5e330-c9f6-4220-8187-008141f66480)
  Deleting category and refreshing page
  ![image](https://github.com/user-attachments/assets/92c800b8-4763-4307-8c2c-6e429ec9c825)
  Since this category is not in use, it is deleted
  ![image](https://github.com/user-attachments/assets/ebe717f9-1034-48ab-bfe5-714e7d8ce92f)
  Printing incoming payment
  ![image](https://github.com/user-attachments/assets/f6514a8a-87fd-46ae-9ce5-f061e223238c)
  ![image](https://github.com/user-attachments/assets/adcf7a64-af43-4d3c-bec3-c910b60f0a78)
  Printing outgoing payment
  ![image](https://github.com/user-attachments/assets/63201ff2-0bbb-476f-ad6e-b73a6e19f585)
  ![image](https://github.com/user-attachments/assets/55e83e79-abf6-41b1-98e4-e304731f4a2d)
  ![image](https://github.com/user-attachments/assets/d4d14210-eb4d-4936-8ac9-759f67eb9681)
  Saving list of payment
  ![image](https://github.com/user-attachments/assets/8b6c5d65-7efe-4314-9a37-1b34c24397e2)
  ![image](https://github.com/user-attachments/assets/29aafed1-acd1-45b0-8074-1891ea926230)
  Printing list of payments
  ![image](https://github.com/user-attachments/assets/302d3050-7701-43d4-a0a8-c7268f21216d)
  ![image](https://github.com/user-attachments/assets/46df4928-9842-4d17-8551-db019b4a2305)
  ![image](https://github.com/user-attachments/assets/d046fe75-316a-4032-b1e0-d56249f741ef)
  ![image](https://github.com/user-attachments/assets/2d3e3913-d538-4e06-bd27-1e1e9fd89539)
  ![image](https://github.com/user-attachments/assets/3e62ca0e-9e35-4764-8e9e-179804e069fd)
  A weekly mail is triggered to all registered user’s email ID with all the payment details.
  ![image](https://github.com/user-attachments/assets/73d0508b-598d-4066-a5e1-3503e7aa98f0)
  Receipt
  ![image](https://github.com/user-attachments/assets/3455d7b3-60cb-4fa8-9afa-62c4dc943dd5)
  Payment
  ![image](https://github.com/user-attachments/assets/a99d06e3-1f36-439f-b9d9-240a736b05fe)
  
- Special comment usage
  Creating incoming and outgoing payment with searchable comments
  ![image](https://github.com/user-attachments/assets/f0a4b64d-ca89-427e-aee6-36fa7cfa5587)
  ![image](https://github.com/user-attachments/assets/03f1970b-0a1d-4c8a-b4f1-c160f3f2d415)
  Searchable comment
  ![image](https://github.com/user-attachments/assets/56491b0e-b34a-4e3a-95d7-569cae6855af)
  ![image](https://github.com/user-attachments/assets/a79c4b72-f69d-49c8-a324-60b1df0c21d5)
  ![image](https://github.com/user-attachments/assets/bcbc284d-e75b-4561-83ae-c8c958eec7f8)
  Since the outgoing payment amount is more than incoming payment amount of eduction fund,
  the dashboard is showing final amount in negative in eduction fund.
  ![image](https://github.com/user-attachments/assets/2e34775f-2fef-4509-8da2-7d219d427c80)
  
- Route protection and flash notifications

---

## 🚀 Conclusion

**The Numo** is a tailored solution that combines **technical accuracy** with **spiritual responsibility**.  
It's a practical tool for real organizations and a showcase of my full-stack development skills.

> 💬 *The app is currently not deployed due to ongoing work on security. However, the complete codebase, documentation, and demo video are available below.*

---


## 📇 Connect with Me

**Rujal Harshad Gandhi**  
📧 rujalgandhi66@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rujal-gandhi)  
📁 GitHub: https://github.com/RujalG/

---


