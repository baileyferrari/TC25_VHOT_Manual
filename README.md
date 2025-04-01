# TC25_VHOT_Manual
### Create a Tableau Cloud Trial
## Step 1: Create a Tableau Cloud Trial Site (Bailey)

### 1. Set Up Your Browser Windows

1. Open your preferred web browser (e.g., Chrome, Edge, Firefox).
2. Open **two windows side-by-side**:
   - **Window 1 (Standard)**: This should be your **regular browser window**, already signed into your **preferred email account** (e.g., Gmail, Outlook, Salesforce email).
   - **Window 2 (Incognito/Private Mode)**: Open a **new incognito or private browsing window**:
     - In Chrome: Press `Ctrl+Shift+N` (Windows) or `Cmd+Shift+N` (Mac)
     - In Edge: Press `Ctrl+Shift+N`
     - In Firefox: Press `Ctrl+Shift+P` (Windows) or `Cmd+Shift+P` (Mac)

> **Why?** Using incognito mode ensures the Tableau trial sign-up process doesn’t auto-login using any saved credentials.


### 2. Navigate to the Tableau Cloud Trial Page

In the **incognito window**, go to:

👉 [https://www.tableau.com/products/trial](https://www.tableau.com/products/trial)


### 3. Fill Out the Trial Form

1. Complete the sign-up form with your details:
   - **First Name**
   - **Last Name**
   - **Company Name** – The name of your organization.
   - **Email** – Enter your preferred email address with a small modification:
     - Append `+TC25` just before the `@` symbol:
       - Example:  
         `john.doe+TC25@salesforce.com`  
         `tsmith+TC25@gmail.com`
   - **Phone Number** – Your preferred phone number.
   - **Job Role / Department / Country** – Fill these out as applicable.

2. Agree to the terms and click **Start Free Trial** (or the corresponding button).


### 4. Confirm Your Email

1. In your **standard browser window** (the one already signed in to your email):
   - Open your inbox and look for the confirmation email from Tableau (or Salesforce).
   - If you don’t see it right away, check the **Spam**, **Promotions**, or **Updates** folders.

2. Click the **confirmation link** provided in the email to activate your trial.


### 5. Set Up Your Tableau Cloud Site

1. After clicking the confirmation link, you'll be taken to a site setup screen.
2. Choose the following:
   - **Site name** (this becomes part of your Tableau Cloud URL)
   - **Username and password**

3. Submit the form. Your Tableau Cloud trial environment will be provisioned — this usually takes 1–2 minutes.


✅ **You're all set!** You now have a fully functional Tableau Cloud trial site ready to explore and use.

---

# Step 2: Upload a Data Source to Tableau Cloud (Bailey)

## 1. Download the Sample CSV File

1. Go to the GitHub repository containing the data file.
2. Locate the file named:  
   **`Sales Cloud Data.csv`**

3. Click on the file to view it.
4. Click the **Download** button (or right-click **"Raw"** and select **Save As**) to save it to your computer.

> 💾 Make sure to remember where you saved the file (e.g., your `Downloads` folder).

---

## 2. Log Into Tableau Cloud

1. In your browser, go to your Tableau Cloud site URL (e.g., `https://<your-site-name>.tableau.com`).
2. Sign in with your username and password.

---

## 3. Upload the Data Source from the Home Page

1. From the **Home** screen, locate the **"New"** button in the upper section of the page.
2. Click the **New** drop-down and select:  
   **📊 Published Data Source**

   ![Published Data Source Upload](Screenshot%202025-03-31%20at%207.56.00%E2%80%AFPM.png)

3. In the file picker window:
   - Browse to the location where you saved the `Sales Cloud Data.csv` file.
   - Select the file and click **Open** (or **Upload**).

4. Tableau Cloud will upload the CSV file and turn it into a **published data source**.

> ⏱️ Upload and processing may take a few seconds depending on your file size.

---

## 4. Confirm the Upload

1. After the upload is complete, you’ll be directed to a screen showing a preview of the data source.
2. You can now create new workbooks using this uploaded data directly in Tableau Cloud.

---

✅ **Nice work!** You’ve uploaded your CSV file as a published data source using Tableau Cloud — all through the web browser, no Desktop required.


