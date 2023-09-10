# SparkML_Activity
# Problem description

The dataset is from a bank, data related to direct marketing campaigns of a Portuguese banking 
institution. The marketing campaigns were based on phone calls. Often, more than one contact to the 
same client was required, to access if the product (bank term deposit) would be (or not) subscribed. 
The data and attribute description are in the folder.

Dataset Description 
The dataset has the following attributes:
1. unique sequence id
2. age (numeric)
3. job : type of job (categorical: 
"admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "bluecollar","self-employed","retired","technician","services")
4. marital_status : marital status (categorical: "married","divorced","single"; note: "divorced" means 
divorced or widowed)
5. education (categorical: "unknown","secondary","primary","tertiary")
6. default: has credit in default? (binary: "yes","no")
7. balance: average yearly balance, in euros (numeric)
8. housing: has housing loan? (binary: "yes","no")
9. loan: has personal loan? (binary: "yes","no")
10. contact: contact communication type (categorical: "unknown","telephone","cellular")
11. day: last contact day of the month (numeric)
12. month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
13. duration: last contact duration, in seconds (numeric)
14. campaign: number of contacts performed during this campaign and for this client (numeric, 
includes last contact)
15. pdays: number of days that passed by after the client was last contacted from a previous campaign 
(numeric, -1 means client was not previously contacted)
16. previous: number of contacts performed before this campaign and for this client (numeric)
17. poutcome: outcome of the previous marketing campaign (categorical: 
"unknown","other","failure","success")
18. **opened_new_td_act_no_yes - has the client subscribed to a term deposit? (binary: "yes","no")**


The idea is we have a set of information about a person whether it's their age the job they have  
marital status whether they have a loan with the bank or not etc. We're trying to decide here whether 
the person will open a new deposit account with this bank.
