# TC25_VHOT_Manual
## Lab Sections
- **[Step 1: Create a Tableau Cloud Trial Site](https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-1-create-a-tableau-cloud-trial-site)**

- **[Step 2: Upload "Sales Cloud Data" as a Published Data Source](https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-2-upload-sales-cloud-data-as-a-published-data-source)**

- **[Step 3: Create Pulse Metrics](https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-3-create-pulse-metrics)**
  - Open Pipe  
  - Win Rate  
  - Average Days to Close

- **[Step 4: Create Advanced Visualizations](https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-4-create-advanced-visualizations)**
  - Open Pipeline by Sales Rep
  - Accounts by Stage
  - Opp by Amount

- [**Step 5: Pull Your Metrics & Visualizations into a Dashboard**](https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-5-pull-your-metrics--visualizations-into-a-dashboard)
  - Sales Overview

- [**Step 6: Publish & Interact**](https://github.com/baileyferrari/TC25_VHOT_Manual/tree/main?tab=readme-ov-file#step-6-publish--interact)

- **[Step 7: OPTIONAL / SELF-PACED: Enable Your Tableau Cloud Site with Advanced AI]**(https://github.com/baileyferrari/TC25_VHOT_Manual/blob/main/README.md#step-7-optional--self-paced-enable-your-tableau-cloud-site-with-advanced-ai)

- [**Step 8 - OPTIONAL / SELF-PACED: Create Visualizations with Tableau Agent**](https://github.com/baileyferrari/TC25_VHOT_Manual/tree/main?tab=readme-ov-file#optional--self-paced---step-8-create-visualizations-with-tableau-agent)

---

## Step 1: Create a Tableau Cloud Trial Site

### 1. Set Up Your Browser Windows

1. Open your preferred web browser (e.g., Chrome, Edge, Firefox).
2. Open **two windows side-by-side**:
   - **Window 1 (Standard)**: Your regular browser window, already signed into your preferred email account (e.g., Gmail, Outlook email).
   - **Window 2 (Incognito/Private Mode)**: Open a new incognito/private window:
     - In Chrome: `Ctrl+Shift+N` (Windows) or `Cmd+Shift+N` (Mac)
     - In Edge: `Ctrl+Shift+N`
     - In Firefox: `Ctrl+Shift+P` (Windows) or `Cmd+Shift+P` (Mac)

> We'll use the **incognito window** for all Tableau setup and access going forward. This ensures we avoid saved sessions or conflicts from existing Tableau accounts.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img1.png)

</details>

<br>

### 2. Set Up Tabs in the Incognito Window

In your **incognito window**, open the following two tabs:

- **Tab 1**: Open the **GitHub repository** for this lab:  
  👉 [TC25 Lab Manual](https://github.com/baileyferrari/TC25_VHOT_Manual)

  > This repo contains everything you'll need for the session, including:
  > - The full **lab manual** to follow along step-by-step
  > - A **CSV data source** file that we’ll upload into Tableau Cloud later

- **Tab 2**: Open the Tableau Cloud Trial signup page:  
  👉 [Start Tableau Cloud Free Trial](https://www.tableau.com/products/trial)

<br>

### 3. Set Up Your Standard Window

In your **standard (non-incognito)** browser window:

- Make sure you are **signed into your email account** (e.g., Gmail, Outlook, or your Salesforce email).
- You only need **one tab open** in this window.
- This is the inbox where you’ll receive the **Tableau Software Account Activation** email.

> 💡 Keep this window open — you’ll switch to it briefly during the activation step.

<br>

### 4. Fill Out the Trial Signup Form

On the [Tableau Trial Page](https://www.tableau.com/products/trial), complete the form with the following details:

- **First Name**
- **Last Name**
- **Company Name** – Your organization or a placeholder.
- **Email** – Use your preferred email address, but **append `+TC25` just before the `@` symbol**:
  - Example:
    - `john.doe+TC25@salesforce.com`
    - `tsmith+TC25@gmail.com`
- **Phone Number** – Enter your preferred phone number.
- **Job Role / Department / Country** – Select as appropriate.

✅ Check the box to agree to the terms, then click **Start Free Trial**.

<br>

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img2.png)

</details>

<br>

### 5. Activate Your Tableau Account (Important!)

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

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img4.png)

</details>

<br>

### 6. Set Your Password & Finish Setup

1. Once you open the activation link in the incognito window, Tableau will recognize your email and display your username.
2. You’ll be prompted to **set a password**.

   - It must meet Tableau’s password criteria.
   - For this exercise, we are using:  
     **`DataRockstar1!`**

   > You may choose your own secure password if you'd like — this is just for simplicity during the lab.

3. Click **Submit**. Tableau will begin provisioning your site.

<br>

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img5.png)

</details>

<br>

### 7. Wait for Trial Activation

- You’ll see a message that says:  
  **“Activating your trial site...”**
- This process takes **1–2 minutes**.
- When finished, you’ll be automatically redirected to your new **Tableau Cloud site homepage**.

<br>

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img7.png)

</details>

<br>

✅ **Done!** You’ve successfully created your Tableau Cloud trial site. We’ll use this site throughout the rest of the lab, be sure to keep this tab open!

<br>

---

## Step 2: Upload "Sales Cloud Data" as a Published Data Source

Next, we’ll upload the **Sales Cloud Data** file into Tableau Cloud to use in our exercises. This process creates a **Published Data Source** directly from the browser — no Tableau Desktop required.

### 1. Download the CSV File

In **Tab 1** of your incognito window (where the GitHub repo is open), locate and download:  
**`Sales Cloud Data.csv`**

> 💾 Save this file somewhere easy to find, like your **Downloads** folder.

<br>

### 2. Start the Upload Process

Go back to your Tableau Cloud **Home** page.  
Click the **“New”** drop-down menu at the top.  
Select **“Published Data Source”** from the list.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img8.png)

</details>

<br>

### 3. Connect to the CSV File

In the **Connect to Data** window that opens:  
Toggle to the **"Files"** tab at the top.  
Click to **browse for a file** and select the `Sales Cloud Data.csv` file you downloaded.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img9.png)

