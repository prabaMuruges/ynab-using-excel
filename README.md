# ynab-using-excel


I have tried different formats of expense tracking in excel before, but could not stick with any of it as it was very naive and pretty much did not get any solid outcomes from those.

Being a failed expenses tracker for a long time, recently my room-mate suggested using [YNAB](https://app.youneedabudget.com/) and I gave it a try.

There was one best feature in YNAB which is outstanding and creates a real purpose. It's the simplest but I somehow neglected it always, it's **Budgeting**.

* We can create multiple categories (with sub-categories) and budget before starting any real transactions.
  * Example - (Month: January)
  
    Categories | Subcategory | Budget
    -----------|-------------|--------
    Expenses   | Rent        | 700
    Expenses   | Food        | 200
    Expenses   | Transport   | 700
    Investment | Gym         | 200
    Investment | Books       | 700
    Investment | Course      | 200
    Saving     | FD          | 700
    Saving     | PF          | 200

* Then we can input the real transactions made in the month.
  
    Date   | Category (with subcategory) | Outflow
    -------|-----------------------------|--------
    1st Jan| Investment: Books           | 50
    2nd Jan| Expense: Rent               | 50
    ...    | ...                         | ...
    ...    | ...                         | ...
    
* Finally we can see the amount spent versus budgeted amount, this will help us to rebudget for the next month and place the amount in better category :) 

* Inspite of all these nice features and their neat (kind-of) UX, I have decided to stop using it. Reason being I felt it's little expensive (*around **$11** per month*) :D 

* I wanted to continue with this approach and tried to replicate the same in excel. Wanted to share this to get any suggestions or may be useful to someone else :D
