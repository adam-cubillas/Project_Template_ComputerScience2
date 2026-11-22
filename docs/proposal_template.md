# 📌 Project Proposal (Draft)

## 📝 Project Title  
Pisay Allowance Tracker 

---

## 🔍 Problem Statement  
What real-world problem does your project want to solve?  
The problem is, when people actually get money, sometimes people are unconscious about how much they spend, and eventually have nothing left, this mostly happens to students. So that’s why we are making an allowance tracker, it keeps track whenever you make or lose any money. It helps people know how much money they have, are conscious of what they are spending, and it helps them really think if they should spend or not.

---

## 🎯 Project Objectives  
Write at least **2–3 clear objectives** your project aims to achieve. Example:  
- Objective 1: To help PSHS scholars monitor their monthly allowance and keep track of their daily expenses 
- Objective 2: To calculate and display the total allowance, total expenses, remaining balance, and spending breakdown by category.  
- Objective 3: To develop a simple Python application that uses JSON file handling to store, retrieve, edit, and delete financial records.  

---

## ⚙️ Planned Features  
Your program must have **at least 5 features (minimum)**.  
We have provided **2 starter ideas** for each dataset — you must design **at least 3 additional features**.  

- Feature 1: Record allowance and expenses  
- Feature 2: View Records 
- Feature 3: Edit Records  
- Feature 4: Delete Records  
- Feature 5: Financial Summary  

*(You may add more features if you like.)*  

---

## ⌨️ Planned Inputs and Outputs  

- **Inputs**  
  1. Transaction Name - The name or description of the allowance or expense
  2. Transaction Type - Whether the record is an allowance or an expense.
  3. Amount - The monetary value of the allowance or expense
  4. Expense Category - The classification of an expense
  5. Record ID - The ID of an existing record that the user wants to edit or delete
  6. Menu Selection - The number corresponding to the feature the user wants to access

- **Outputs**  
  1. Saved Records - A list of all recorded allowances and expenses, including their names, types, amounts, and categories.
  2. Financial Summary - The total allowance received, total expenses, and remaining balance.
  3. Spending Breakdown - The total amount spent in each expense category.
  4. Confirmation Messages - Messages indicating whether a record was successfully added, edited, or deleted.
  5. Error Messages - Notifications when the user enters invalid information, such as an incorrect amount or record ID. 
---

## 🧠 Logic Plan  
Describe your program’s logic:  

### Pseudocode  
**START**

1. Check if the JSON file containing saved records exists.
2. If it exists, load the previously saved records.
3. If it does not exist, create an empty list of records.

4. Display the main menu:
   - Record Allowance
   - Record Expense
   - View Records
   - Edit Record
   - Delete Record
   - Financial Summary
   - Exit

5. Ask the user to enter their menu selection.

6. If the user chooses Record Allowance:
   - Ask for the allowance name.
   - Ask for the amount.
   - Assign a unique Transaction ID.
   - Save the allowance record to the JSON file.

7. If the user chooses Record Expense:
   - Ask for the expense name.
   - Ask for the amount.
   - Display the available expense categories.
   - Ask the user to select a category.
   - Assign a unique Transaction ID.
   - Save the expense record to the JSON file.

8. If the user chooses View Records:
   - Display all saved allowance and expense records.

9. If the user chooses Edit Record:
   - Ask for the Transaction ID.
   - Find the matching record.
   - Allow the user to modify its information.
   - Save the updated record to the JSON file.

10. If the user chooses Delete Record:
    - Ask for the Transaction ID.
    - Find the matching record.
    - Ask the user to confirm the deletion.
    - Delete the selected record.
    - Update the JSON file.

11. If the user chooses Financial Summary:
    - Calculate the total allowance.
    - Calculate the total expenses.
    - Subtract total expenses from total allowance.
    - Calculate the total expenses for each category.
    - Display the financial summary and spending breakdown.

12. If the user chooses Exit:
    - Save all records to the JSON file.
    - Display an exit message.
    - End the program.

13. If the user enters an invalid menu selection:
    - Display an error message.
    - Return to the main menu.

**REPEAT steps 4–13 until the user exits.**

**END**


### Flowchart  
Attach or draw a flowchart showing how the program will work.  

---

## 📂 GitHub Repository Link  
Paste your GitHub repository link here:  
`https://github.com/username/project-proposal`  

---