</details>

<br>

### 4. Publish the Data Source

Once the data loads, click **“Publish As...”** in the top-right corner.  
In the popup window:
- Name the data source: **`Sales Cloud Data`**
- Keep the default project folder selected.

Click **Publish**.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img11.png)

</details>

<br>

### 5. Finish & Return to Home

If you see a success message, acknowledge or close any pop-ups.  

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img12.png)

</details>

<br>

In the upper left corner, click **“File”** → **“Close”** to return to your Tableau Cloud **Home** page.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img13.png)

</details>

<br>

✅ **Success!** You’ve now uploaded and published your first data source to Tableau Cloud. You’ll use this dataset in the next steps of the lab.

<br>

---

## Step 3: Create Pulse Metrics

In this step, you’ll create three dynamic Pulse Metrics using the "Sales Cloud Data" source you uploaded earlier.

---

### Open Pipeline Metric

#### 1. Create New Metric

1. From the left-hand navigation, click **Pulse**.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img14.png)

</details>

<br>

2. Click **New Metric Definition**.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img15.png)

</details>

<br>

3. Search for and connect to your **Sales Cloud Data** published data source.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img16.png)

</details>

<br>

4. Label the metric: **Open Pipeline**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img17.png)

</details>


<br>

#### 2. Metric Setup
- **Measure**: `Amount`
  - Keep Aggregation as default: `Sum`, `Running Total`
- **Time Dimension**: `Close Date`

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img18.png)

</details>

<br>

#### 3. Add Definition Filters
- Filter on `Stage`
  - **Exclude**: `Closed Lost`, `Closed Won`

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img21.png)

</details>

<br>

#### 4. Adjustable Metric Filters
- Account Name  
- Account Type  
- Opportunity Owner  
- Stage  
- Forecast Category  

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img22.png)

</details>

<br>

