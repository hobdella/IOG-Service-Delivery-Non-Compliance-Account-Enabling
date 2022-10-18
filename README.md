# IOG-Service-Delivery-Non-Compliance-Account-Enabling

**Overview**

Cyber Defence manages compliance training on behalf od the company. The non-compliance process deals with the disabling of user accounts following a process of reminders and a contiued failure to complete assigned training. Once identified for deactivation a sperate process deals with disabling the account. This service deals with the enabling of the disabled account and the process to be followed. There are two types of deactivation 1st time and 2nd time, they have different processes to follow.

**Enabling the Account - 1st deactivation**

1. This process is initiated by an update on the Teams channel OG-DS Non-Compliance Deactivations along the lines of "Hi, can the Cyber Defense/RCG Training Sheet be updated today please - any questions, let me know,"

2. Create a new Request for Change ticket (Simple Change) and put the requester as the name of the person who requested this deactivation;

3. The worksheet(s) are located under the Files menu on the OG-DS Non-Compliance Deactivations Teams channel.

4. The worksheet will list the new entries that need actioning 

5. Create a new CSV file in the following form NonComplianceDDMMYYY.csv

6. For each different note create a new CSV file and to differentiate it append the file name with an _n (ie NonComplianceDDMMYYY_1.csv)

7. Look up usernames in AD always ensuring the employee ID matches the user you have found (names will not be unique, Employee ID are always unique.

8. List the usernames in column A,  one entry per line.

9. Open your PowerShell ISE (run-as admin) and load the deactivations script into the console.

10. Amend lines 7 (inputFile), 10 (outputFile) and 17  (ADtext) 

11. Save and Run the script

12. Once the script has run check AD to ensure the accounts are disabled and the telephone tab is updated.

13. Attach the log file to the ticket 

14. Update the worksheet

15. Complete and save the ticket,

16. Update the Teams channel confirming the deactivations have been actioned and add the ticket number.

**Enabling the Account - 2nd deactivation** 

It is imperative that you handle these differently to the 1st Deactivations.
 
2nd Deactivation – Telephone Tab Note:
 
User did not complete RBI Cyber Defense 2020 after first deactivation. Please refer user to HRBP: Elizabeth Stewart - 07/05/2020 – LM
 
As per the notes, you cannot enable the account without direction from the relevant HR Partner who is mentioned by name in the note. Only when we get an instruction from the HR Partner (or any other business partner in their absence) can we enable the account. When you receive that instruction in email add it to the ticket then enable the account and update the spreadsheet as normal.

