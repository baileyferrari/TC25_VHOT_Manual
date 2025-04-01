# TC25_VHOT_Manual
## Lab Sections
- [Step 1: Create a Tableau Cloud Trial Site](https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-1-create-a-tableau-cloud-trial-site-bailey)

- **Step 2: Configure Your Tableau Cloud Site**

- **Step 3: Upload "Sales Cloud Data" as a Published Data Source**

- **Step 4: Create Pulse Metrics**
  - Open Pipe  
  - Win Rate  
  - Average Days to Close

- **Step 5: Create Visualizations with Tableau Agent**
  - Top Accounts  
  - Top Sellers  
  - Opportunity Details

- **Step 6: Pull Everything Together into a Dashboard!**
  - Sales Overview

- **Step 7: Publish & Interact**


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

<br>

## 2. Set Up Tabs in the Incognito Window

In your **incognito window**, open the following two tabs:

- **Tab 1**: Open the **GitHub repository** for this lab:  
  👉 [TC25 Lab Repository](https://github.com/baileyferrari/TC25_VHOT_Manual)

  > This repo contains everything you'll need for the session, including:
  > - The full **lab manual** to follow along step-by-step
  > - A **CSV data source** file that we’ll upload into Tableau Cloud later

- **Tab 2**: Open the Tableau Cloud Trial signup page:  
  👉 [Start Tableau Cloud Free Trial](https://www.tableau.com/products/trial)

<br>

## 3. Set Up Your Standard Window

In your **standard (non-incognito)** browser window:

- Make sure you are **signed into your email account** (e.g., Gmail, Outlook, or your Salesforce email).
- You only need **one tab open** in this window.
- This is the inbox where you’ll receive the **Tableau Software Account Activation** email.

> 💡 Keep this window open — you’ll switch to it briefly during the activation step.

<br>

## 4. Fill Out the Trial Signup Form

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

<br>

## 5. Activate Your Tableau Account (Important!)

1. In your **standard browser window** (signed into your email), look for an email with the subject:  
   **`Tableau Software Account Activation`**

2. **DO NOT click the link directly in the email.** Instead:

   - **Right-click** the button or link in the email.
   - Select **"Copy link address"** (or similar, depending on your email provider).
   - Switch to your **incognito window** and open a **new tab**.
   - **Paste** the copied link into the address bar and hit **Enter**.

> 🛠️ **Why this step matters:**  
> Opening the activation link in incognito prevents Tableau from auto-redirecting you to an existing site. This ensures you're creating a brand-new Tableau Cloud trial site — even if you're part of a paid org or have requested a trial before.

<br>

## 6. Set Your Password & Finish Setup

1. Once you open the activation link in the incognito window, Tableau will recognize your email and display your username.
2. You’ll be prompted to **set a password**.

   - It must meet Tableau’s password criteria.
   - For this exercise, we are using:  
     **`DataRockstar1!`**

   > You may choose your own secure password if you'd like — this is just for simplicity during the lab.

3. Click **Submit**. Tableau will begin provisioning your site.

<br>

## 7. Wait for Trial Activation

- You’ll see a message that says:  
  **“Activating your trial site...”**
- This process takes **1–2 minutes**.
- When finished, you’ll be automatically redirected to your new **Tableau Cloud site homepage**.

<br>

✅ **Done!** You’ve successfully created your Tableau Cloud trial site. We’ll use this site throughout the rest of the lab, be sure to keep this tab open!

<br>

---

# Step 2: Configure Your Tableau Cloud Site

Now that your trial site is activated, let’s configure it to unlock powerful AI and agentic capabilities we’ll be using throughout the lab.

<br>

## 1. Open Site Settings

1. From the **Home** page of your Tableau Cloud site, scroll to the very bottom of the left-hand navigation.
2. Click **Settings**.

<br>

## 2. Enable AI Features (General Tab)

1. The **Settings** page will default to the **General** tab.
2. Under the section titled **“Turn on AI in Tableau by feature area”**, **check every checkbox** that appears — these enable:
   - Tableau Pulse summaries
   - Semantic question matching
   - Pulse Discover
   - Conversational Web Authoring
   - Tableau Prep suggestions

3. Your screen should look like this:

   ![Enable AI Features](Screenshot%202025-03-31%20at%208.57.03%E2%80%AFPM.png)

4. Click the **blue "Save"** button in the upper right corner of the screen to apply these settings.

<br>

## 3. Add Viz Extension URL (Extensions Tab)

We’re going to enable a powerful new capability called **viz extensions**, which makes it easier to build granular, dynamic visualizations like detailed text tables.

1. While still in **Settings**, click on the **“Extensions”** tab at the top.
2. Under **"Enable Specific Extensions"**, do the following:
   - Click the **`+ Add URL`** button.
   - Paste the following URL in the **Extension URL** field:  
     ```
     https://tableau-vizext-prod.s3.us-east-2.amazonaws.com/table-network/table.html
     ```
   - Under **Full Data Access**, change the dropdown to **Allow**.
   - Under **User Prompts**, change the dropdown to **Hide**.

3. Your configuration should look like this:

   ![Viz Extension Settings](Screenshot%202025-03-31%20at%208.57.16%E2%80%AFPM.png)

4. Click the **blue "Save"** button in the upper right to apply the changes.

<br>

✅ **Nice job!** Your Tableau Cloud site is now fully configured for AI-driven insights and advanced reporting with viz extensions.

<br>

---

# Step 3: Upload "Sales Cloud Data" as a Published Data Source

Next, we’ll upload the **Sales Cloud Data** file into Tableau Cloud to use in our exercises. This process creates a **Published Data Source** directly from the browser — no Tableau Desktop required.

## 1. Download the CSV File

In **Tab 1** of your incognito window (where the GitHub repo is open), locate and download:  
**`Sales Cloud Data.csv`**

> 💾 Save this file somewhere easy to find, like your **Downloads** folder.

<br>

## 2. Start the Upload Process

Go back to your Tableau Cloud **Home** page.  
Click the **“New”** drop-down menu at the top.  
Select **“Published Data Source”** from the list.

<br>

## 3. Connect to the CSV File

In the **Connect to Data** window that opens:  
Toggle to the **"Files"** tab at the top.  
Click to **browse for a file** and select the `Sales Cloud Data.csv` file you downloaded.

<br>

## 4. Publish the Data Source

Once the data loads, click **“Publish As...”** in the top-right corner.  
In the popup window:
- Name the data source: **`Sales Cloud Data`**
- Keep the default project folder selected.

Click **Publish**.

<br>

## 5. Finish & Return to Home

If you see a success message, acknowledge or close any pop-ups.  
In the upper left corner, click **“File”** → **“Close”** to return to your Tableau Cloud **Home** page.

✅ **Success!** You’ve now uploaded and published your first data source to Tableau Cloud. You’ll use this dataset in the next steps of the lab.

<br>

---