#### 5. Formatting
- **Number Format**: Currency (`USD`)

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img23.png)

</details>

<br>

#### 6. Time Settings
Click **Next > Time**
- **Date Offset**: `180 days`  
- **Minimum Time Granularity**: `Week`  
- **Time Comparison**: Keep defaults (`Prior Year`, `Prior Period`)

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img24.png)

</details>

<br>

#### 7. Goal Settings
Click **Next > Goals**
- Skip for now — we’ll set a manual goal later.

<br>

#### 8. Add Insights
Click **Next > Insights**
- **Value Going Up**: `Favorable`
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img25.png)

</details>

<br>

- **Record Identifier**: `Account ID`  
- **Record Identifier Name**: `Account Name`  
- **Singular**: `Account`, **Plural**: `Accounts`

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img26.png)

</details>

<br>

Leave other insights settings unchanged.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img27.png)

</details>

<br>

#### 9. Final Steps
- **Add Yourself** as a follower of the metric.
- After the metric is created, click the **ellipses (…)** on the metric tile and select **Set Goal**.
  - Type in: `600,000,000`
  - Click **Save**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img28.png)

</details>

<br>

- Explore your new **Open Pipeline** metric!
<br> 
- Navigate back to the **Pulse Digest**
  - In the top left drop down, click into **Tableau Pulse** and select **Followed metrics**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img29.png)

</details>

<br>

### ⏱️ Average Days to Close Metric

#### 1. Create New Metric
1. Click **New Metric Definition**.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img31.png)

</details>
<br>

2. Connect to the same **Sales Cloud Data** source.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img32.png)

</details>
<br>

3. Label the metric: **Avg Days to Close**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img33.png)

</details>

<br>


#### 2. Metric Setup
- **Measure**: `Days to Close`
  - Change Aggregation to: `Average`
- **Time Dimension**: `Close Date`

<br>

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img34.png)

</details>
<br>

#### Definition Filters
- Filter on `Stage`
  - **Include only**: `Closed Won`
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img37.png)

</details>
<br>


#### 3. Adjustable Metric Filters
- Account Name  
- Forecast Category  
- Opportunity Owner  
- Account Type  
- Lead Source  

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img38.png)

</details>

<br>

#### 4. Formatting
- **Number Format**: `Number`  
- **Singular**: `Day`  
- **Plural**: `Days`

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img39.png)

</details>

<br>

#### 5. Time Settings
Click **Next > Time**
- **Date Offset**: `180 days`  
- **Minimum Time Granularity**: `Week`  
- **Time Comparison**: Keep defaults

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img40.png)

</details>

<br>

#### 6. Goal Settings
Click **Next > Goals**  
- Skip

<br>

#### 7. Insights
Click **Next > Insights**
- **Value Going Up**: `Unfavorable`
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img43.png)

</details>
<br>

- **Turn off** Record Level Insights

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img44.png)

</details>
<br>

#### 8. Save & Follow Metric
- Click **Save**, then **Follow the Metric**.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img45.png)

</details>
<br>
  
- Return to the **Pulse Home Page**.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img46.png)

</details>

<br>

### 🏆 Win Rate Metric

#### 1. Create a New Metric
1. From the Pulse Home Page, click **New Metric**.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img48.png)

</details>

<br>

2. Connect to the **Sales Cloud Data** data source.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img49.png)

</details>

<br>

3. Title the metric: **Win Rate**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img50.png)

</details>

<br>

#### 2. Advanced Definition Setup

1. Click **Advanced Definition**.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img51.png)

</details>

<br>

2. In the Advanced Analytics Editor, create a new calculated field:
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img52.png)

</details>

Input the following:
   - **Name**: `Win Rate`
   - **Formula**:  
     ```
     SUM([Opportunities Won]) / COUNTD([Opportunity ID])
     ```
   - Click **OK**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img53.png)

</details>

<br>

4. Drag the `Win Rate` calculated field to the **Measure** box.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img54.png)

</details>

<br>

5. Drag `Close Date` to the **Time Dimension** box.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img55.png)

