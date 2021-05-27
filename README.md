# Collateral Management 

Collateral is a property or an asset that a borrower offers as a way for a lender to secure the loan. Collateral arrangement is a risk reduction tool that mitigates risk by reducing credit exposure. Collateral doesn’t turn a bad counterparty into a good one and doesn’t eliminate credit risk. Instead, it just reduces the loss at the time of default. Collateral arrangement is an essential element in the plumbing of the financial system. 

In the derivatives world, collateral posting is a risk reduction tool that mitigates risk by reducing credit exposure. It allows financial institutions to reduce economic capital and credit risk, free up lines of credit, and expand the range of counterparties. All of these factors contribute to the growth of financial markets. The benefits are broadly acknowledged and affect dealers and end users, as well as the financial system generally. 

The Bankruptcy code affords special treatment to financial derivative contracts that allows counterparties to terminate derivative contracts with a debtor in bankruptcy and seize the underlying collaterals. This presentation gives an overview of collateral arrangement in the derivatives market. It also illustrates how collateral management impact valuation and counterparty credit risk.  

Keywords:
Collateral, credit risk, counterparty credit risk, valuation, credit mitigation




	Collateral Definition
	Collateral is a property or an asset that a borrower offers as a way for a lender to secure the loan.
	Collateral arrangement is a risk reduction tool that mitigates risk by reducing credit exposure.
	Collateral doesn’t turn a bad counterparty into a good one and doesn’t eliminate credit risk. Instead, it just reduces the loss at the time of default.
	Collateral management is an essential element in the plumbing of the financial system.
	Collateral assets: mainly cash, also equities, bonds, MBS, debt instruments.

	Special Treatments in the Derivatives Market
	The Bankruptcy code generally prevents creditors from seizing assets of a firm in bankruptcy. This provision is called the “automatic stay”.
	The code affords special treatment to financial derivative contracts, which exempts these contracts from the “automatic stay”.
	The special treatment is also called a safe harbor.
	The safe harbor allows counterparties to terminate derivative contracts with a debtor in bankruptcy and seize the underlying collaterals.

	Benefits of Collateral Posting
	Reduce credit risk.
	Free credit lines with existing counterparties.
	Increase business with counterparties.
	Expand the range of counterparties.
	Equalize the disparity in counterparty creditworthiness.

	Collateral Arrangement Forms
	There are two types of collateral arrangement: pledge and title transfer.
	Pledge
	The giver posts collateral to the taker.
	The giver still owns the collateral.
	If the giver defaults, the taker can take the cash or sell the securities.
	It is widely used in US.
	Title Transfer
	The taker owns the collateral.
	The giver is only entitled to the return of fungible securities and/or repayment of cash.
	It is widely used in the stock-lending and repo market.

	Credit Support Annex (CSA)
	CSA (or Margin Agreement or Collateral Agreement) is a legal document that regulates collateral posting.
	Trades under a CSA should be also under a netting agreement, but not vice verse.
	It defines a variety of terms related to collateral posting.
	Threshold (TH): it defines the amount below which no collateral is posted.
	Minimum transfer amount (MTA): it is the minimum amount that can be transferred for any margin call.
	Independent amount (or initial margin or haircut): it is the amount of collateral required to open a position.
	Collateral posting rules
	If V <= TH + MTA, no collateral is called.
	If V > TH + MTA, collateral is called and collateral = V-TH-MTA

	Valuation under Collateral Arrangement.
	A simple example: a financial contract pays X at maturity T.
	Valuation without collateral arrangement
	At time T, the contract either defaults or survives.
	The default probability is p and the survival probability is q where q = 1-p.
	The survival payoff is X and the default value is φX where φ is the recovery rate.
	The value is the discounted expectation of all the possible payoffs, i.e.,
V(t)=(pφX+qX)D(t)
Where D(t) is the discount factor.
	Valuation with collateral arrangement
	At time T, the contract either defaults or survives.
	The default probability is p and the survival probability is q where q = 1-p.
	If the party survives, the survival payoff is X and the taker returns the collateral to the giver. In this case, collateral has no effect at all.
	If the party defaults, the default payment is the collateral C. 
	The value is the discounted expectation of all the possible payoffs and given by
V_c (t)=(pC+qX)D(t)
	Normally C>pφ, thus V_c (t)>V(t)
	Collateral affects default payoff only.
	Collateral improves recovery.
	Collateral increases value.

	Credit Exposure under Collateral Arrangement
	Settlement period (call period): it is the time period from collateral called to collateral exchanged.
	Liquidation period (cure period): it is the time period from the most recent exchange of collateral until the defaulting counterparty is closed out.
	Margin period of risk = settlement period + liquidation period.
	Let 〖MTM〗_t=max⁡(∑_i▒〖〖MTM〗_t^i,0)〗 be the portfolio value at time t, where 〖MTM〗_t^i is the value of i-th trade at t.
	If we assume that the collateral asset is cash only, the credit exposure is given by
E_c (t)={■(〖MTM〗_t&if 〖MTM〗_t≤TH+MTA@TH+MTA&if 〖MTM〗_t>TH+MTA)┤
	If the collateral is non cash, 〖MTM〗_t=max⁡(∑_i▒〖〖MTM〗_t^i,0)+〖MTM〗_t^C 〗 where 〖MTM〗_t^C is the value of the collateral asset. In other words, we need to simulate the value change of the collateral asset during margin period of risk.

references:

https://finpricing.com/lib/IrCurveIntroduction.html

https://bitbucket.org/cfrm17/collateral/downloads/collateral-3.pdf


