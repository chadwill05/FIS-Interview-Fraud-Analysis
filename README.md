# FIS-Interview-Fraud-Analysis

I recently completed FIS' Card Fraud Analytics - Analyst Excel Comprehension.

I have decided to take this a step further and add further analysis and go deeper into the dataset. 

In this repository you will see a cleaned up Card Fraud Dataset. All this data was uploaded to a Postgresql Database for safekeeping and uploaded via csv to Google Colab (Jupyter Notebook) for further Python Analysis. 

**Cons with this dataset: There was no Date Timestamp** 


**5 QUESTIONS I wanted to look further into**
1. **Identify High-Risk Transactions**: What are the top 10 transactions with the highest fraud scores, and what characteristics do they share?
2. **Fraud Score Distribution and Outliers**: What is the distribution of fraud scores across the dataset?
3. **Merchant Category Analysis**: How do transaction amounts and fraud scores vary across different merchant categories (SIC Codes)?
4. **Geographical Analysis**: Which countries or states have the highest average fraud scores?
5. **Correlation Between Fraud Scores and Transaction Amounts**: Is there a correlation between transaction amounts and fraud scores?
6. **Point of Sale Entry Mode Analysis**: How do fraud scores differ by POS entry mode?


**TABLES IN THIS DATASET**
1. Trn Auth Post: Transaction Authorization Posting. This likely refers to the status or details of the authorization for a transaction.
2. Trn Pos Ent Cd: Transaction Point of Sale Entry Code. This could indicate how the transaction was entered at the point of sale, such as swiped, chip read, manually entered, etc.
2. Sic Cd: Standard Industrial Classification Code. This is a code that indicates the type of business or industry of the merchant.
4. Sic Desc: Standard Industrial Classification Description. The description that corresponds to the SIC code, detailing the type of merchant or industry.
5. Mer Cnty Cd: Merchant Country Code. The country code where the merchant is located.
6. Cntry: Country. This could also be the country of the transaction or the country associated with the account.
7. Mer St: Merchant State. The state or region where the merchant is located.
8. Mer Cty: Merchant City. The city where the merchant is located.
9. Mer Nm: Merchant Name. The name of the merchant where the transaction took place.
10. Acct Nbr: Account Number. The account number associated with the transaction.
11. Frd Scor: Fraud Score. A score indicating the likelihood that the transaction is fraudulent.
12. Ext Scor2: External Score 2. This could be an additional score provided by an external system or model to assess the transaction.
13. Ext Scor1: External Score 1. Similar to Ext Scor2, another score from an external source.
14. Rltm Req: Real-time Request. This might indicate whether a real-time check or validation was requested for the transaction.
15. Usr Ind 4: User Indicator 4. This could be a custom field used for specific user-related data or flags.
16. Mer Id: Merchant ID. A unique identifier for the merchant.
17. Terminal Id: Terminal ID. The identifier for the point of sale terminal where the transaction occurred.
18. Terminal Entry Cap: Terminal Entry Capability. Indicates the capabilities of the terminal, such as chip, magnetic stripe, contactless, etc.
19. Client 2 Xid: Client 2 External ID. A secondary identifier for the client, possibly used for linking with external systems.
20. Trn Amt: Transaction Amount. The monetary value of the transaction.
21. Fraud_Score_Bands: This might be a categorical representation of the fraud score, grouped into bands (e.g., low, medium, high risk).
22. BIN: Bank Identification Number. The first few digits of a credit card number, which identify the issuing bank.
23. Average Risk Score: An average score of risk, possibly aggregated from multiple scores or over multiple transactions.
24. POS_Entry_Mode: Point of Sale Entry Mode. Describes how the card information was entered during the transaction.
25. Merchant_Location: The physical or registered location of the merchant.