</details>

<br>

Update the field accordingly:
   - Click into the drop-down of the **YEAR(Close Date)** field → Select `Month` → Click **Apply**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img56.png)

</details>
  
<br>

#### 3. Adjustable Metric Filters
- Opportunity Owner  
- Industry  
- Lead Source  

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img57.png)

</details>

<br>

#### 4. Formatting
- **Number Format**: `Percentage`

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img58.png)

</details>

Click **Next**

<br>

#### 5. Time Settings
- **Date Offset**: `180 days`  
- **Minimum Time Granularity**: `Week`

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img59.png)

</details>

Click **Next**

<br>

#### 6. Insights
- **Value Going Up**: `Favorable`
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img60.png)

</details>

- **Turn Off** Record Level Outliers

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img61.png)

</details>

Click **Save**, then **Follow the Metric**.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img62.png)

</details>

<br>

✅ After completing this step, you’ll have three active Pulse Metrics on your Pulse Digest:
- **Open Pipeline**
- **Avg Days to Close**
- **Win Rate**

You’re now ready to move on to building visualizations!

---

## Step 4: Create Advanced Visualizations

### 🔹 Visualization 1: Open Pipeline by Sales Rep

#### 1. Create a new workbook
- From Tableau Pulse, click into the top left drop-down menu and select **Tableau Cloud** to return to the Tableau Cloud Home Page
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img63.png)

</details>
<br>

- From the home page, click into the **New** drop-down from the welcome banner and select **workbook**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img64.png)

</details>

<br>

- Connect to the **Sales Cloud Data** data source we uploaded previously
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img65.png)

</details>

Let’s build a visualization to show open pipeline by sales rep.

<br>

#### 2. Set up your basic bar chart:
- In the **Data pane** on the left, drag **`Amount`** onto the **Columns** shelf.
- Drag **`Opportunity Owner`** onto the **Rows** shelf.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img66.png)

</details>

You should now see a horizontal bar chart showing the total opportunity amount each sales rep has ever owned.

<br>

#### 3. Add filters to narrow the data:
- Drag **`Stage`** onto the **Filters** shelf:
  - In the filter pop-up, check **`Closed Lost`** and **`Closed Won`**
  - Click **“Exclude selected values”**
  - Hit the blue **OK** button
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img67.png)

</details>

<br>

  - To apply this filter to all future visualizations:
    - Click the dropdown on the Stage filter pill > **Apply to Worksheets** > **All Using This Data Source**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img68.png)

</details>

<br>

- Drag **`Close Date`** onto the Filters shelf:
  - In the pop-up, choose **Relative Date** > click **Next**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img69.png)

</details>

  - Change the dropdown from “Days” to **Years**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img70.png)

</details>

  - Keep the default **“This year”** selection
  - Click **OK**
  - Apply this filter to all future visualizations:
    - Click the dropdown on the Close Date filter pill > **Apply to Worksheets** > **All Using This Data Source**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img71.png)

</details>

<br>

#### 4. Change the visualization type:
- Click the **Show Me** tab in the top right
- Select the **Treemap** chart type

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img72.png)

</details>

<br>

#### 5. Add context with a label:
- Find **`Opportunity ID`** in the Data pane
- On **Mac**: hold **Option** and drag `Opportunity ID` to the **Label** section on the **Marks card**
- On **Windows**: hold **Ctrl** and drag `Opportunity ID` to **Label**
- In the dialog that appears, choose **CNTD(Opportunity ID)** and click **OK**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img73.png)

</details>

This will now show the **amount** represented by **size**, and the **number of opportunities** per rep as a label.

<br>

#### 6. Rename your worksheet:
- Double-click the sheet tab and rename it:  
  **`Amount by Rep`**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img75.png)

</details>
  
<br>
---

### 🔹 Visualization 2: Top 10 Accounts by Stage

Next, we’ll create a more detailed view of opportunity amount by account name.

#### 1. Build the base chart:
- Drag **`Amount`** to the **Columns** shelf
- Drag **`Account Name`** to the **Rows** shelf
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img76.png)

