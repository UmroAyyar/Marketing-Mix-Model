# Marketing-Mix-Model
We use e-commerce data from a small shopify store to conduct this analysis. 

We built an MLR model to interpret the data better and to identify the marketing cahnnels that have the highest impact on sales.

We the bult a regularized model using both L1 and L2 regularization to ensure that our model was not overfit. The trend of the coefficents was simillar in both the MLR and the regularized models so we will use the MLR coefficents to build our recommendations.

Views both organic and Paid have a high impact on overall sales. For every Paid view we experiance a 2.242 increase in sales and 3.275 impact for every organic view. Email also appears to be a significant with every email view contributing 0.15 to sales. FInally, Social Media which is an interaction term we created for Google and Facebbok views has an impact of 0.069.

The recommendation here is simple, increase focus and investment on all of the mentioned channels. Investing good SEO, and paid content along with Email campaigns is bound to pay off devidents.

Affiliate impressions has a negetive effect with every affiliate view costing 2.036 sales. Since Affiliate programs are expensive to run, eliminating the affiliate program right away is a good practice.

We also see a month over month and week over week sales improvement. this can be causeuse of the time sensetive nature of our sales as seen in the sales timeserise, with sales picking up around the holidays.

Divisions seem to be the single largest impact creating variable. Division B, E, C, I are all highly impactful. It would be prudent to focus on Divisions that have ahigh impact and slowly cull the Divisions that have a low impact in terms of sales.
