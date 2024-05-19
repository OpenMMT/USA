
# Model Detail

## Model Assumptions

- The model assumes constant rates for taxes, spending, interest on debt, fiscal multipliers, GDP growth, money supply growth, and policy changes. This simplifies the model but may not capture real-world variability.
- The model assumes immediate effects of changes in federal spending and taxes on consumer spending, firm spending, and savings. This ignores potential lags in economic behavior.
- The model does not account for international trade, capital flows, or external economic shocks, assuming a closed economy for simplicity.


## Model Variables and Parameters

| # | Name <br> (Label) | Formula | Description | Data Source
|----|------------------|-----------------------------------------------|---------------------------------------------------------|-----------------------------------------------------|
| 1. | Federal Taxes   (FT)  |  ![Federal Taxes](https://r.latexeasy.com/image.svg?\frac{dFT}{dt}%20=%20\text{tax\_rate}%20\times%20(CS%20%2B%20Firm_S%20%2D%20C_{\text{Savings}})) | The equation captures the flow of taxes from consumer and firm spending, adjusted for savings. |    - U.S. Treasury: Monthly Treasury Statemen |
| 2. | Federal Spending  (FS)  |  ![Federal Spending](https://r.latexeasy.com/image.svg?\frac{dFS}{dt}%20=%20\text{spending\_rate}%20\times%20(Firm_{Savings}%20+%20C_{Savings})) | The equation links federal spending to firm and consumer savings.| - Congressional Budget Office (CBO): Budget and Economic Data |
| 3. | Inflation Rate  (IR)  |  ![Inflation Rate](https://r.latexeasy.com/image.svg?\frac{dIR}{dt}%20=%20k\times%20\frac{FS%20-%20FT}{ND}) | The relationship between spending, taxes, and national debt is critical for understanding inflation dynamics. | - Bureau of Labor Statistics (BLS): Consumer Price Index (CPI) |
| 4. | National Debt  (ND)  |  ![National Debt](https://r.latexeasy.com/image.svg?\frac{dND}{dt}%20=%20FS%20-%20FT) |  The relationship between spending, taxes, and national debt is critical for understanding inflation dynamics. Introduce a scaling factor k to ensure the units are consistent and to reflect the proportional relationship. The difference between federal spending and taxes directly ties to the accumulation of national debt. | - U.S. Treasury: Debt to the Penny |
| 5. | Interest Payments on National Debt  (IPND)  |  ![Interest Payments on National Debt](https://r.latexeasy.com/image.svg?\frac{dIPND}{dt}%20=%20\text{debt\_interest\_rate}%20\times%20ND) | This captures the compounding effect of debt over time. | - U.S. Treasury: Monthly Statement of the Public Debt | - U.S. Treasury: Monthly Statement of the Public Debt |
| 6. | Consumer Spending  (CS)  |  ![Consumer Spending](https://r.latexeasy.com/image.svg?\frac{dCS}{dt}%20=%20\text{fiscal\_multiplier}%20\times%20FS%20-%20\text{tax\_rate}%20\times%20CS) | This reflects the impact of fiscal policy on consumer behavior. | - BEA: Personal Consumption Expenditures |
| 7. | Consumer Savings  (C\_Savings)  |  ![Consumer Savings](https://r.latexeasy.com/image.svg?\frac{dC_{Savings}}{dt}%20=%20\text{tax\_rate}%20\times%20CS%20-%20FS) | The interplay between taxation and federal spending on consumer savings is crucial. | - BEA: Personal Income and Outlays |
| 8. | Firm Spending  (Firm_S)  |  ![Firm Spending](https://r.latexeasy.com/image.svg?\frac{dFirm_S}{dt}%20=%20\text{fiscal\_multiplier}%20\times%20FS%20-%20\text{tax\_rate}%20\times%20Firm_S) | This models how fiscal policy influences firm behavior. | - BEA: Gross Private Domestic Investment |
| 9. | Firm Investment  (Firm_I)  |  ![Firm Investment](https://r.latexeasy.com/image.svg?\frac{dFirm_I}{dt}%20=%20\text{fiscal\_multiplier}%20\times%20Firm_S%20-%20\text{tax\_rate}%20\times%20Firm_I) | Reflects the impact of fiscal policy on firm investment activities. | - BEA: Gross Private Domestic Investment |
| 10. | Firm Savings  (Firm\_Savings)  |  ![Firm Savings](https://r.latexeasy.com/image.svg?\frac{dFirm_{Savings}}{dt}%20=%20\text{tax\_rate}%20\times%20Firm_S%20-%20FS) | Similar to consumer savings, this captures firm behavior in response to fiscal policy. | - BEA: Gross Private Domestic Investment |
| 11. | Public Spending  (Public_S)  |  ![Public Spending](https://r.latexeasy.com/image.svg?\frac{dPublic_S}{dt}%20=%20FS) |  Represents direct government spending in the economy. | - Congressional Budget Office (CBO): Budget and Economic Data |
| 12. | GDP (GDP)  |  ![GDP](https://r.latexeasy.com/image.svg?\frac{dGDP}{dt}%20=%20\text{growth\_rate}\times%20GDP) | Represents the gross domestic product of the economy. | -Bureau of Economic Analysis (BEA): GDP Data |
| 13. | Money Supply (M2)  |  ![Money Supply](https://r.latexeasy.com/image.svg?\frac{dM2}{dt}%20=%20\text{money\_growth\_rate}\times%20M2) | Represents the total amount of money available in the economy. | -Federal Reserve: M2 Money Stock | 
| 14. | Central Bank Interest Rate (CBIR)  |  ![Central Bank Interest Rates](https://r.latexeasy.com/image.svg?\frac{dCBIR}{dt}%20=%20\text{policy\_change}\times%20CBIR) | Represents the interest rates set by the central bank. | -Federal Reserve: Federal Funds Rate |
| 15. | Tax Rate  | | The rate at which taxes are levied on consumer and firm spending. | - IRS: Federal Tax Rates |
| 16. | Spending Rate  | | The rate at which federal spending occurs, influenced by firm and consumer savings. | - Congressional Budget Office (CBO): Budget and Economic Data |
| 17. | Debt Interest Rate  | | The rate at which interest accrues on the national debt. | - U.S. Treasury: Interest Rate Data |
| 18. | Fiscal Multiplier  | | A factor that measures the impact of government spending on economic activity. | - Economic Research Service (ERS): Fiscal Policy Reports |
| 19. | Growth Rate  | | The rate at which the GDP grows. | - Bureau of Economic Analysis (BEA): GDP Data |
| 20. | Money Growth Rate | |  The rate at which the money supply grows. | - Federal Reserve: M2 Money Stock |
| 21. | Policy Change  | | The rate at which the central bank adjusts interest rates. | - Federal Reserve: Federal Funds Rate |
| 22. | k  | | A scaling factor to ensure units are consistent in the inflation rate equation. | - Model Assumption |
