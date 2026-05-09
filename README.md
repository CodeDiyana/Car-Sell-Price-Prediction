<h1>Car Sell Price Precition </h1>




<h2>Description</h2>
In this research, we used a real dataset on used cars, which was taken from the Kaggle website and collected based on used car ads on eBay. 
The dataset includes features related to technical and economic information of cars. The main features include manufacturer (car brand), model, year of manufacture, mileage (vehicle usage rate), fuel type, transmission, and sales price. These features are among the most important factors affecting the value of used cars and have been used in many related studies and lectures. Sales price, predictive value analysis is the target of this project.

<br />




<h2>Program walk-through:</h2>


- <b>1.Data cleaning and renaming</b> 
- <b>2.Visualizing:</b>
- <b>Distribution of selling price</b> 
- <b>Relationship between mileage and price</b>
- <b>Price difference by fuel type or transmission </b> 
- <b>Top 10 most common makes and their average resale price </b>
- <b>3.Applying classification model whether a car is “High Value” or “Low Value.” (spliting data into test/train,Applying  logistic regression)
</b> 





<h2>Program Visualizations::</h2>

- <b>Distribution of selling price </b> 


<p align="center">

<br/>
<img src="https://i.imgur.com/1uVMLjm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

- <b>relationship between mileage and price </b> 


<p align="center">

<br/>
<img src="https://i.imgur.com/lgHht9Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

 - <b>price difrence by fuel type </b> 


<p align="center">

<br/>
<img src="https://i.imgur.com/3pcHVUk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

 - <b>price by transmission types </b> 


<p align="center">

<br/>
<img src="https://i.imgur.com/QEN40SA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

 - <b> Top 10 repeated brand in datas and medium price of them </b> 


<p align="center">

<br/>
<img src="https://i.imgur.com/xXg0cPK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

  <h2>Normalization Practice::</h2>

  <br />
 a) 1NF Check:
  <br/>All values are atomic (single values per cell). The table satisfies 1NF but has partial and transitive dependencies violating higher normal forms.  <br />

  <br />
 b)Functional Dependencies
: <br />
  <br/>Book_ISBN → Book_Title, Publisher_ID, Publisher_Name  
  <br />Author_ID → Author_Name 
  <br /> Publisher_ID → Publisher_Name   
   <br /> (Book_ISBN, Warehouse_Code) → Copies
 <br />

   <br /> c & d) Normalization Steps with Tables

 <br />
<img src="https://i.imgur.com/SSRmpRk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2NF — Remove Partial Dependencies (attributes depending on only part of composite key):
: <br/>
 <br />Book Table:  
 <br/>

<img src="https://i.imgur.com/jTu7IRS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3NF — Remove Transitive Dependency (Publisher_Name depends on Publisher_ID, not Book_ISBN):
 <br/>
 <br/>
 
 <br/>
Publisher Table:

<img src="https://i.imgur.com/rUhtoA8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<img src="https://i.imgur.com/ZY8HiK1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

