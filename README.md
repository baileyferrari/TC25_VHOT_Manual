# TC25_VHOT_Manual
## Sections
[Step 1: Create a Tableau Cloud Trial Site](https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-1-create-a-tableau-cloud-trial-site-bailey)

#### Step 2: Upload the "Sales Cloud Data" Data Source
#### Step 3: Create Your First Pulse Metrics
#### Step 4: Build a Tableau Dashboard

---

# Step 1: Create a Tableau Cloud Trial Site (Bailey)

## 1. Set Up Your Browser Windows

1. Open your preferred web browser (e.g., Chrome, Edge, Firefox).
2. Open **two windows side-by-side**:
   - **Window 1 (Standard)**: Your regular browser window, already signed into your preferred email account (e.g., Gmail, Outlook, Salesforce email).
   - **Window 2 (Incognito/Private Mode)**: Open a new incognito/private window:
     - In Chrome: `Ctrl+Shift+N` (Windows) or `Cmd+Shift+N` (Mac)
     - In Edge: `Ctrl+Shift+N`
     - In Firefox: `Ctrl+Shift+P` (Windows) or `Cmd+Shift+P` (Mac)

> ⚠️ We'll use the **incognito window** for all Tableau setup and access going forward. This ensures we avoid saved sessions or conflicts from existing Tableau accounts.

---

## 2. Set Up Tabs in the Incognito Window

1. In your **incognito window**, open the following two tabs:

   - **Tab 1**: Open the lab manual to follow along with this walkthrough:  
     👉 [TC25 Lab Manual - Sections](https://github.com/baileyferrari/TC25_VHOT_Manual/tree/main?tab=readme-ov-file#sections)

   - **Tab 2**: Open the Tableau Cloud Trial signup page:  
     👉 [Start Tableau Cloud Free Trial](https://www.tableau.com/products/trial)

---

## 3. Fill Out the Trial Signup Form

On the [Tableau Trial Page](https://www.tableau.com/products/trial), complete the form with the following details:

- **First Name**
- **Last Name**
- **Company Name** – Your organization or a placeholder.
- **Email** – Use your preferred email address, but **append `+TC25` just before the `@` symbol**:
  - Example:
    - `john.doe+TC25@salesforce.com`
    - `tsmith+TC25@gmail.com`
- **Phone Number** – Optional but can be filled in.
- **Job Role / Department / Country** – Select as appropriate.

✅ Check the box to agree to the terms, then click **Start Free Trial**.

---

## 4. Activate Your Tableau Account (Important!)

1. In your **standard browser window** (signed into your email), look for an email with the subject:  
   **`Tableau Software Account Activation`**

2. **DO NOT click the link directly in the email.** Instead:

   - **Right-click** the button or link in the email.
   - Select **"Copy link address"** (or similar, depending on your email provider).
   - Switch to your **incognito window** and open a **new tab**.
   - **Paste** the copied link into the address bar and hit **Enter**.

> 🛠️ **Why this step matters:**  
> Opening the activation link in incognito prevents Tableau from auto-redirecting you to an existing site. This ensures you're creating a brand-new Tableau Cloud trial site — even if you're part of a paid org or have requested a trial before.

---

## 5. Set Your Password & Finish Setup

1. Once you open the activation link in the incognito window, Tableau will recognize your email and display your username.
2. You’ll be prompted to **set a password**.

   - It must meet Tableau’s password criteria.
   - For this exercise, we are using:  
     **`DataRockstar1!`**

   > You may choose your own secure password if you'd like — this is just for simplicity during the lab.

3. Click **Submit**. Tableau will begin provisioning your site.

---

## 6. Wait for Trial Activation

- You’ll see a message that says:  
  **“Activating your trial site...”**
- This process takes **1–2 minutes**.
- When finished, you’ll be automatically redirected to your new **Tableau Cloud site homepage**.

---

✅ **Done!** You’ve successfully created your Tableau Cloud trial site. We’ll use this site throughout the rest of the lab.


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