</details>

- Click the **Sort** icon in the toolbar to sort account names by value

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img77.png)

</details>

<br>

#### 2. Filter to the top 10 accounts:
- Drag **`Account Name`** to the **Filters** shelf
- In the filter dialog, navitate to the **Top/Bottom** drop-down section
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img78.png)

</details>

<br>

  - Choose **By Field**
  - Set:
    - **Top**: leave as-is
    - **Count**: `10`
    - **Field**: `Amount`
    - **Aggregation**: `Sum`
  - Click **OK**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img79.png)

</details>

<br>

#### 3. Add color by stage:
- Drag **`Stage`** to the **Color** section of the **Marks** card

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img80.png)

</details>

<br>

#### 4. Make it color-blind friendly:
- Click on the **Color** legend in the Marks card
- In the **Edit Colors** window:
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img81.png)

</details>

  - Change the palette to **Color Blind**
  - Click **Assign Palette**
  - Then click **OK**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img82.png)

</details>

<br>

#### 5. Rename your worksheet:
- Double-click the sheet tab and rename it:  
  **`Accounts by Stage`**

<br>

### 📌 Visualization 3: Opportunity-Level Pipeline Detail (Viz in Tooltip)

This third and final visualization will give us the **granularity needed to complement the aggregate-level views**, enabling detailed inspection of individual opportunities within each account.

---

### 🔧 Create the "Opp by Amount" Worksheet

1. **Create a new worksheet** by clicking the **new sheet tab** at the bottom.

2. In the **Data pane**:
   - Drag **`Amount`** to the **Columns** shelf.
   - Drag **`Opportunity Name`** to the **Rows** shelf.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img83.png)

</details>

<br>

3. **Adjust the axis to show full opportunity names**:
   - Hover over the **Y-axis** (vertical axis on the left).
   - When your cursor turns into a **black arrow**, click and drag the axis to **expand the space** and make labels readable.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img84.png)

</details>

4. Rename the worksheet tab to:  
   **`Opp by Amount`**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img85.png)

</details>

---

### 🛠️ Add This Viz as a Tooltip (Viz in Tooltip)

Now we’ll embed this new worksheet as a dynamic **Viz in Tooltip** inside the **Accounts by Stage** view, allowing users to hover and inspect specific opportunities within a stacked bar.

1. Click into the **`Accounts by Stage`** worksheet tab (the second viz we built) to open it.

2. In the **Marks card**, click on **Tooltip**.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img86.png)

</details>

3. In the **Tooltip editor**:
   - Click **Enter** a few times to create some space beneath the existing text.

4. In the **top toolbar**, click the **Insert** dropdown:
   - Hover over **Sheet** > select **`Opp by Amount`**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img87.png)

</details>

<br>

   You’ll see a placeholder like:
``` <Sheet name="Opp by Amount" maxwidth="300" maxheight="300"> ```

5. Edit the inserted sheet tag:
  - Change maxwidth="300" to maxwidth="600"
  - Change maxheight="300" to maxheight="600"

  Final version:
``` <Sheet name="Opp by Amount" maxwidth="600" maxheight="600"> ```

<br>

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img88.png)

</details>

<br>

  - Click **OK** to save the updated tooltip.

✅ Now when you hover over any stacked bar in the Accounts by Stage chart, you'll see the exact opportunity names (and amounts) that fall within that account + stage combination!

This tooltip drill-down gives us both the aggregated picture and a direct line of sight into individual deals — perfect for quick pipeline inspection.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img89.png)

</details>

<br>

# Step 5: Pull Your Metrics & Visualizations into a Dashboard

Now that we've created visualizations and Pulse metrics, it's time to combine them into a single, interactive dashboard.

### 🔧 Create the Dashboard

1. **Open a new dashboard**:
   - Click the **Dashboard icon** at the bottom of the screen (next to your worksheet tabs).

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img90.png)

</details>

<br>

