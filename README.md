<h2>1. Business Problem</h2>
Super Brinquedos is a fictional toy store, and as Children's Day is approaching, the Commercial Manager wants to take advantage of this period to boost sales..
The Commercial Manager requested the creation of a dashboard to understand the store's performance to date and, based on historical data, define the sales strategy.

<h2>2. Business Assumptions</h2>
The data for the month of August is incomplete. However, after analyzing the current data, it is possible to observe small or irrelevant variances in the number of sales compared to other months, both in terms of volume and margin percentage. Due to this fact, the decision was made to include the data for August.

<h2>3. Solution Strategy</h2>
<h4>3.1 Load data from CSV</h4>
<h4>3.2 Basic data treatment on Power BI/Python</h4>
<h4>3.3 Explore and analyze data</h4>
<h4>3.4 Metric creation</h4>
<h4>3.5 Visual Dashboard Creation</h4>
<h4>3.6 Analyze results and draw conclusions</h4>

<h1>4. Business Questions</h1>

<h4>4.1 Which products are the top sellers?</h4>
The top 5 selling products are Product 26, 77, 92, 71, and 97.

<h4>4.2 Which products have the best and worst margins?</h4>
Products with Highest Profit Margin are Product 26, 77, 92, 97, 71;
Products with Highest Percentage Margin are Product 58, 95, 22, 5, 20;
Products with Lowest Profit Margin are Product 80, 56, 4, 76, 24;
Product	with Lowest Profit Margin Percentage are Product 87, 25, 56, 54, 37.

<h4>4.3 What is the evolution of sales in terms of Volume, Sales Value, and Margin?</h4>

4.3.1 Volume
| Month | Volume | Volume % ▲   |
| ----- | ------ | ------------ |
| jan   | 3879   |              |
| fev   | 3433   | -11.50%   	|
| mar   | 4034   | 17.51%   	|
| abr   | 3584   | -11.16%  	|
| mai   | 3839   | 7.11%    	|
| jun   | 3756   | -2.16%   	|
| jul   | 3337   | -11.16%  	|
| ago   | 1910   | -42.76%  	|

4.3.2 Sales
| Month | Sales Value      | Sales Value % ▲ |
| ----- | ---------------- | ----------------|
| jan   | R$ 106520.36     |                 |
| fev   | R$ 96029.24      | -9.85%       	  |
| mar   | R$ 114655.95     | 19.40%       	  |
| abr   | R$ 96813.34      | -15.56%      	  |
| mai   | R$ 106875.86     | 10.39%       	  |
| jun   | R$ 104086.94     | -2.61%       	  |
| jul   | R$ 92356.92      | -11.27%      	  |
| ago   | R$ 52776.27      | -42.86%      	  |

4.3.3 Margin %
| Month | Profit Margin    | Profit Margin % ▲ |
| ----- | ---------------- | ----------------- |
| jan   | R$ 53431.51      |                   |
| fev   | R$ 47876.98      | -10.40%           |
| mar   | R$ 57710.41      | 20.54%            |
| abr   | R$ 48396.99      | -16.14%           |
| mai   | R$ 53943.09      | 11.46%            |
| jun   | R$ 52142.03      | -3.34%            |
| jul   | R$ 46155.13      | -11.48%           |
| ago   | R$ 26496.75      | -42.59%           |

<h4>4.6 What is the best product mix that offers the highest Sales Value and Margin %?</h4>
The category of products that offers the highest sales value is the "Pelúcia" category, which has a margin of 49.98%. Even though it has the lowest profit margin compared to other categories, it still demonstrates the best performance in the combined aspects of sales value and margin percentage. The total sales value for this category is R$211.174,23, corresponding for approximately 27% of the total sales value.

<h4>4.7 What is the percentage growth of sales month over month and year to date?</h4>

Month	Sales %	Year-to-Date Sales %

 | Month | Sales %  | Year-to-Date Sales % |
 | ----- | -------- | -------------------- |
 | jan   | 13.83%   | 13.83%               |
 | fev   | 12.47%   | 26.30%               |
 | mar   | 14.89%   | 41.19%               |
 | abr   | 12.57%   | 53.76%               |
 | mai   | 13.88%   | 67.64%               |
 | jun   | 13.52%   | 81.15%               |
 | jul   | 11.99%   | 93.15%               |
 | ago   | 6.85%    | 100.00%              |

<h2>5. Business Insights</h2>

<h4>5.1 The sales value varies for the same product, potentially reaching over 500%, and a lower volume is not necessarily related to a higher price.</h4>
This observation suggests that sales volume loses some of its relevance as an indicator of profitability, emphasizing the importance of profit margin %. This opens the door to further analysis, such as price optimization, customer segmentation, and discount strategies.

<h4>5.2 Sales distribution is uniform across various perspectives, indicating temporal stability and diversity in products and sellers.</h4>
In this case, it is challenging to identify a specific sales driver, and Pareto assumptions may not be applicable.

<h4>5.3 There is a risk of profit loss; a small variation in margins can make the company more vulnerable to cost-related factors.</h4>
Given the low variation in margin %, it is advisable to expand marketing or product sales strategies, such as seasonal promotions, bundles and packages, and upselling or cross-selling strategies. The Children's Day promotion may be an interesting point of start, however, it would be interesting to develop other strategies to boost sales at specific points throughout the year.

<h2>6. Conclusion</h2>
The dashboards provides the possibility to analysis and get valuable insights into product performance, pricing dynamics, and sales evolution. 
Recommendations include a focus on profit margins, exploration of pricing optimization and marketing strategies, and consideration of potential risks to profitability. The creation of a visual dashboard facilitates ongoing monitoring and informed decision-making to Super Brinquedos company

<img align="center" alt="2_1" src="https://github.com/cliffpk3/super-brinquedos/blob/main/files/sb_01.png"><img>
