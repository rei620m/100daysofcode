## 100daysofcode
Details about the challenge can be found at [100daysofcode.com](https://www.100daysofcode.com/) or the [official repo](https://github.com/Kallaway/100-days-of-code)

Start date: 9/25/2024<br>
End date: TBD

## Log

|Day|Date|Project / What I Learned| 
|-|-|-| 
|1|9/25|Html form| 
|2|9/26|[Gohan_dousuru](https://github.com/rei620m/gohan_dousuru)| 
|3|9/27|[Gohan_dousuru](https://github.com/rei620m/gohan_dousuru)|
|4|9/28|[Luxeritas_custom](https://github.com/rei620m/luxeritas_custom): custom cursor on wordpress theme| 
|5|9/29|[Gohan_dousuru](https://github.com/rei620m/gohan_dousuru)| 
|6|9/30|Html form<br>Project inspiration: [https://whatwebcando.today/](https://whatwebcando.today/)| 
|7|10/1|[Nobi](https://github.com/rei620m/nobi), [Google_flight_search.py](https://github.com/rei620m/python_automation/blob/main/google_flight_search.py), APIs in python| 
|8|10/2|Html form| 
|9|10/3|Html form<br>・ Use [input type="text"] instead of date for more flexibility on mobile<br>・ Need to run validation to only accept numbers and "/" or "-"<br>・Cross-browser compatibility: [caniuse.com/input-datetime](https://caniuse.com/input-datetime)| 
|10|10/4|Supervised learning with scikit-learn<br><code># Evaluate test-set accuracy</code><br><code>from sklearn.metrics import accuracy_score</code><br><code>accuracy_score(y_test, y_pred)</code>| 
|11|10/5|Binary classification<br>・ Logistic regression and SVM algorithms are natively designed for binary classifications<br>・ Can also use knn and decision trees| 
|12|10/6|Html tooltip on mobile| 
|13|10/7|[Tailwind css](https://tailwindcss.com/docs/installation)<br>・ Include tailwind's css file via CDN or generating it during development<br>・ Customize colours, spacing, breakpoints, etc. with the configuration file <code>tailwind.config.js</code><br>・ Style elements by adding tailwind utility classes in html file<br>・<code>prefers-color-scheme</code> media query 'dark' modifier for dark mode<br>・ For production, use PurgeCSS to remove unused classes from the css file| 
|14|10/8|Time series analysis in R<br>・ use<code>log()</code>to stabilise variability or linearise rapid growth pattern<br>・<code>tx.plot()</code>plots regular time series data<br>・ zoo or xts package can also handle irregular time series data<br>・<code>diff(..., lag = s)</code>calculates the length s seasonal change series<br>&nbsp;&nbsp;&nbsp;&nbsp;・ ex. s=12 for monthly data, s=4 for quarterly datas<br>&nbsp;&nbsp;&nbsp;&nbsp;・ default for first differencing is lag=1|
|15|10/9|Time series analysis in R and python<br>・ ARIMA<br>&nbsp;&nbsp;&nbsp;&nbsp;・ statsmodels in python, forecast package in R<br>&nbsp;&nbsp;&nbsp;&nbsp;・ Combination of AutoRegressive (AR), Integrated (I), and Moving Average (MA)<br>&nbsp;&nbsp;&nbsp;&nbsp;・ Assumes a linear relationship between past values and future values<br>&nbsp;&nbsp;&nbsp;&nbsp;・ Requires constant mean and variance over time<br>・ Prophet<br>&nbsp;&nbsp;&nbsp;&nbsp;・ fbprophet in python, prophet package in R<br>&nbsp;&nbsp;&nbsp;&nbsp;・ Automatically detects changes in trend using "changepoints" and adjust forecasts accordingly<br>&nbsp;&nbsp;&nbsp;&nbsp;・ Robust to missing data, outliers, and is more flexible in handling seasonality and non-linear trends|
|16|10/10|Generate word cloud from survey responses in R (English only)|
|17|10/11|[Wordcloud](https://github.com/rei620m/wordcloud): translate multilingual survey responses and generate word cloud in English<br>・ textTinyR and translateR require devtools for installation from GitHub<br><code>install.packages("devtools")</code><br><code>devtools::install_github("mlampros/textTinyR")</code><br><code>devtools::install_github("ropensci/translateR")</code>|
|18|10/12|Query snowflake data on databricks|
|19|10/13|Distribution plot and binning with numpy, matplotlib, seaborn|
|20|10/14|Rfm model in python|
|21|10/15|Read and write data from snowflake and treasure data in databricks. To convert pandas to spark df, upgrade to DBR 13.x or downgrade to pandas 1.x|
|22|10/16|Html form|
|23|10/17|Html form|
|24|10/18|Html form|
|25|10/19|Time series analysis with prophet<br>・ Designed for univariate time series<br>・ For multiple input variables, use additional regressors<br>・ For multiple related output variables, just model each one separately as univariate time series, or use the forecast values of one variable as inputs to the next<br>・ Can also consider more advanced models like VAR or LSTM|
|26|10/20|Agile process on github projects|
|27|10/21|Html form|
|28|10/22|Html form|
|29|10/23|Time series analysis with prophet<br>・ By default, prophet uses 80% confidence interval, meaning there's an 80% chance that the actual value will fall between yhat_lower and yhat_upper|
|30|10/24||
|31|10/25||
|32|10/26||
|33|10/27||
|34|10/28||
|35|10/29||
|36|10/30||
|37|10/31||
|38|11/1||
|39|11/2||
|40|11/3||
|41|11/4||
|42|11/5||
|43|11/6||
|44|11/7||
|45|11/8||
|46|11/9||
|47|11/10||
|48|11/11||
|49|11/12||
|50|11/13||
|51|11/14||
|52|11/15||
|53|11/16||
|54|11/17||
|55|11/18||
|56|11/19||
|57|11/20||
|58|11/21||
|59|11/22||
|60|11/23||
|61|11/24||
|62|11/25||
|63|11/26||
|64|11/27||
|65|11/28||
|66|11/29||
|67|11/30||
|68|12/1||
|69|12/2||
|70|12/3||
|71|12/4||
|72|12/5||
|73|12/6||
|74|12/7||
|75|12/8||
|76|12/9||
|77|12/10||
|78|12/11||
|79|12/12||
|80|12/13||
|81|12/14||
|82|12/15||
|83|12/16||
|84|12/17||
|85|12/18||
|86|12/19||
|87|12/20||
|88|12/21||
|89|12/22||
|90|12/23||
|91|12/24||
|92|12/25||
|93|12/26||
|94|12/27||
|95|12/28||
|96|12/29||
|97|12/30||
|98|12/31||
|99|1/1||
|100|1/2||
