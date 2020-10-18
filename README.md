# GDP-Analysis
## Project Description
In this project I'm going to use global indicators from GapMinder to explore trends in North American economies. In particular I will investigate how employment rate, trade balances and Gross formation Capital(GFC) effect the GDP's of Canada, the United States and Mexico. <br>

## Project Files
The following files were used in my analyis:<br>
> GDP Analysis.ipynb - Jupyter notebook used for analysis<br>
> GDPpercapita.xlsx  - Gross Domestic Product or GDP per capita data on countries<br>
> 15 employ.xlsx - Employment data for 15+ year old demographic<br>
> 15-24 employ.xlsx - Employment data for 15-24 year old demographic<br>
> Investment.xlsx - Gross Capital Formation or GFC per country<br>
> Trade balance.xlsx - Trade balance between imports and exports per country<br>

## Conclusions
The factors that affect GDP are known, however the database did not have all the indicators we needed to verify they were indeed the strongest factors. <br>

I chose the factors:<br>
* Employment rate for ages 15+ <br>
* Employment rate for ages 15-24 <br>
* Trade balance between imports and exports <br>
* Investment by the respective country (Gross Capital Formation or GFC) <br>

All these indicators were chosen from GapMinder because they were calculated proportionally with respect to population or GDP to make analyzing the data more reliable in comparisons. <br>
<br>
* 1. I used employment rate because consumer expenditure is a source of income for the country and I wanted to see if the employment rate affected GDP and therefore consumer expenditure. By checking the mean employment rate for ages 15+ we can see the strongest average also has the strongest GDP, which is the United States. However, this does not conclude that they are correlated. <br>
* 2. The employment rate between ages 15-24 would have negligible impact on the GDP and we could see that from the plots that they roughly follow the same trend as the employment rate for ages 15+. We can conclude that this is not a strong indicator of GDP. <br>
* 3. Finally, the GFC was not a good indicator of GDP because Mexico had the highest mean GFC and the lowest GDP. It is not wrong to say that GFC affects GDP but it is not a strong indicator in the sense that you could make predictions based on its trend. <br>
* 4. The trade balance shows how the country is importing or exporting but not how it is profiting. From my analysis there is no correlation between GDP and trade balance. I can tell this by the mean values for this indicator and the plots displayed. <br>