2. **Rename the dashboard**:
   - Double-click where it says **"Dashboard 1"**
   - Rename it: **`Sales Overview`**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img91.png)

</details>

<br>

3. **Adjust dashboard sizing**:
   - In the **Dashboard pane** on the left, change the **Size** dropdown to `Automatic`.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img92.png)

</details>

<br>

### 🧱 Build the Layout with Containers

1. In the **Objects** section of the **Dashboard pane**, drag out **two Horizontal containers**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img93.png)

</details>

<br>

  - Place the **first container** to take up the full width of the dashboard (upper half).
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img94.png)

</details>
<br> 
  - Drop the **second container** just below it (lower half of the dashboard).
  <details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img95.png)

</details>
<br>

### 📊 Add Pulse Metrics to the Top Container

1. In the **Objects** pane, find **Pulse Metric**.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img96.png)

</details>

<br>

3. Drag in each of your three metrics to the **top container**:
   - Pull the Pulse Metric object into the top container
     - Click the **Open Pipeline** metric
     - Select the **"Quarter to Date"** card
     - Keep all defaults, click **Add to Dashboard**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img98.png)

</details>

<br>

  - Pull the Pulse Metric object into the top container
    - Click the **Avg Days to Close** metric
    - Select **Quarter to Date** > Add to Dashboard

<br> 

  - Pull the Pulse Metric object into the top container
    - Click the **Win Rate** metric
     - Select **Quarter to Date** > Add to Dashboard

<br>

4. Once all three are added, double-click the **gray hamburger menu** at the top of the container.

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img99.png)

</details>

<br>

A **blue menu** should appear atop the container. 

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img100.png)

</details>

<br> 

Click into the container format drop down, and select select **Distribute Contents Evenly**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img101.png)

</details>

<br>

### 📈 Add Visualizations to the Bottom Container

1. In the **Sheets** pane, drag **`Amount by Rep`** into the **bottom horizontal container** (left side).
   - A legend may appear on the right—don’t worry, we’ll remove it later.

<br>

2. Drag **`Accounts by Stage`** into the **right side** of the same container.
<br>

3. Remove the legends:
   - Click the vertical section containing the legends
   - Click the blue **X** in the upper-left of that container to delete it

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img102.png)

</details>

<br>

### 🎨 Format the Dashboard

1. **Show the dashboard title**:
   - In the top menu, go to **Dashboard** > **Show Title**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img104.png)

</details>
<br>

2. **Distribute contents evenly**:
   - Click into either viz, then double-click the **gray hamburger menu**
   - In the **blue dropdown**, select **Distribute Contents Evenly**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img103.png)

</details>

<br>

3. **Fit both visualizations to screen**:
   - Click into **Amount by Rep**, use the dropdown to set **Fit** to **Entire View**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img105.png)

</details>

   - Repeat for **Accounts by Stage**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img106.png)

</details>

<br>

### 🔄 Add Filter Action (Interactivity)

1. In **Amount by Rep**, click the **filter icon** on the viz toolbar to enable interactivity.
   - Try clicking on **John Demby** in the treemap — you’ll see the other viz filter by rep.
  
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img107.png)

</details>

<br>
2. Uh oh! Only a few accounts appear — not the top 10. Why?
   - By default, Tableau is showing the top 10 **overall**, not per rep.
   - To fix this, we’ll **add the filter to context**.

<br>

### ❓ What’s a Context Filter?

A **context filter** tells Tableau to apply one filter *before* calculating another. This ensures that our **"Top 10 Accounts"** is calculated **per sales rep**, not globally.

<br>

### 🛠️ Fix the Filter with Context

1. In the dashboard, click into the **Accounts by Stage** worksheet (via the **Go-to sheet** icon beneath the "X" in the format menu).
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img108.png)

</details>

<br>

2. In the **Filters** shelf, find **`Action (Opportunity Owner)`**

3. Click its dropdown > select **Add to Context**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img109.png)

</details>

<br>

### ✅ Publish the Dashboard

