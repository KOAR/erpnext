#Managing Transactions In Multiple Currency

You can make transaction in your base currency as well as in customer or supplier currencies. When you make transaction in your customer or supplier currency, the same currency reflects only in print format of that transaction. And system pass back end
entry in your base currency.
<br>
<br>To understand this scenario will take example of Sales Invoice, where your base currency is INR and your customer currency is USD.
<br>
<br>Following are steps to create Sales Invoice in customer currency.
<br>&nbsp;
<br><b>Step 1:</b> Go to Selling &gt;&gt; Documents &gt;&gt; Sales Invoice &gt;&gt; (+) New.
<br>
<br><b>Step 2:</b> Select Customer and Enter other details.
<br>
<br>
<img src="{{docs_base_path}}/assets/img/articles/Selection_012.png">
<br><b>Step 3:</b> Select customer currency and related Price List.
<br>
<br>
<img src="{{docs_base_path}}/assets/img/articles/Selection_016.png">
<br>
<br>
<br>On selecting customer currency 'Exchange Rate' field will open under Currency field, where you will enter exchange rate of customer currency to basic currency. In our case for USD to INR. You can check exchange rate online
for your customer currency to your currency.
<br>
<br>Also you can set default customer currency in customer master. Which will auto fetch in transactions.
<br>
<br>
<img src="{{docs_base_path}}/assets/img/articles/Selection_017.png">&nbsp;
<br>System has Currency Exchange master, where you can set currency exchange masters for your multiple currencies. To Set this go to Accounts &gt; Setup &gt; Currency Exchange. <br><br><b>Step 4:</b> Select Item details.<br>
<br>On selecting Item details Sales invoice Total section will look like below image.
<br>
<br>
<img src="{{docs_base_path}}/assets/img/articles/Selection_018.png" width="750">
<br>
<br>
<br>
<b>Step 5:</b> Save and Submit <br><br>Enter other details like Taxes and charges, Terms and Condition if there and save and submit the invoice form. After submit click on Printer Icon to check print preview. The same document print or email document will you send to your customer or supplier.<br>For our case it will look as below image.<br><br><img src="{{docs_base_path}}/assets/img/articles/Selection_019.png">&nbsp;&nbsp; <br>
<br>
<br>