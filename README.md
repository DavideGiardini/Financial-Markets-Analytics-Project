# Financial-Markets-Analytics-Project
Building Portfolios with different Screening strategies based on several companies' indicators.

This Project was written in collaboration with Vittorio Haardt and Alberto Formigoni for the Financial Markets Analytics course in the Master Degree in Data Science.
The aim of the project was to utilize <strong>several key indicators</strong> of several companies to build the Portfolio with the highest expected returns.<br>
The indicators used for the project were more than 40. They included, for example: <strong>PE ratio, EBITDA, Sales and Debt per Share, the Price and all of its Moving Averages, Volatility, Return on Equity, Price to Book Ratio</strong>, ecc.
							For this reason, this project is also testament of our deep knowledge of these fundamental indicators.<br><br>
							In our introductory phase, we built all the tools necessary for our analysis.<br>
							After a first cleaning phase, we built a benchmark that would have been later used to compare all of our Portfolios.
							We then built a <strong>complex Python function</strong> that could emulate a Screening model.
							The function would decide, at every point in time, which stocks to buy and which stocks to sell, based on the companies indicators.
							Then, it would also compute, at every month, the value of the Portfolio, taking into account both our buy/sell operations and the stocks' price's movements.
							This function would then be used (with some slight changes) at every point of the document, to evaluate different Screening techniques.
							<br>
							We then passed on to build other function that would compute different metrics to evaluate the performances of each Portfolio: <strong>Information ratio</strong>, <strong>Sharpe ratio</strong> and <strong>Sortino ratio</strong>.<br>
							<br>
							After setting up all of our tools, we started to build different portfolio with different screening strategies and evaluate their performances.<br>
							We therefore applied a <strong>Sequential Screening</strong> and then a <strong>Simultaneous Screening</strong>.
							After that, we developed a technique to <strong>account for the correlation between the factors</strong>.
							Then we built a <strong>Weighted Portfolio</strong> (weighted on the stocks' volatility), and a Portfolio based on <strong>momentum</strong>.<br>
							For the last point, we were asked to try to implement a <strong>Deep Learning</strong> technique to build the portfolio from the data.
							We decided to use <strong>Prophet</strong>: a Deep Learning algorithm developed by Meta to forecast time series.<br><br>
							The Project went on achieving the best results.
