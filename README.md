# PuttingCreditFactor-Implementation
Data Collection: The high yield bond data is extracted from Bloomberg.
HY_11_09: the basic information of the high yield bond, including: bond name, ISIN, ratings, industry sector and maturity.
MID_PX: the price of all the bonds from 2020-1-31 to 2023-1-31.

Codes: the factors are reproducted from the paper: Putting Credit Factor Investing into Practice.
Due to the limitation of data sources, only implemented 4 factors: OAS, Value, Momentum & Multi-factor.
Then did the backtesting, the backtesing is conducted by stratification.
Some factors are good, others are...quite normal.
Then put restriction(service charge) and evaluate again, as you can predict, the performance won't be as good as before.
If bloomberg could give us more data access, we can did it better:)