1. From the **Accounts by Stage** worksheet, click the light blue **Publish As…** button in the top-right.
2. Name your workbook: **`Sales Overview`**

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img110.png)

</details>

<br>
---

## Step 6: Publish & Interact

Now that it's published, let's try it out!

1. In the green banner at the top of the screen, click **Go to Workbook**
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img111.png)

</details>

2. Click the dashboard tile open the **Sales Overview** dashboard.
<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img112.png)

</details>

3. Let's interact and drill down!
   - Click **“John Demby”** within the treemap.
   - Watch the bottom chart update to show **John’s top 10 accounts**.
   - Hover over the stacked bars — you’ll see insights like:
     - “John has over $4.5M with Displaytech in the Qualification stage.”
     - Thanks to the viz and tooltip, we can also see individual opp names and amounts!

<details>
  <summary> ⚠️ <strong> HINT </strong> - Expand to view example sceenshot </summary>

  ![Alt text](Images/Img113.png)

</details>

<br>

### ⏸️ PAUSE: Tableau Agent Demo

We’re pausing here for a live walkthrough of Tableau Agent.

If you're following along later or exploring on your own:

- Continue to the next section of this lab manual -- we've provided a few **starter prompts** using this same dataset to show you how much easier it is to create similiar visualizations to what we created manually today.
- You’re also welcome to use your **own prompts** or **upload new data**.
- This trial site is **completely secure** and **only accessible to you** (or others you explicitly invite).

<br>

---

## Step 7: OPTIONAL / SELF-PACED: Enable Your Tableau Cloud Site with Advanced AI

### 1. Open Site Settings

1. From the **Home** page of your Tableau Cloud site, scroll to the very bottom of the left-hand navigation.
2. Click **Settings**.

<br>

### 2. Enable AI Features (General Tab)

1. The **Settings** page will default to the **General** tab.
2. Under the section titled **“Turn on AI in Tableau by feature area”**, **check every checkbox** that appears — these enable:
   - Tableau Pulse summaries
   - Semantic question matching
   - Pulse Discover
   - Conversational Web Authoring
   - Tableau Prep suggestions

4. Click the **blue "Save"** button in the upper right corner of the screen to apply these settings.

<br>

--

## Step 8 - OPTIONAL / SELF-PACED: Create Visualizations with Tableau Agent

### 1. Navigate to the Home Page

- Click the **Tableau** logo or select **Home** from the left-hand navigation to return to the Home page.

---

### 2. Access the Sales Cloud Data Source

- Click the **Explore** tab in the left-hand sidebar.
- Navigate to the **Default** project.
- Locate the **Sales Cloud Data** published data source.
- Click the **New** dropdown and select **Workbook Using This Data Source**.

---

### 3. Engage with Tableau Agent

- Click the **Agentforce** logo in the top-left to launch Tableau Agent.
- Click the blue **"Got it"** button to enter the conversational experience.

---

### 4. Create the "Top Reps" Visualization

1. In Tableau Agent, type:  
   **`amount by owner`**  
   → A horizontal bar chart will appear showing total amount by opportunity owner.

2. Click **Show Me** in the top-right and select the **Treemap** chart type.

3. Add a label for distinct opportunities:
   - Locate **Opportunity ID** in the Data pane.
   - Right-click (or Command-click on Mac) and **drag** it onto the **Marks card > Label**.
   - In the dialog, choose **CNTD(Opportunity ID)**.

4. Rename the worksheet:
   - Click the sheet tab at the bottom.
   - Rename it to **Top Reps**.

---

### 5. Create the "Top Open Opps" Visualization

1. Open a **new worksheet**.

2. Open Tableau Agent and type:  
   **`Show opportunity name by amount`**

3. Filter the data:
   - Type: **`Exclude closed won and closed lost opportunities`**
   - Then: **`Filter to top 10 accounts by amount`**
   - Then: **`Add stage to color`**

---

<br>

✅ You now have two visualizations, all thanks to Tableau Agent!
- **Top Reps** – Treemap with opportunity count
- **Top Open Opps** – Filtered bar chart showing key accounts






