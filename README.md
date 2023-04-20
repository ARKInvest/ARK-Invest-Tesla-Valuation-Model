# ARK-Invest-Tesla-Valuation-Model

V7 published 04/20/23

This file “Tesla 2027 Valuation Extract for Github” includes an extract of our 2027 price target model for Tesla. Please read ARK’s blog https://ark-invest.com/articles/valuation-models/arks-tesla-price-target-2027/ for a more detailed discussion of our assessment, updates since our last published model, and key components of the model.
ARK used a Monte Carlo simulation to arrive at our estimated price target for Tesla as well as our bull and bear price targets.
A description of each worksheet in the file:

“Tesla Example Valuation” worksheet allows users to provide their own inputs for a fundamental-based valuation of Tesla. Users can change the 5 key drivers of the model in cells J12-J17, as well as  36 other inputs in cells H19-60. Note that because our price target is derived from a Monte Carlo analysis, there is no one single bear and bull case, but ARK has given example inputs for a bull and bear case in columns L and M.

The “Valuation ASP Tables” worksheet allows the user to change both vehicle average selling price and addressable market at each price point. One can also change the price per mile for an autonomous robotaxi, as well as the inputs for the adoption curve for the percent of Tesla’s fleet that is operating in the ride-hail network. This worksheet feeds into both the “Tesla Valuation” tab and the “Monte Carlo Single Simulation” tab.

The “Tesla Valuation Inputs” worksheet allows users to adjust the minimum, bear case, bull case, and maximum inputs for each variable. All variables are modeled as normally distributed with the bear and bull case inputs determining the values one standard deviation below/above the mean. The maximum and minimum inputs are used to exclude all distributions falling outside of the normal range from the analysis. Note that the “probability that robotaxis launch” row is the only binary input. When changing variables in this worksheet it may be necessary to wait to allow the simulation to calculate. Clicking immediately on another cell within the worksheet could cut the simulation short and provide inaccurate results. The output of the model is a probabilistic range of values. 

A single simulated outcome is visible on the “Monte Carlo Single Simulation” worksheet; and a collection of all the simulations is visible on the “Monte Carlo Simulation Output” worksheet. A static example of 5,000 simulations using ARK’s inputs and assumptions is included in the “Example 5,000 Simulations” tab.

We will welcome all questions and constructive criticism and feedback.



V6 published 4/14/22 

This file “Tesla 2026 Valuation Extract for Github” includes an extract of our 2026 price target model for Tesla. Please read ARK’s blog for or a more detailed discussion of our assessment, updates since our last published model, and key components of the model. 

ARK used a Monte Carlo simulation to arrive at our estimated price target for Tesla as well as our bull and bear price targets. 

A description of each worksheet in the file: 

“Tesla Example Valuation” worksheet allows users to provide their own inputs for a fundamental-based valuation of Tesla. Users can change the 5 key drivers of the model in cells H12-H17, as well as 32 other inputs in cells H19-55. Note that because our price target is derived from a Monte Carlo analysis, there is no one single bear and bull case, but ARK has given example inputs for a bull and bear case in columns K and L. 

The “Valuation ASP Tables” worksheet allows the user to change both vehicle average selling price and addressable market at each price point. One can also change the price per mile for an autonomous robotaxi, as well as the inputs for the adoption curve for the percent of Tesla’s fleet that is operating in the ride-hail network. This worksheet feeds into both the “Tesla Valuation” tab and the “Monte Carlo Valuation” tab. 

The “Tesla Valuation Inputs” worksheet the user can adjust the minimum, bear case, bull case, and maximum inputs for each variable. All variables are modeled as normally distributed with the bear and bull case inputs determining the values one standard deviation below/above the mean. The maximum and minimum inputs are used to exclude all distributions falling outside of the normal range from the analysis. Note that the “probability that robotaxis launch” row is the only binary input. When changing variables in this worksheet it may be necessary to wait to allow the simulation to calculate. Clicking immediately on another cell within the worksheet could cut the simulation short and provide inaccurate results. The output of the model is a probabilistic range of values. A single simulated outcome is visible on the “Monte Carlo Single Simulation” worksheet; and a collection of all the simulations is visible on the “Monte Carlo Simulation Output” worksheet. A static example of 5,000 simulations using ARK’s inputs and assumptions is included in the “Example 5,000 Simulations” tab. 

We will welcome all questions and constructive criticism and feedback. 


V5 published 3/19/21

