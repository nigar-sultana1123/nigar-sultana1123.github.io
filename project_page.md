# Modeling-Default
 
More than a decade ago, peer-to-peer (P2P) lending services began to connect borrowers and lenders directly through online platforms for micro-credit funding in the absence of traditional banking systems. This idea of lending (or borrowing) money outside the conventional financial system quickly garnered attention, and people began using the P2P service because of its lower transaction and intermediation costs compared to the traditional institutions---the key drivers of interest margins. Moreover, the P2Ps operated outside banking regulatory systems using an online automated system, which implied not carrying loans on their books (thus avoiding liabilities for loans), which helped to minimize the operating cost of P2P services. Consequently, these lower costs are transferred across both the demand and supply network of the market. The benefits to the borrowers revolved around the speed of funding, higher funding rate, ease of the application process, reasonable interest rates, and the promise of non-collateralized loans often at competitive interest rates.
 
 
Although P2P is growing fast, in addition to its highlighted benefits, there is a high exposure of lenders to default, because of asymmetric information. From the record of the P2P lending platform, lenders have little information concerning the borrowers. On the other hand, a borrower has near-complete information about his or her capability of loan repayment.  Given this fact, an investor who is trying to secure a high return on this platform, confronted with a critical question: how risky is the borrower?
 In order to help an investor with this question, P2P services rate each requested loan with a grade that takes into account the borrower's credit history. This grading system represents the relative risk of default among different grades, that is, a lower grade represents a higher chance of default. As discussed earlier, P2P services also provide interest rates corresponding to each grade that, like the grading system, reflects the credit history of the borrower. Therefore, the lower the grade, the higher the default risk and, consequently, the higher the interest rate. An investor is, however, provided with a wide range of additional information about the borrower (for example, loan purpose, income verification, annual income). The contribution of this additional information to the information asymmetry, of course, requires an in-depth analysis. 
 
 ## Problem Statement
 My goal is to study, whether this additional information---besides the grading system---can help the investors to have a more holistic view of each borrower and to take a more educated decision on whether or not to grant the loan. In other words, whether it can reduce the information asymmetry.
 
 ## Data 
 For my analysis, I used data from \textit{Lending Club}, the biggest P2P company in the United States. The sample contains loans funded from 2012 to 2015 including two maturity periods: 36 months and 60 months. Loans with 36 months maturity period considered for the analysis because the loan funded for 60 months maturity period in December 2015, is still unknown. See the "DataAppendix" for more details about the variables.
 ## EDA
 Exploratory data analysis has been done in Tableau. All the graphs are included in the Figures folder. Also the description od EDA can be found in the "ProjectFinalDraft".
  
 ## Modeling
 Discrete-time survival analysis was performed for explaining loan default. The full analysis has been explained in the "ProjectFinalDraft" file.
