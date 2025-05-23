This database was belongs to Kaggle website which is was open source of customer information who brought the bike or not.
For this analysis I use Google sheet to complete this project.
Hopefully,
- I remove duplicates from the data using Data -> Data Clean up -> Remove Duplicates -> From which range of the sheet -> Done.
- Replace Martial Status "M"- "Married", "S"-"Single" by using Shortcut key CTRL+H we recieve pop up of Find & Replace the values in the sheet, enter "M" in the find Column and Replace with "Married"
then select the range between the column and Click the Replace all Button on the bottom vise versa for "S".
- Replace Gender "M"- "Male" and "F"- "Female" like the above processes.
- I explore the data then find the age catagory, we are not use with different age in numbers. We want to create the dashboard so I insert a new column which I was named as "Age Bracket".
- In Age Bracket column I use IF Formula, =IF(L2) For Example, =IF(L2>54,"Old 54+",IF(L2>32,"Adolescent","Invalid"),IF(L2<32,"Middle Age")), This Formula helps me to catagorize the age.
- Now the data was looking good for further process.
- Select all of the data and click Insert-> Pivot Table -> Pop up will appear and asking for range and perform in the sheet or Existing Sheet-> New sheet -> Done.
- Now Pivot table sheet was open, then we click Values add the Income -> click Column add the Purchased Bike -> click Rows and add the column Gender, we already find the average income and who
brought the bike or not with the Gender wise.
- Now time for the Dashboard after analysis drag values of average Income of the customer and drag the values , then click on Insert-> Chart.
- Boom! We have the dashboard, in the editer side remove the Grand total. We can clearly see the visualization of Average Gender who brought the bike with their Average Income or not.
- Like that I create more dashboard like this by using of AI(Artifical Intellenge) with the Command Prompt.