This file “Tesla 2025 Valuation Extract for Github_3.18.21” includes our 2025 price target model for Tesla. Please read ARK’s blog (https://ark-invest.com/articles/analyst-research/tesla-price-target-2/) for or a more detailed discussion of our assessment, updates since our last published model, and key components of the model. ARK used a Monte Carlo simulation to arrive at our estimated price target for Tesla as well as our bull and bear price targets. 

A description of each worksheet in the file:

“Tesla Valuation” worksheet allows users to provide their own inputs for a fundamental-based valuation of Tesla. Users can change the 5 key drivers of the model in cells H12-H17, as well as 28 other inputs in cells H19-51. Note that because our price target is derived from a Monte Carlo analysis, there is no one single bear and bull case, but ARK has given example inputs for a bull and bear case in columns J and K.

The “Valuation ASP Tables” worksheet allows the user to change both vehicle average selling price and addressable market at each price point. One can also change the price per mile for an autonomous robotaxi.

The “Monte Carlo Inputs” worksheet the user can adjust the minimum, bear case, bull case, and maximum inputs for each variable. All variables are modeled as normally distributed with the bear and bull case inputs determining the values one standard deviation below/above the mean. The maximum and minimum inputs are used to exclude all distributions falling outside of the normal range from the analysis. Note that the “probability that robotaxis launch” row is the only binary input. When changing variables in this worksheet it may be necessary to wait to allow the simulation to calculate. Clicking immediately on another cell within the worksheet could cut the simulation short and provide inaccurate results. 
The “Monte Carlo ASP Tables” worksheet allows the user to change both vehicle average selling price and addressable market at each price point. One can also change the price per mile for an autonomous robotaxi.
The output of the model is a probabilistic range of values. A single simulated outcome is visible on the “Monte Carlo Valuation” worksheet; and a collection of all the simulations is visible on the “Monte Carlo Simulations” worksheet. A static example of 5,000 simulations using ARK’s inputs and assumptions is included in the “Example 5,000 Simulations” tab. 

We will welcome all questions and constructive criticism and feedback.
________________________________________________________________________________________

V4 published 3/25/20

Update 3/19/20: We adjusted our Tesla valuation to account for the estimated impact of COVID-19. We have added an input that allows users to adjust factory utilization and realized average selling price (ASP) assumptions for 2020. Note that these changes have adjusted our bear, bull, and expected value price targets for Tesla in 2024. 

This file “Tesla 2024 Valuation Extract for Github_3.25.20_v4” contains three different Tesla valuation extracts for users to experiment with their own inputs. The first model assumes ARK’s current research and underlying inputs are correct, but that our probabilities of events occurring, like autonomous robotaxis launching, are subject to change. The second model allows the user to change the underlying inputs but does not provide a probabilistic outcome. The third model allows the user to change both probabilities and inputs. Please read ARK’s blog (https://ark-invest.com/research/tesla-price-target) for or a more detailed discussion of our assessment of the key drivers determining.

ARK Invest Tesla Scenario Probability Model [“Probabilities” worksheet]

This model allows users to input their own probabilities for each of the following:

•	Autonomous Capability – Will Tesla launch a fully autonomous taxi service successfully?

•	Capital Efficiency – Will Tesla scale factories capital efficiently? 

•	Gross Margins – Will Tesla’s cost of manufacturing vehicles continue to fall in line with Wright’s Law?

•	Access to Capital Markets – If Tesla is unable to lower costs, launch an autonomous taxi network, or become capital efficient, will it also be denied access to the capital markets?

•	Black Swan Event – Will Tesla go bankrupt?

The output is a probability weighted average price for Tesla in the year 2024,  as well as a bull and bear case. Note that user inputs will adjust the probability at which each scenario occurs while using ARK’s estimated price targets for each probability weighted scenario in column H to calculate bull, bear, and probability weighted average price. Read ARK's Blog with further explanation of our assumptions and thoughts on Tesla here https://ark-invest.com/research/tesla-price-target

Tesla Bottom Up Model [Tesla Valuation and Valuation ASP Tables worksheets]

This model allows users to provide their own inputs for a fundamental-based valuation of Tesla. The “key drivers” are the inputs ARK described in detail in the blog linked above. We have included a representative set of inputs for these variables for ARK’s current bear and bull cases for reference. The “Valuation ASP Tables” worksheet allows the user to change both vehicle average selling price and addressable market at each price point. One can also change the price per mile for an autonomous robotaxi.

The output of the model is a probability weighted average value and financial metrics in the year 2024.

Tesla Monte Carlo Model [Monte Carlo Inputs, Monte Carlo ASP Tables, Monte Carlo Valuation, and Monte Carlo Simulation worksheets]

This model allows users to provide a range of inputs for a bottom up valuation of Tesla. On the “Monte Carlo Inputs” worksheet the user can adjust the minimum, bear case, bull case, and maximum inputs for each variable. All variables are modeled as normally distributed with the bear and bull case inputs determining the values one standard deviation below/above the mean. The maximum and minimum inputs are used to exclude all distributions falling outside of the normal range from the analysis. Note that the “probability that robotaxis launch” row is the only binary input. When changing variables in this worksheet it may be necessary to wait to allow the simulation to calculate. Clicking immediately on another cell within the worksheet could cut the simulation short and provide inaccurate results. The “Monte Carlo ASP Tables” worksheet allows the user to change both vehicle average selling price and addressable market at each price point. One can also change the price per mile for an autonomous robotaxi.

The output of the model is a probabilistic range of values. Relevant charts are on the “Monte Carlo Inputs” worksheet; a single simulated outcome is visible on the “Monte Carlo Valuation” worksheet; and a collection of all the simulations is visible on the “Monte Carlo Simulations” worksheet.

Note, the distribution of price targets arising from the Monte Carlo simulation would imply a narrower bull vs bear outcome-range than our manual tuning would suggest. We still believe that the broader dispersion of outcomes is a more likely outcome due to capital markets reflexivity—if things are going poorly for Tesla then the debt markets will treat them more skeptically, and vice versa—whereas the Monte Carlo simulation treats capital markets receptiveness independently of financial performance.

We will welcome all questions and constructive criticism and feedback. 

---------------------------------------------------------------------------

ARK’s Old 2023 Tesla Valuation Model (file “Tesla Valuation for Github_5.27.19_v3.5“):

V1 published 5/22/19. Read ARK’s corresponding blog with further explanation of our assumptions and thoughts on Tesla here: https://ark-invest.com/research/tesla-valuation-model

V2 published 5/23/19 fixes: 2018 ASP (was previously just Model 3 ASP), slight correction on 2018 sales units, and fix of EBITDA margin formula

V3 published 5/27/19 Performed a broader extraction of balance sheet feed-throughs from the underlying model to allow the extract to more intuitively respond to different capital intensity expectations and unit sales expectations. Minor formula fix on 5/29/19. Updated debt from 2019 capital raise 5/30/19.

Authors: Sam Korus, Tasha Keeney, Brett Winton


Disclosure:
This work is licensed under a Creative Commons Attribution-Non-Commercial 4.0 International License.
You may not use the material for commercial purposes without first obtaining written permission.

2020, ARK Investment Management LLC. All content is original and has been researched and produced by ARK Investment Management LLC (“ARK”) unless otherwise stated herein. 

This material is for informational purposes only and does not constitute, either explicitly or implicitly, any provision of services or products by ARK. Nothing contained herein constitutes investment, legal, tax or other advice and is not to be relied on in making an investment or other decision. Investors should determine for themselves whether a particular service or product is suitable for their investment needs or should seek such professional advice for their particular situation.

This material is intended only to provide observations and views of the author(s) at the time of writing, both of which are subject to change at any time without prior notice. Certain of the statements contained herein are statements of future expectations and other forward-looking statements that are based on ARK's current views and assumptions and involve known and unknown risks and uncertainties that could cause actual results, performance or events to differ materially from those expressed or implied in such statements. Past performance is no guarantee of future results. Equities may decline in value due to both real and perceived general market, economic, and industry conditions. 

ARK's statements are not an endorsement of any company or a recommendation to buy,sell, or hold any security. For a list of all purchases and sales made by ARK for client accounts during the past year that could be considered by the SEC as recommendations, please go to https://ark-invest.com/wp-content/trades/ARK_Trades.pdf. It should not be assumed that recommendations made in the future will be profitable or will equal the performance of the securities in this list. For full disclosures, please go to https://ark-invest.com/terms-of-use.

While ARK’s current assessment of the subject company may be positive, please note that it may be necessary for ARK to liquidate or reduce position sizes prior to the company attaining any indicated valuation prices due to a variety of conditions including, but not limited to, client specific guidelines, changing market conditions, investor activity, fundamental changes in the company’s business model and competitive landscape, headline risk, and government/regulatory activity.  Additionally, ARK does not have investment banking, consulting, or any type of fee-paying relationship with the subject company.

