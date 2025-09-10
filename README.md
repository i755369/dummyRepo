# Fieldglass Buyer Company Creation (Exercise)

### INTERNAL

## TABLE OF CONTENTS

- [Fieldglass Buyer Company Creation (Exercise)](#fieldglass-buyer-company-creation-exercise)
    - [INTERNAL](#internal)
  - [TABLE OF CONTENTS](#table-of-contents)
  - [EXERCISE MATERIALS](#exercise-materials)
    - [Contingent Exercise](#contingent-exercise)
    - [Company Configuration Workbook](#company-configuration-workbook)
    - [Contingent User Role Permissions Matrix](#contingent-user-role-permissions-matrix)
    - [Supplier Configuration Workbook](#supplier-configuration-workbook)
    - [Contingent Hiring Manager Demo Rubric](#contingent-hiring-manager-demo-rubric)
  - [CREATE A COMPANY](#create-a-company)
    - [Create Company Details](#create-company-details)
  - [ESTABLISH COMPANY CONFIGURATION](#establish-company-configuration)
    - [Specify Configuration Settings](#specify-configuration-settings)
    - [Coordinator/Distributor](#coordinatordistributor)
  - [BASIC COMPANY SETUP](#basic-company-setup)
    - [Log In](#log-in)
    - [Create a Default Escalation Threshold](#create-a-default-escalation-threshold)
    - [Enable Currencies](#enable-currencies)
    - [Create Business Units](#create-business-units)
    - [Create Cost Centers](#create-cost-centers)
    - [Create Sites](#create-sites)
    - [Create a Location](#create-a-location)
    - [Create User Roles](#create-user-roles)
    - [Create Users](#create-users)
    - [Create a General Ledger Account](#create-a-general-ledger-account)
    - [Create a Task Code](#create-a-task-code)
    - [Create Expense Codes](#create-expense-codes)
    - [Create an Activity Item and Activity Checklist](#create-an-activity-item-and-activity-checklist)
    - [Create Rates and Rate Classifications](#create-rates-and-rate-classifications)
    - [Create Invoice Adjustments](#create-invoice-adjustments)
    - [Create Approval Groups](#create-approval-groups)
    - [Create Reason Codes](#create-reason-codes)
    - [Create Supplier Invitations](#create-supplier-invitations)
    - [Configure MSP Fee](#configure-msp-fee)
    - [Configure Supplier Companies](#configure-supplier-companies)
    - [Complete Supplier Setup](#complete-supplier-setup)
    - [Create Distribution Lists](#create-distribution-lists)
    - [Create Contingent Type](#create-contingent-type)
    - [Create Worker Pay Types](#create-worker-pay-types)
    - [Create a Job Posting Template](#create-a-job-posting-template)
    - [Enable Work Item Messaging](#enable-work-item-messaging)

## EXERCISE MATERIALS

### Contingent Exercise

- **Create a Company Initial**

  This document will guide you through the initial creation of your test company, including step-by-step instructions for creating the essential Admin menu items. This is the first document you should reference, and will be used throughout the entirety of the initial exercise.

### Company Configuration Workbook

This spreadsheet provides the company-level configuration for the setup of your test company. This configuration reflects the Recommended Solution, and should be followed closely.

After following the steps in the exercise workbook to create the Buyer company shell, you should immediately reference this spreadsheet to complete the company configuration, prior to navigating away from the page.

### Contingent User Role Permissions Matrix

These spreadsheets provide the user role permissions for the two user roles created in the initial exercise: Hiring Manager and Program Office.

### Supplier Configuration Workbook

This spreadsheet provides the company-level configuration for the setup of your Supplier companies. While Supplier companies are created with a default configuration, we recommend enabling several other options as well.

### Contingent Hiring Manager Demo Rubric

This rubric provides the guidelines for the Hiring Manager Demo to be completed for your manager and buddy as an assessment of this exercise.

---

## CREATE A COMPANY

### Create Company Details

1. Login to the Fieldglass SA (Super Admin) Account
2. In the Client Tools section at the top of the launch page, click **Create Buyer Company**.
3. Enter the following information about your company:

| Section/Field              | Description/Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Company Details**        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Company Code               | Enter a two- to four-digit alpha-numeric code to identify your company. The company code must be unique and not used by any other company (Buyer or Supplier) in this pre-prod environment.                                                                                                                                                                                                                                                                                                                |
| Note                       | After you enter values for all the required fields on the page and click**Submit**, you will be notified if your company code is a duplicate. If the company code is a duplicate, you will be required to enter a new, unique company code before you can save your information. To determine if company codes have already been used, click the **View Buyer Company** or **View Supplier Company** link from the main launch page. (Click **Home** at the top of the page to return to the launch page.) |
| Company Name               | Enter a name for your company.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Company ID                 | This can be the same as the name.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Address 1                  | Enter an address.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| City                       | Enter a city.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| State/Province             | Enter a state if using a US address. This format must be the two-letter state abbreviation. For example, Illinois would be IL.                                                                                                                                                                                                                                                                                                                                                                             |
| Country                    | Select a country.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ZIP/Postal Code            | Enter a zip/postal code.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Test Company?**          | Do not change the default value of No. By default, report transforms are not done on test companies, so if you change the default value of No, you are limiting your ability to run reports for your company.                                                                                                                                                                                                                                                                                              |
| **Is Parent Company?**     | Do not change the default of No. Parent companies are used when Buyers have multiple companies that they would like to separate for transactional purposes but have reporting capability across all entities. Parent companies require additional setup. If you change the default to Yes, this will delay the creation of your test company as you will need to create a new, non-parent company. If a parent company is created, it cannot be changed.                                                   |
| **Contract Source**        | This should be set to**FG**.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Default Person Details** | The default person section is used to establish the first Buyer user administrator. For your test company, you should make yourself the administrator. After saving your company details, you will receive emails inviting you to register your administrator user account.                                                                                                                                                                                                                                |
| First Name                 | Enter your first name as the primary user for the company.                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Last Name                  | Enter your last name (surname) as the primary user for the company.                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Email                      | Enter your SAP work email address. You must enter your email address in order to receive the user registration email sent by the system. Do not enter a “dummy” email address.                                                                                                                                                                                                                                                                                                                             |
| User Name                  | Enter a username that you will use to sign into your test company. You username must be unique across all SAP Fieldglass users in this pre-prod environment. You may want to have your username be: first initial, last name, underscore, company code. For example:`jdoe_TCMX`                                                                                                                                                                                                                            |
| **Helpdesk User**          | This section is where the SAP Fieldglass Administrator user account is created. It allows SAP Fieldglass to have a user account in each company in order to log into a Buyer or Supplier company. This user account enables SAP Fieldglass to assist with troubleshooting and tracks any actions taken as “SAP Fieldglass” and not as a Buyer or Supplier user.                                                                                                                                            |
| First Name                 | Do not change the default name:**Fieldglass**                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Last Name                  | Do not change the default name:**Administrator**                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Username                   | Leave the default username. The username is automatically created after you enter a company code. All Helpdesk usernames for all companies should be:`companycode@fg_help` For example: `LSFG@fg_help`                                                                                                                                                                                                                                                                                                     |
| Password                   | Enter a password. Note: If your company code is not unique, you will be required to re-enter the password after changing your company code.                                                                                                                                                                                                                                                                                                                                                                |
| Email                      | Do not change the pre-populated email address in this field:`fieldglassadmindefault@sap.com`                                                                                                                                                                                                                                                                                                                                                                                                               |

5. When you have entered all the required information, click **Submit** at the top of the page.

**WARNING!** The Buyer company configuration must be defined prior to being able to create items in the Buyer company Admin menu. Do not register your Buyer administrator until the company configuration is complete.

You will receive two registration emails with instructions that tell you how to register your first Buyer administrator user. You should continue to follow the steps on the next page (“Configuring Your Company”) to establish your company, and register your user at a later time.

---

## ESTABLISH COMPANY CONFIGURATION

1. In the Client Tools section of the launch page, click **View Buyer Company**.
2. Enter your company code in the **Code** field and click **Filter** (or press **Enter**).
3. Click the link for your company **Name**.
4. Click **Edit Configuration**.

### Specify Configuration Settings

### Coordinator/Distributor

**Description**

When a company is created with the company configuration **Does Buyer Have MSP?** enabled, users can be set up to act as a Coordinator or Distributor through their user profiles. Coordinators and Distributors can be associated to business units, Coordinators can be included in approval workflows, and Distributors can be assigned to distribute job postings.

Generally, users in the Program Office or who are Administrators, will be set up as Coordinators or Distributors.

In the next section, you will create business units, and in order to assign a Coordinator or Distributor to the business unit, there must be at least one user who has been set up with that permission. Therefore, you will need to update the profile of your Buyer administrator user before creating new business units. A user cannot enable this flag for their own user account, so you will need to utilize the Fieldglass Administrator account to complete this action.

**Set Up**

1. Log in as the Fieldglass Administrator user using the **Username** box on the **SA** page. The default format of the username should be **<COMPANY_CODE>@fg_help**
2. Click **Sign In**.
3. Navigate to the Admin Menu (gear icon at the bottom left of the page)
4. From the Admin menu, select **User** in the **User** section.
5. Click the **Name** of your Buyer administrator; this should be your name. This is the user you created while generating the company details at the beginning of this exercise.
6. Select the checkbox next to the **This User can act as Coordinator/Distributor** setting.
7. Click **Edit**.
8. Click **Update**.

---

## BASIC COMPANY SETUP

After establishing your company configuration, you can begin your basic company setup. Company setup can be completed by any user with administrative rights.

### Log In

To access the Admin menu for your company, log in with your Buyer administrator username and password.

### Create a Default Escalation Threshold

Add a default set of escalation thresholds:

1. From the Admin menu, select **Thresholds – Escalation** in the **Workflow** section.
2. Click **New**.
3. Enter a title into the **Name** field; for example, **Default**.
4. If desired, set a **Threshold Time** in hours for one or more escalation thresholds.
5. Click **Add**.

---

### Enable Currencies

Add multiple currencies:

1. From the Admin menu, select **Currency** in the **Financial Data** section.
2. Click **Add**.
3. Select **GBP (United Kingdom Pound)**, **EUR (Euro)**, **USD (US Dollars)** and **AUD (Australian Dollar)**.
4. Click **Add**.

Additional currencies can be added at any time.

---

### Create Business Units

When you created your company, a default business unit was automatically created. This business unit has the same name as your company, and can be used as a parent business unit.

Add two child business units under the default parent business unit:

1. From the Admin menu, select **Business Unit** in the **Company Structure** section.
2. Click **New**.
3. Add information about **Business Unit 1**, as outlined in the table below.
4. Click **Add**.
5. Repeat steps 2-4 to add **Business Unit 2**.

You can add additional business units, if desired.

| Field                     | Business Unit 1                              | Business Unit 2                              |
| ------------------------- | -------------------------------------------- | -------------------------------------------- |
| Code                      | FA                                           | IT                                           |
| Name                      | Finance and Accounting                       | Information Technology                       |
| Parent Business Unit      | Default Business Unit (Company Code)         | Default Business Unit (Company Code)         |
| Escalation Preference     | Select the Escalation Preference you created | Select the Escalation Preference you created |
| Coordinator Required      | Yes                                          | Yes                                          |
| Distributor Required      | Yes                                          | Yes                                          |
| Remit-to Address Required | No                                           | No                                           |

---

### Create Cost Centers

Add two cost centers:

1. From the Admin menu, select **Cost Center** in the **Company Structure** section.
2. Click **New**.
3. Add information about **Cost Center 1**, as outlined in the table below.
4. Click **Add**.
5. Repeat steps 2-4 to create **Cost Center 2**.

**Note**: Use your Buyer administrator user as the owner for your new cost centers. After you add additional users, you can change the cost center owner. Any currency enabled for your Buyer company can be associated to a cost center.

If you wish, you can add additional cost centers.

| Field                                                                                                        | Cost Center 1                   | Cost Center 2                   |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------- | ------------------------------- |
| Code                                                                                                         | 200                             | 300                             |
| Name                                                                                                         | Operational Accounting          | Network Solutions               |
| Is it a Project Cost Center?                                                                                 | No                              | No                              |
| Currency (click the Add or remove Currencies button to access a list of currencies enabled for your company) | AUD, USD, GBP, EUR              | AUD, USD, GBP, EUR              |
| Owner                                                                                                        | Select your Buyer administrator | Select your Buyer administrator |
| Include all Task Codes                                                                                       | Yes                             | Yes                             |
| Include all Expense Codes                                                                                    | No                              | No                              |

---

### Create Sites

Add two sites:

1. From the Admin menu,select **Site** in the **Company Structure** section.
2. Click **New**.
3. Add information about **Site 1**, as outlined in the table below. All other required fields should remain as defaulted.
4. Click **Add**.
5. You may see a gold warning message after you add a new site. These warnings are informational and will not prevent you from continuing with your company setup. Click **Add** again to bypass the warning.
6. Repeat steps 2-4 to create **Site 2**.

If you wish, you can add additional sites.

| Field                                                                                                        | Site 1                                 | Site 2                                 |
| ------------------------------------------------------------------------------------------------------------ | -------------------------------------- | -------------------------------------- |
| Code                                                                                                         | Chicago IL                             | London UK                              |
| Name                                                                                                         | Chicago IL                             | London UK                              |
| Currency (click the Add or remove Currencies button to access a list of currencies enabled for your company) | USD                                    | GBP                                    |
| Selectable Site                                                                                              | Yes                                    | Yes                                    |
| Parent Site                                                                                                  | Select the Default Site (Company Code) | Select the Default Site (Company Code) |
| Corporate Calendar                                                                                           | Select the Default Corporate Calendar. | Select the Default Corporate Calendar. |
| State/Province                                                                                               | Illinois                               | N/A                                    |
| ZIP/Postal Code                                                                                              | 60606                                  | N/A                                    |
| Country                                                                                                      | United States (USA)                    | United Kingdom (GBR)                   |

**Note**: All sites which are configured with United States as the country require a State/Province and Zip/Postal Code to be entered. Non-US sites do not.

---

### Create a Location

Add a location:

1. From the Admin menu, select **Location** in the **Company Structure** section.
2. Click **New**.
3. Add information about the location, as outlined in the table below.
4. Click **Add**.

You can add additional locations, if desired.

| Field           | Location 1                |
| --------------- | ------------------------- |
| Code            | 111 North Canal Suite 600 |
| Name            | 111 North Canal Suite 600 |
| Site            | Chicago IL                |
| Address 1       | 111 North Canal           |
| Address 2       | Suite 600                 |
| City            | Chicago                   |
| State/Province  | IL                        |
| Zip/Postal Code | 60606                     |
| Country         | United States (USA)       |

---

### Create User Roles

**Set Up**

Add two user roles:

1. From the Admin menu, select **User Role** in the **User** section.
2. Click **New**.
3. Add the user role information for the **Hiring Manager** role, as outlined in the **Create a Company Contingent User Role Permissions Matrix** spreadsheet.
4. Click **Add**.
5. Repeat steps 2-4 to create the **Program Office** user role.

**Hint**: After creating the Hiring Manager user role, you can copy that role and make the necessary changes for the **Program Office** user role.

---

### Create Users

**Set Up:**

Add two users:

1. From the Admin menu, select **User** in the **User** section.
2. Click **New**.
3. Add information about User 1, as outlined in the table below.
4. Click **Add**.
5. Repeat steps 2-4 to create User 2.

**Note:** For your test company, create your own user details. Each user must have a unique username. To receive the registration emails for these users, be sure to enter your own email address.

| Field                                            | User 1                                                                                                                                                                          | User 2                                                                                                                                                                          |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| First Name                                       | Enter a first name.                                                                                                                                                             | Enter a first name.                                                                                                                                                             |
| Last Name                                        | Enter a last name.                                                                                                                                                              | Enter a last name.                                                                                                                                                              |
| Username                                         | Enter a unique username. (You may want to use your company code in the username to ensure it is unique: for example,`jdoe_LSFG`)                                                | Enter a unique username. (You may want to use your company code in the username to ensure it is unique: for example,`jsmith_LSFG`)                                              |
| Display Name                                     | Enter the user’s name as it should be displayed in the application. For example: Last, First.                                                                                   | Enter the user’s name as it should be displayed in the application. For example: Last, First.                                                                                   |
| Email                                            | Enter your email address.                                                                                                                                                       | Enter your email address.                                                                                                                                                       |
| Role                                             | Hiring Manager                                                                                                                                                                  | Program Office                                                                                                                                                                  |
| Primary Business Unit                            | Select one of your business units.                                                                                                                                              | Select one of your business units.                                                                                                                                              |
| Default Cost Center                              | Select one of your cost centers, if desired. Note: You may need to select the**Unused** radio button above the field before your cost center will display in the drop-down box. | Select one of your cost centers, if desired. Note: You may need to select the**Unused** radio button above the field before your cost center will display in the drop-down box. |
| Default Site                                     | Select one of your sites, if desired.                                                                                                                                           | Select one of your sites, if desired.                                                                                                                                           |
| Primary Supervisor                               | Select your Buyer administrator.                                                                                                                                                | Select your Buyer administrator.                                                                                                                                                |
| Signature Authority                              | 65,000.00 (AUD), 30,000.00 (GBP), 40,000.00 (EUR), 50,000.00 (USD)                                                                                                              | 80,000.00 (AUD), 45,000.00 (GBP), 50,000.00 (EUR), 60,000.00 (USD)                                                                                                              |
| User Access: Cost Centers, Business Units, Sites | All                                                                                                                                                                             | All                                                                                                                                                                             |

**User-Specific Additional Settings:**

| Field                                                     | User 1                 | User 2                 |
| --------------------------------------------------------- | ---------------------- | ---------------------- |
| This User can act as Coordinator/Distributor              | No                     | Yes                    |
| User will receive Ask an Expert (Contingent) questions    | No                     | Yes                    |
| User will receive Ask an Expert (Services) questions      | No                     | Yes                    |
| Program office will assist with Job Posting creation      | Yes                    | Yes                    |
| Scheduler will assist with Interview and Meeting creation | No                     | Yes                    |
| Use Flexible Sourcing                                     | No                     | No                     |
| PMO Dashboard                                             | No                     | Yes                    |
| Visualizer                                                | No                     | Yes                    |
| Manage Site Configurations                                | No                     | Yes                    |
| View and Report on Sensitive Data                         | No                     | Yes                    |
| View Restricted Attachments                               | No                     | Yes                    |
| View History Tab                                          | No                     | Yes                    |
| Set Run As User                                           | No                     | Yes                    |
| View Release Feature Administration                       | No                     | Yes                    |
| Employee ID                                               | Enter any employee ID. | Enter any employee ID. |

| Field                  | User 1                                                                                                                                                     | User 2                                                                                                                                                     |
| :--------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Preferences: Messaging | Select which types of messages you would like the user to receive via email. Messages not received via email will be in the SAP Fieldglass message center. | Select which types of messages you would like the user to receive via email. Messages not received via email will be in the SAP Fieldglass message center. |
| Email Format           | HTML Based                                                                                                                                                 | HTML Based                                                                                                                                                 |

### Create a General Ledger Account

Add one default general ledger account:

1. From the Admin menu, select **General Ledger Account** in the **Financial Data** section.
2. Click **New**.
3. Add information about the general ledger account, as outlined in the table below.
4. Click **Add**.

| Field | Value              |
| ----- | ------------------ |
| Code  | Default GL Account |
| Name  | Default GL Account |

---

### Create a Task Code

Add a Task Code:

1. From the Admin menu, select **Task Code** in the **Financial Data** section.
2. Click **New**.
3. Add the task code information, as outlined in the table below.
4. Click **Add**.

| Field                       | Value              |
| --------------------------- | ------------------ |
| Code                        | Hours Worked       |
| Name                        | Hours Worked       |
| Billable                    | Yes                |
| Capitalized                 | No                 |
| General Ledger Account Name | Default GL Account |

---

### Create Expense Codes

Add an expense code:

- A Buyer may create expense codes for categories like “Meals”, “Hotel”, or “Airfare”.

1. From the Admin menu, select **Expense Code** in the **Financial Data** section.
2. Click **New**.
3. Add the expense code information, as outlined in the table below.
4. Click **Add**.
5. Repeat steps 2-4 for the remaining expense codes.

| Value                       | 1                  | 2                  | 3                  |
| --------------------------- | ------------------ | ------------------ | ------------------ |
| Code                        | Travel - Meals     | Travel - Fares     | Travel - Lodging   |
| Name                        | Travel - Meals     | Travel - Fares     | Travel - Lodging   |
| Billable                    | Yes                | Yes                | Yes                |
| Capitalized                 | No                 | No                 | No                 |
| General Ledger Account Name | Default GL Account | Default GL Account | Default GL Account |

---

### Create an Activity Item and Activity Checklist

Add an activity item:

1. From the Admin menu, select **Activity Item** in the **Workflow** section.
2. Click **New**.
3. Select **Manage Worker**, then click **Complete Offboarding Task**.
4. Add the activity item information, as outlined in the table below.
5. Click **Add**.

| Field                                | Value                 |
| ------------------------------------ | --------------------- |
| Code                                 | Return Badge          |
| Action                               | Return Badge          |
| Actor                                | (Worker’s Supervisor) |
| Usage                                | Mandatory             |
| Completion Based On Prerequisite     | No                    |
| Frequency                            | Once                  |
| When will this Activity Item be due? | On Worker End Date    |
| Send Work Items                      | 5 working days        |
| Escalate                             | 2 working days        |

You will also need to create an activity checklist and associate the activity item:

6. From the Admin menu, select **Activity Checklist** in the **Workflow** section.
7. Click **New**.
8. Add the activity checklist information, as outlined in the table below.
9. Click **Add**.

| Field        | Value                   |
| ------------ | ----------------------- |
| Code         | All Sites - Offboarding |
| Name         | All Sites - Offboarding |
| Associate To | Company                 |

1. In the left-hand menu, select **Items (0)**.
2. Click **Add**.
3. Select the **Return Badge** activity item and click **Add**.

### Create Rates and Rate Classifications

One or more rate classifications must be created before creating any type of rate.

Add a rate classification:

1. From the Admin menu, select **Rate Classification** in the **Rate Structure** section.
2. Click **New**.
3. Enter the details for **Rate Classification 1**, as outlined in the table below.
4. Click **Add**.
5. Repeat steps 2-4 for the other rate classification.

**Note:** Because rate classifications are not applicable to standard rates, but the field is required, it is suggested that you create a rate classification with a name and code that is the same as your rate type. For example, create a rate classification called “Factor” to be used with all factor type rates or create a rate classification called “Markup” to be assigned to all markup type rates. This exercise has instructions to create a rate type of rate, so the suggestion is to name a classification “Rate” as well.

| Field | Rate Classification 1 | Rate Classification 2 |
| ----- | --------------------- | --------------------- |
| Code  | Rate Factor           | Rate Factor           |
| Name  | Rate Factor           | Rate Factor           |

Add a rate:

1. From the Admin menu, select **Rate** in the **Rate Structure** section.
2. Click **New**.
3. Enter the details for **Rate 1**, as outlined in the table below.
4. Click **Add**.
5. Repeat steps 2-4 for the other rate.

You can add additional rates for the remaining currencies enabled in your test company using the same approach detailed in the table below, if desired.

| Field                                                                             | Rate 1                             | Rate 2                             |
| --------------------------------------------------------------------------------- | ---------------------------------- | ---------------------------------- |
| Code                                                                              | ST                                 | Hr                                 |
| Name                                                                              | ST                                 | Hr                                 |
| Type                                                                              | Rate                               | Factor                             |
| Rate Classification                                                               | Rate Factor                        | Rate Factor                        |
| Automatically recalculate the factor rate when base rate is changed on WO and WOR | NA                                 | Yes                                |
| Currency                                                                          | USD                                | USD                                |
| Rate Category                                                                     | ST                                 | OT                                 |
| Unit of Measure                                                                   | Hour                               | Hour                               |
| Rate Schedule                                                                     | Time Sheet Entry Hours and Minutes | Time Sheet Entry Hours and Minutes |
| Minimum Rate                                                                      | 1.00                               | NA                                 |
| Maximum Rate                                                                      | 100.00                             | NA                                 |
| Factor                                                                            | NA                                 | 1.35                               |
| Base Rate Category                                                                | NA                                 | ST                                 |

---

### Create Invoice Adjustments

Create an invoice adjustment in addition to the default Site Tax adjustment:

1. From the Admin menu, select **Invoice Adjustment** in the **Financial Data** section.
2. Click **New**.
3. Enter the details for **Invoice Adjustment 1**, as outlined in the table below.
4. Click **Add**.
5. Repeat steps 2-4 for the other adjustment.

| Field              | Invoice Adjustment 1                                                                                                      | Invoice Adjustment 2                                                                                                      |
| :----------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Type               | Invoice Adjustment                                                                                                        | Credit/Debit Memo Adjustment                                                                                              |
| Name               | VAT                                                                                                                       | VAT                                                                                                                       |
| Default Unit/Value | Percentage/0%                                                                                                             | Percentage/0%                                                                                                             |
| Module             | All Modules except Task Code                                                                                              | All Modules                                                                                                               |
| Usage:             | Available to Supplier Flag, Include in Actual Spend, Include in Estimated and Committed Spend, Applies to Supplier Amount | Available to Supplier Flag, Include in Actual Spend, Include in Estimated and Committed Spend, Applies to Supplier Amount |
| Site Override List | Add the site created and assign value to 20%                                                                              | Add the site created and assign value to 20%                                                                              |
|                    |                                                                                                                           |                                                                                                                           |

### Create Approval Groups

**Set Up**

Add approval groups from different modules and currencies.

1. From the Admin menu, select **Approval Group** in the **Workflow** section.
2. Click **New**.
3. Select **Job Posting** in the **Module** field.
4. Use the information shown in the **Job Posting Approval Group** screen capture below to enter approval group information.

**Note:** Set the Maximum Approval Amount to 0.00. This will allow the approval group to apply to every amount.

5. Click **Add**.
6. Repeat steps 2-5 to create additional job posting approval groups with **GBP**, **EUR**, **USD**, and **AUD** selected as the currencies.
7. Repeat steps 2-6 to create **Work Order**, **Work Order Revision**, and **Time Sheet** approval groups for all currencies.

**Note:** The images of each USD approval group below are from the **Approval Group: Details** page, shown once the approval groups are added. The Create Approval Group page may look different.

**After you create your approval groups, you must associate them to your business units. By selecting the **Include All New Business Units?** check box, SAP Fieldglass will automatically associate your approval groups to new business units; however, you must manually associate them to existing business units.**

**Repeat the following steps for each of your approval groups:**

1. From the Admin menu, select **Approval Group** in the **Workflow** section.
2. Click the **Name** of the desired approval group. The menu on the left side of the page will expand.
3. Click **Business Units (0)** in the menu on the left side of the page.
4. Click **Add**. The **Associate Business Units to Approval Group** dialog box is displayed.
5. Click **Filter**.
6. Select all the available business units.
7. Click **Add**.

**Job Posting Approval Group**

**Work Order Approval Group**

**Work Order Revision Approval Group**

**Time Sheet Approval Group**

**Expense Sheet Approval Group**

### Create Reason Codes

**Set Up**

Add reason codes:

1. In the **Configuration** section of the **Admin** menu, select **Reason**.
2. Click **New**.
3. Add reason code information, as outlined in the table below. You should create reasons for each **Module/Type** combination listed below, but you do not have to use the Name (Reason) provided as it is merely a suggestion.
4. Click **Add**.
5. Repeat steps 2-4 for each reason code you want to add.

| **Module/Type**              | Name                                    |
| ---------------------------- | --------------------------------------- |
| Credit/Debit Memo            | Credit/Debit Memo Incorrect Cost Center |
| Expense Sheet Rejected       | Other: See comments                     |
| Job Posting Closed           | Position No Longer Needed               |
| Job Posting Halt             | Max Submissions Reached                 |
| Job Posting Rejected         | Other: See Comments                     |
| Job Seeker Rejected          | Job Seeker Not Qualified                |
| Time Sheet Rejected          | Incorrect Hours                         |
| Time Sheet Revised           | Incorrect Hours                         |
| Work Order Closed            | Other: See Comments                     |
| Work Order Rejected          | Other: See Comments                     |
| Work Order Revision Rejected | Other: See Comments                     |
| Worker Closed                | Assignment Ended                        |
| Worker Closed                | Assignment Ended Due to Performance     |
| Rating: Neutral              | Do Not Rehire                           |

---

### Create Supplier Invitations

**Set Up**

Invite three Suppliers:

1. From the Admin menu, select **Supplier Invitation** in the **Supplier** section.
2. Click **Invite**.
3. Add the requested information for the first Supplier, as outlined in the table below.
4. Click **Invite**.
5. Repeat steps 2-4 for the second and third Suppliers.

**First Supplier Invitation**

| Field                                                                                                                          | Value                                       |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------- |
| Non-transactional Supplier                                                                                                     | No                                          |
| Non-transactional Suppliers are Suppliers who do not access SAP Fieldglass but are tied to profile workers in the application. |                                             |
| Supplier Name                                                                                                                  | Enter a name for your MSP Supplier company. |
| Primary Contact Person                                                                                                         | First Name                                  |
| Enter a first name for the Supplier administrator.                                                                             |                                             |
| Primary Contact Person                                                                                                         | Last Name                                   |
| Enter a last name for the Supplier administrator.                                                                              |                                             |
| Email                                                                                                                          | Enter your email address.                   |
| MSP Company                                                                                                                    | Yes                                         |
| Manage Services                                                                                                                | Temp, Services, Profile Worker              |
| Service Provided                                                                                                               | Temp, Services, Profile Worker              |
| Register Supplier                                                                                                              | No                                          |
| through Qualification Process                                                                                                  |                                             |

**Second Supplier Invitation**

| Field                                              | Value                                          |
| -------------------------------------------------- | ---------------------------------------------- |
| Non-transactional Supplier                         | No                                             |
| Supplier Name                                      | Enter a name for your second Supplier company. |
| Primary Contact Person                             | First Name                                     |
| Enter a first name for the Supplier administrator. |                                                |
| Primary Contact Person                             | Last Name                                      |
| Enter a last name for the Supplier administrator.  |                                                |
| Email                                              | Enter your email address.                      |
| Service Provided                                   | Temp, Services, Profile Worker                 |

**Third Supplier Invitation**

| Field                                              | Value                                         |
| -------------------------------------------------- | --------------------------------------------- |
| Non-transactional Supplier                         | No                                            |
| Supplier Name                                      | Enter a name for your third Supplier company. |
| Primary Contact Person                             | First Name                                    |
| Enter a first name for the Supplier administrator. |                                               |
| Primary Contact Person                             | Last Name                                     |
| Enter a last name for the Supplier administrator.  |                                               |
| Email                                              | Enter your email address.                     |
| Service Provided                                   | Temp, Services, Profile Worker                |

Once you have received the email invitation to register in SAP Fieldglass, follow the instructions in the email and registration pages to electronically sign the Contractor Access Agreement and become a Supplier:

**Note:** You must be completely signed out of your test environment before clicking the link in the registration email. If you are still signed in, you may see the below invalid URL error. To correct, sign out of the environment and click the link again.

For the purposes of this exercise, on the first screen during the registration process, select **No** for the question, “Do you have an existing Fieldglass account that you would like to link to [Buyer Company]?”

If the “Potential Matches” page appears, do not click **Contact Administrator** for any of the listed companies; click on **Continue to Contractor Access Agreement**.

Once the CAA is signed, you will be taken directly to the Supplier account; the application will confirm that your Supplier account is fully registered, as shown below.

---

### Configure MSP Fee

Once you have registered your MSP Supplier, follow these steps to configure the MSP fee percentage:

1. Log in as the MSP Supplier.
2. From the Admin menu, select **Buyer** in the **Buyer** section.
3. Click on the **Name** of your Buyer company.
4. Click **Edit**.
5. In the **MSP %** field, enter `3.00`.
6. Click **Update**.

---

### Configure Supplier Companies

Once a Supplier is active in SAP Fieldglass, the Supplier company configuration must be updated.

1. From the Client Tools section of the SA page, click **View Buyer Company**.
2. Search for your Buyer company and click on the **Name**.
3. On the **Company Details** page, click on the **Suppliers** tab. This will show you all active Suppliers for your Buyer company. You may want to note the **Code** for each Supplier as this is the unique identifier for each Supplier company.
4. Click on the **Name** of a Supplier company.
5. Click **Edit Configuration**.
6. Configure your Supplier as specified in the **Internal Supplier Configuration Workbook Guide**, enter a **Reason**, and click **Save**.
7. Enable integration connectors as specified in the **Internal Supplier Configuration Workbook Guide** via **More Actions** on the **Company Details** page.

Repeat steps 1-7 to update the company configuration for your remaining Suppliers.

---

### Complete Supplier Setup

After all of your Supplier administrator users are registered, you can complete the Buyer setup of the Supplier. You must associate your Suppliers to the sites you created earlier. If you do not associate Suppliers to sites, the Suppliers will not be able to receive job postings or statements of work.

**Link a Supplier to sites:**

1. Logged in as the Buyer, from the Admin menu select **Supplier** in the **Supplier** section.
2. Click the name of your first Supplier. The menu on the left side of the page will expand.
3. Click **Sites** in the menu on the left side of the page.
4. Click **Add**. The **Associate Sites to Supplier** dialog box is displayed.
5. Verify that all sites are selected.
6. Click **Add**.
7. Repeat steps 1-6 for your remaining two Suppliers.

When you invited your Suppliers, you specified whether they could engage in Temp, Services, or Profile Worker transactions. If these settings need to be edited it can be done from the **Supplier Details** page, and information regarding invoicing can be set up here as well.

**Edit Supplier details:**

1. Logged in as the Buyer, from the Admin menu select **Supplier** in the **Supplier** section.
2. Click the name of your first Supplier to be taken to the **Supplier: Details** page.
3. Click **Edit**.
4. Configure the **Accounting** details for the Supplier per the field definitions table below.
5. Click **Update**.
6. Repeat steps 1-5 for your remaining two Suppliers.

| **Section/Field**                   | Accounting                                                                                                                                                                                                                                                                                                                 |
| ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Consolidated Invoice for Contingent | Select**Created By Buyer** to have this Supplier’s Contingent invoices to be included on a consolidated invoice. If this is selected, once an invoice has been approved it will go into **Pending Consolidation** status.                                                                                                  |
| Consolidated Invoice for Services   | Select**Created By Buyer** to have this Supplier’s services (SOW) invoices to be included on a consolidated invoice. If this is selected, once an invoice has been approved it will go into **Pending Consolidation** status.                                                                                              |
| Service Provided                    | Select which services the Supplier can provide.<ul><li>Temp (Job Posting)</li><li>Services (SOW Bid and SOW)</li><li>Profile Worker</li></ul>                                                                                                                                                                              |
| MSP Service Fee                     | Select**Supplier-funded**, meaning that the MSP Fee is subtracted from the amount paid to the Supplier by the Buyer.                                                                                                                                                                                                       |
| Supplier can create Profile Workers | Select whether the Supplier can create profile workers, or whether the responsibility for creation of profile workers for this Supplier lies solely with the Buyer.                                                                                                                                                        |
| Remittance Type (Contingent)        | Select the way in which payments are made to the Supplier for both<ul><li>Contingent</li><li>Services</li></ul>. <ul><li>Direct Pay: Buyer pays the Supplier and the MSP separately.</li><li>Indirect Pay: Buyer pays the MSP the full amount; MSP pays the Supplier the amount from the Buyer less the MSP fee.</li></ul> |

---

### Create Distribution Lists

**Description**

Distribution lists determine which Suppliers will receive a job posting. When a job posting is distributed, it is sent to the Suppliers on the associated distribution list. Distribution lists can be associated to business units and to specific job posting templates. Often, organizations have multiple distribution lists based on the type of labor provided by the Supplier.

To use the “Auto Distribute” functionality, you must have at least one distribution list and one Supplier set as “Mandatory” or “Preferred” on that list.

**Read more about Supplier Distribution Lists in SAP Help Portal.**

**Example**

A Buyer may have different distribution lists for different types of labor; for instance, a distribution list for Marketing positions may contain different Suppliers or different Supplier tiers than a distribution list for IT positions.

**Set Up**

For your test company, create one distribution list that contains all Suppliers, and name the list “All Suppliers”. You can add more Suppliers and distribution lists at any time.

1. Logged in as the Buyer, from the Admin menu, select **Distribution List** in the **Supplier** section.
2. Click **New**.
3. Enter **All Suppliers** in the **Name** field.
4. Select **Yes** for **Associate all Business Units**.
5. For each Supplier, enter `1` for the **Level** and select **Preferred** in the **Usage** column.
6. Click **Add**.

---

### Create Contingent Type

**Description**

Contingent Type simplifies the job posting process for both Buyers and Suppliers. The feature allows Buyers to define a relevant and simplified user experience, including fields that are visible, specifically for their Contingent labor needs.

**Read more about Contingent Type in SAP Help Portal.**

**Example**

A Buyer may have multiple functional areas within the company that have different Contingent labor requirements, and many job positions that sit under each respectively.

Buyers need a way to define these different requirements at a high level, and align the relevant Job positions to each.

**Set Up**

For your test company, create one contingent type. You can add further contingent types at any time.

1. Logged in as the Buyer, from the Admin menu, select **Contingent Type** in the **Worker** section.
2. Click **New**.
3. Enter the details for the **Contingent Type** as outlined in the table below.

**Note:** Selections should remain as defaulted unless otherwise noted below.

| Field                                                                                                                                 | Value                                          |
| ------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| Name                                                                                                                                  | Default Contingent Type                        |
| Associate all Business Units                                                                                                          | Yes                                            |
| Accounting                                                                                                                            | Allow Time in Hundreths of Hours on Time Sheet |
| Disallow Approval of Time Sheet/Expense Sheet/Invoice when Committed Spend is Exceeded or Committed Spend is Exceeded for Cost Center | Yes                                            |

---

### Create Worker Pay Types

**Description**

Rates and markups may differ for the same position, depending on how the worker is sourced or classified. Worker pay types, in conjunction with rate grids, support this requirement.

Rate grids are set on the job posting template, and there can be a separate rate grid for each worker pay type included on the template. The Supplier selects the appropriate worker pay type when submitting a job seeker.

**Example**

The most common examples of worker pay types are **PAYE** (Pay As You Earn) and Limited Company for UK workers, or worker pay types for those that are recruited versus only payrolled.

**Set Up**

For your test company, you must create at least one worker pay type. Additional worker pay types can be added as desired.

1. In the Admin menu, select **Worker Pay Type** in the **Worker** section.
2. Click **New**.
3. Add information about the worker pay type as outlined in the table below and click **Add**.

| Field                                                           | Worker Pay Type |
| --------------------------------------------------------------- | --------------- |
| Code                                                            | Recruited       |
| Name                                                            | Recruited       |
| Exclude Pay Rate from Tax Adjustment (for rate component rates) | No              |
| Location Attendance Required                                    | No              |

4. If you wish, you can add additional worker pay types.

| Field                                                           | Worker Pay Type |
| --------------------------------------------------------------- | --------------- |
| Code                                                            | Payrolled       |
| Name                                                            | Payrolled       |
| Exclude Pay Rate from Tax Adjustment (for rate component rates) | No              |
| Location Attendance Required                                    | No              |

---

### Create a Job Posting Template

**Set Up**

For your test company, you should create at least one job posting template. You can create as many templates as you wish.

1. In the Admin menu, select **Job Posting Template** in the **Worker** section.
2. Click **New**.
3. Enter the details as shown below.

**Note:** Selections should remain as defaulted unless otherwise noted below.

| Section/Field                | Description/Value                                                                       |
| ---------------------------- | --------------------------------------------------------------------------------------- |
| **Contingent Type**          | Default Contingent Type                                                                 |
| **Base Information**         |                                                                                         |
| Title                        | Accountant                                                                              |
| Description                  | Performs work to ensure employees are paid on time and their paychecks are accurate ... |
| Associate all Business Units | Yes                                                                                     |
| **Labor Type**               | Accounting/Finance                                                                      |
| **Accounting**               |                                                                                         |
| Estimated Additional Spend   | 5.00%                                                                                   |

4. Check the box next to the **Recruited** worker pay type, which you configured earlier. Do not mark it as Primary.
5. Click **Add or remove Rates**. The **Add or Remove Rates on Job Posting Template** dialog box is displayed.

**Note:** Job posting templates can hold rates in different currencies, reducing the need to create separate job posting templates per country.

6. Click **Filter**.
7. Select the **ST | Hr | USD** and **OT | Hr | USD** rates you created.
8. Click **Add Selected**.
9. Click **Update**.
10. Select the **Used to Estimate Calculated Spend** checkbox next to the ST rate you just added.

| Section                                                                                   | Selection Rule                                                                                  |     |
| ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | --- |
| **Posting**                                                                               | This section is where the rules of the job posting are defined.                                 |     |
| On Auto-halt Job Posting when positions are filled                                        |                                                                                                 |     |
| **For Temporary Hire only**                                                               | This section contains rules that apply only to temp work sourced through the application.       |     |
| Off Auto Engage Job Seeker                                                                |                                                                                                 |     |
| Off Auto Register Job Seeker                                                              |                                                                                                 |     |
| Off Suppress Markup in Job Posting (for non-rate component rates)                         |                                                                                                 |     |
| **Display Rates to Suppliers**                                                            | On Show Maximum Rate to Suppliers                                                               |     |
| **Job Seeker**                                                                            | On Supplier must submit Resume/CV                                                               |     |
| **Work Order**                                                                            | This section is where the rules of work orders related to the job posting are defined.          |     |
| On Use approval group if found for Work Order                                             |                                                                                                 |     |
| **Work Order Revision**                                                                   | This section is where the rules of work order revisions related to the job posting are defined. |     |
| On Use approval group only if Work Order Revision exceeds Job Posting Estimated Spend     |                                                                                                 |     |
| **Time/Expense**                                                                          | This section is where the time sheet and expense sheet rules are defined.                       |     |
| On Give Workers access to all Task Codes for the Cost Centers                             |                                                                                                 |     |
| On Allow Worker to submit Time Sheets                                                     |                                                                                                 |     |
| On Disallow Approval of Time/Expense Sheet/Invoice when Maximum Expense Spend is Exceeded |                                                                                                 |     |

11. Click **Continue**.
12. Review your data.
13. Click **Add**.

**Note:** Update the **Maximum rate to $35.26**.

14. Select **All Suppliers** as your **Distribution List**.

**Note:** Review your data and click **Add**.

---

### Enable Work Item Messaging

For your company, ensure that each of the messages listed in the table below is configured to be sent.

1. In the Admin menu, select **Messaging** in the **Messaging** section.
2. Use the **Module** field to locate the message you want to enable.
3. Select the check box next to each message that should be enabled.
4. Click **Enable Message**.
5. Repeat steps 2-4 for the other messages in the table.

| Module                     | Done By  | Activity                      | Recipient      |     |
| -------------------------- | -------- | ----------------------------- | -------------- | --- |
| Interview/Meeting Schedule | Buyer    | Submit to Supplier            | Supplier       |     |
| Interview/Meeting Schedule | Buyer    | Reschedule                    | Supplier       |     |
| Interview/Meeting Schedule | Supplier | Accept                        | Buyer          |     |
| Interview/Meeting Schedule | Supplier | Decline                       | Buyer          |     |
| Interview/Meeting Schedule | Buyer    | Confirm                       | Supplier/Buyer |     |
| Job Posting                | Buyer    | Notify Approvers              | Buyer          |     |
| Job Posting                | Buyer    | Submit                        | Supplier       |     |
| Job Posting                | Buyer    | Redistribute                  | Supplier       |     |
| Job Seeker                 | Buyer    | Reject                        | Supplier       |     |
| Job Seeker                 | Supplier | Withdraw                      | Buyer          |     |
| Work Order                 | Buyer    | Submit                        | Supplier       |     |
| Work Order                 | Supplier | Accept                        | Buyer          |     |
| Work Order                 | Supplier | Decline                       | Buyer          |     |
| Work Order                 | Buyer    | Activate (Track Time/Expense) | Worker         |     |
| Work Order                 | Buyer    | Submit                        | Buyer          |     |
| Work Order                 | Buyer    | Re-Invite Worker              | Worker         |     |
| Work Order                 | Supplier | Re-Invite Worker              | Worker         |     |
| Work Order                 | Buyer    | Submit                        | Supplier       |     |
| Work Order                 | Supplier | Accept                        | Buyer          |     |
| Work Order                 | Supplier | Decline                       | Buyer          |     |
| Work Order                 | Buyer    | Final Approval                | Worker         |     |
| Work Order                 | Buyer    | Final Rejection               | Worker         |     |
| Work Order                 | Worker   | Submit                        | Buyer          |     |
| Work Order                 | Buyer    | Create                        | Supplier       |     |

---
