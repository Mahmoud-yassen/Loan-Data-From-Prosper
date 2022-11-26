# Loan Data From Prosper
## by Mahmoud Yassin


## Loan Data From Prosper

>  Prosper is a peer-to-peer lender that provides personal loans to borrowers with fair or good credit. In This Journey we will explore `Loan data from prosper` dataset which includes`113937` observations and `81` variable including loan status, borrowerAPR, borrower rate , term and more and in this analysis I chose to work with loans originated after July 2009 because some of the crucial features of the analysis doesn't exist before that date so the size after periliminary wrangling is `83161` observations and `9` variables


## Summary of Findings

* The `BorrowerAPR` on average was increasing from 2009 to 2012 and was decreasing from 2012 to 2014 
* The `BorrowerAPR` is highly negatively correlated with `ProsperScore` And `ProsperRating (Alpha)`
* The `BorrowerAPR` is higher on average for the data points with `Not employed` EmploymentStatus
* The `BorrowerAPR` is negatively correlated with `LoanOriginalAmount`
* The `LoanOriginalAmount` on average increases with the increase of rating or score
<ul>
<li>By breaking the relaion between `BorrowerAPR` and `LoanOrignalAmount` by the `ProsperRating (Alpha)` we found two major observations:
    <oL>
        <li> The relation between the `BorrowerAPR` and `LoanOriginalAmount` remains negative for `ProsperRating (Alpha)` From `HR` to `B` that strengthen the initial observation
         <li>The relation between the `BorrowerAPR` and `LoanOriginalAmount` goes from negative to positive for `ProsperRating (Alpha)` of `A` and `AA` which disagree with the initial observation 
             
   </ol>
</li>
<li>By breaking the relaion between `BorrowerAPR` and `LoanOrignalAmount` be the<em>Term</em> It seems that the relation is still negative but the rate is different acorss the `Term` Categories as the relation is stronger for the three year and the five year terms than the one year term And this logical as usually the loan with higher Term have higher Amount. So this strengthen the initial observation
<li> By breaking the relaion between `BorrowerAPR` and `ProsperRating (Alpha)` by the <em>Term</em> we found three major observations:
    <ol>
     <li> The higher the Rating the lower The APR and that agrees with the initial observation but there is more to the story
     <li> the `BorrowerAPR` <strong> decrease </strong> with the increase in the `Term` for data points with rating from `HR` to `C`
     <li> the `BorrowerAPR` <strong>increase</strong> with the increase in the `Term` for data points with rating from `B` to `AA`

   </ol>
</li>
<li> By breaking the relaion between `ProsperScore` and `LoanOrignalAmount` by the `Term` It seems that for the one year term the score doesn't influence the Loan Amount but for the three and five years term the loan amount increases with higher higher score and this can be explained by the lack of data points with one year term
    
</ul>
#### I chose to add them  to the explanatory presentation because they help making a good story and they add value to the presentation


## Key Insights for Presentation

> The main insights is centered around how other features influence Borrower APR and Loan Amount and How they influence each other.
I decided not to add the dead ends or relations that doesn't help conveying the message or doesn't fit in the whole picture