# SAP Cash Journal Configuration Guide

## Overview
This guide describes step by step procedures how a user can configure SAP Cash Journal.

## Prerequisites

Before you begin, ensure you have:

- SAP system access
- Appropriate user roles and permissions


## Introduction
The SAP Cash Journal serves as a sub-ledger within bank accounting, designed to manage a business's cash transactions efficiently. It provides automatic calculations and displays of opening and closing balances, along with the total receipts and payments.


## Configure Cash Journal
**To configure the SAP cash journal**:
1. Login to the SAP ERP system.
2. Navigate to the **SAP Easy Access** screen.
3. Then navigate to 'Financial Accounting > Financial Accounting Global Settings > Cash Journal > Define Cash Journal'.
4. To define cash journal settings:
       Create a new cash journal by entering a unique journal code.
       Specify the currency value and assign an appropriate company code.
       Set the parameters for cash journal postings, such as posting keys and account assignments.
5.  Assign users who needs to access the cash journal.
6.	Configure authorization roles to control permissions for cash journal transactions.
7.	To integrate with other modules:
      **Note**: Ensure integration with other financial modules, such as Accounts Payabale and Accounts Receivable, to streamline cash management processes.
8.	To test the configuration:
        Perform test transactions to verify whether the cash journal is functioning as expected.
        Check whether reporting of cash inflows and outflows are configured correctly.
9.	Monitor cash journal and user access regularly to ensure compliance and modify as per the business requirements.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

To configure SAP Cash Journal, it is necessary to perform following configuration:
- Create GL Account for Cash Journal
- Setup Amount limit 
- Define document types for cash journal
- Define number range interval for cash journal
- Maintain Business Transaction
- Setup Print Parameter for Cash Journal
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Create GL Account for Cash Journal
**To create GL Account for Cash Journal**:
1. Execute the TCODE **FS00** in the SAP command field. Alternatively, you can also navigate to **SPRO > Reference IMG > Financial Accounting > General Ledger Accounting**.
![Sample image 1](SAP-Cash-Journal-images/image1.png) 
2. Enter the G/L account and Company codes in the respective fields.
![Sample image 2](Projects/SAP-Cash-Journal-images/image2.png)
3. In the Type/Description tab, in the Control in Chart of Accounts specify G/L Account Type and Account Group from the drop-down list. Enter Short Text and G/L Account long text fields.
**Note**: Ensure to enable account capability to post automatically.
![Sample image 3](Projects/SAP-Cash-Journal-images/image3.png)
4. Click on the Save icon next to the command field.
![Sample image 4](Projects/SAP-Cash-Journal-images/image4.png)

## Setup Amount Limit
**To set up the cash journal amount limit**:
1. Navigate to **SPRO > Reference IMG > Financial Accounting > Bank Accounting > Business Transactions > Cash Journal > Define Amount Limit**.
image1
2. In the **Change View “Cash Journal: Amount Limit”: Overview** screen, click on the **New Entries**. **Note**: In this screen, you will see a list of all previously defined amount limits.
image2
3. Enter Company Code, valid from date, and the maximum amount that a cash journal should hold.
image3
4. Click **Save** icon. The new amount limit is saved.
image4
5. While saving, select the **customizing request ID** in the dialog box.
image5
6. Press **Enter** to save the new amount limit in the system.
image6



  



