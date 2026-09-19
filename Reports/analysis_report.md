============================= Bitcoin vs Gold Volatility Comparison ================================
## Analysis Report
### Project Objective
The objective of this project is to compare Bitcoin and Gold from a risk and volatility perspective using quantitative finance techniques and time-series analysis.
The study evaluates return characteristics, volatility behavior, downside risk, and volatility persistence to better understand the differences between these two widely discussed assets.



## Dataset
Source: Yahoo Finance
Assets:
* Bitcoin (BTC-USD)
* Gold Futures (GC=F)
Period:
* January 2020 – September 2026
Frequency:
* Daily



## Methodology
The following analytical techniques were applied:
1. Log Return Calculation
2. Descriptive Statistics
3. Augmented Dickey-Fuller (ADF) Test
4. Annualized Volatility
5. Rolling Volatility Analysis
6. Correlation Analysis
7. GARCH(1,1) Modeling
8. Value at Risk (VaR)
9. Expected Shortfall (ES)



## Stationarity Analysis
ADF tests were performed on the return series of both assets.
Results indicate that Bitcoin returns and Gold returns are stationary, making them suitable for volatility modeling and risk analysis.



## Volatility Analysis
### Annualized Volatility
| Asset   | Annualized Volatility |
| ------- | --------------------- |
| Bitcoin | 60.87%                |
| Gold    | 19.18%                |
Bitcoin exhibited substantially higher volatility than Gold.
The volatility ratio indicates that Bitcoin was approximately 3.14 times more volatile than Gold during the analyzed period.
This result confirms that Bitcoin remains a significantly higher-risk asset compared to Gold.



## Correlation Analysis
The correlation between Bitcoin and Gold returns was:
0.1180
This weak positive correlation suggests that the two assets generally move independently from one another.
As a result, Gold and Bitcoin may provide diversification benefits when included together in a portfolio.



## GARCH Volatility Modeling
A GARCH(1,1) model was applied to estimate time-varying conditional volatility.

### Volatility Persistence
| Asset   | Persistence |
| ------- | ----------- |
| Bitcoin | 0.9571      |
| Gold    | 0.9625      |
Both assets exhibited high volatility persistence.
These values indicate that volatility shocks tend to remain in the market for extended periods rather than disappearing immediately.
The results also confirm the existence of volatility clustering in both markets.



## Value at Risk (95%)
| Asset   | VaR    |
| ------- | ------ |
| Bitcoin | -5.47% |
| Gold    | -1.87% |
The VaR results suggest that under normal market conditions there is a 5% probability that daily losses could exceed these levels.
Bitcoin demonstrated substantially larger downside risk compared to Gold.



## Expected Shortfall (95%)
| Asset   | Expected Shortfall |
| ------- | ------------------ |
| Bitcoin | -8.96%             |
| Gold    | -2.92%             |
Expected Shortfall measures the average loss when returns fall beyond the VaR threshold.
The results indicate that extreme losses are significantly larger for Bitcoin than for Gold.



## Key Findings
* Bitcoin returns are considerably more volatile than Gold returns.
* Bitcoin exhibited approximately 3.14 times higher annualized volatility.
* Correlation between Bitcoin and Gold was weak.
* Both assets displayed strong volatility persistence.
* Bitcoin showed significantly higher downside risk based on VaR and Expected Shortfall.
* Volatility clustering was evident in both markets.



## Conclusion
This analysis demonstrates that Bitcoin and Gold possess substantially different risk profiles.
While Gold continues to exhibit relatively stable behavior, Bitcoin remains a highly volatile asset with greater exposure to extreme price movements.
Although the weak correlation between the two assets may offer diversification opportunities, risk-sensitive investors should carefully consider the significantly higher volatility and downside risk associated with Bitcoin.
Overall, the findings highlight the importance of volatility modeling and risk measurement when evaluating modern financial assets.



============================  مقایسه نوسان‌پذیری بیت‌کوین و طلا ======================================
## گزارش تحلیل
### هدف پروژه
هدف این پروژه مقایسه بیت‌کوین و طلا از منظر ریسک و نوسان‌پذیری با استفاده از روش‌های مالی کمی و تحلیل سری‌های زمانی است.
در این مطالعه ویژگی‌های بازده، رفتار نوسان، ریسک نزولی و پایداری نوسان دو دارایی بررسی شده است تا تفاوت‌های آن‌ها از دیدگاه مدیریت ریسک بهتر درک شود.



## داده‌های مورد استفاده
منبع داده:
Yahoo Finance
دارایی‌ها:
* Bitcoin (BTC-USD)
* Gold Futures (GC=F)
بازه زمانی:
* ژانویه 2020 تا سپتامبر 2026
تناوب داده:
* روزانه



## روش تحلیل
در این پروژه از روش‌های زیر استفاده شده است:
1. محاسبه بازده لگاریتمی
2. آمار توصیفی
3. آزمون ADF
4. نوسان‌پذیری سالانه
5. نوسان‌پذیری متحرک
6. تحلیل همبستگی
7. مدل GARCH(1,1)
8. Value at Risk
9. Expected Shortfall



## تحلیل ایستایی
آزمون ADF بر روی بازده‌های بیت‌کوین و طلا انجام شد.
نتایج نشان داد که سری بازده هر دو دارایی ایستا هستند و برای مدل‌سازی نوسان و تحلیل ریسک مناسب‌اند.



## تحلیل نوسان‌پذیری
### نوسان‌پذیری سالانه
| دارایی   | نوسان‌پذیری |
| -------- | ----------- |
| بیت‌کوین | 60.87%      |
| طلا      | 19.18%      |
نتایج نشان می‌دهد که بیت‌کوین نوسان بسیار بیشتری نسبت به طلا داشته است.
نسبت نوسان‌پذیری نشان می‌دهد که بیت‌کوین در دوره مورد بررسی حدود 3.14 برابر پرنوسان‌تر از طلا بوده است.



## تحلیل همبستگی
همبستگی بازده بیت‌کوین و طلا برابر بود با:
0.1180
این مقدار بیانگر رابطه مثبت اما ضعیف بین دو دارایی است.
در نتیجه می‌توان انتظار داشت که ترکیب این دو دارایی تا حدی مزایای تنوع‌بخشی ایجاد کند.



## مدل‌سازی GARCH
برای برآورد نوسان شرطی از مدل GARCH(1,1) استفاده شد.

### پایداری نوسان
| دارایی   | Persistence |
| -------- | ----------- |
| بیت‌کوین | 0.9571      |
| طلا      | 0.9625      |
مقادیر بالا نشان می‌دهد شوک‌های نوسان در هر دو بازار ماندگار هستند و اثر آن‌ها به سرعت از بین نمی‌رود.
این موضوع وجود پدیده Volatility Clustering را نیز تأیید می‌کند.



## Value at Risk (95%)
| دارایی   | VaR    |
| -------- | ------ |
| بیت‌کوین | -5.47% |
| طلا      | -1.87% |
این نتایج نشان می‌دهد که در شرایط عادی بازار، احتمال 5 درصدی وجود دارد که زیان روزانه از این مقادیر بیشتر شود.



## Expected Shortfall (95%)
| دارایی   | Expected Shortfall |
| -------- | ------------------ |
| بیت‌کوین | -8.96%             |
| طلا      | -2.92%             |
این معیار میانگین زیان در بدترین سناریوهای بازار را اندازه‌گیری می‌کند.
نتایج نشان می‌دهد زیان‌های شدید در بیت‌کوین به مراتب بزرگ‌تر از طلا هستند.



## مهم‌ترین یافته‌ها
* بیت‌کوین نوسان بسیار بیشتری نسبت به طلا دارد.
* نوسان سالانه بیت‌کوین حدود 3.14 برابر طلا بوده است.
* همبستگی بین دو دارایی ضعیف است.
* هر دو بازار دارای پایداری بالای نوسان هستند.
* ریسک نزولی بیت‌کوین به طور قابل توجهی بیشتر از طلاست.
* پدیده Volatility Clustering در هر دو دارایی مشاهده شد.



## جمع‌بندی
نتایج این پروژه نشان می‌دهد که بیت‌کوین و طلا دارای پروفایل‌های ریسک متفاوتی هستند.
در حالی که طلا رفتار باثبات‌تری از خود نشان می‌دهد، بیت‌کوین همچنان دارایی بسیار پرنوسان‌تری است و در معرض حرکات شدید قیمتی قرار دارد.
همچنین اگرچه همبستگی پایین میان این دو دارایی می‌تواند مزایای تنوع‌بخشی ایجاد کند، اما سرمایه‌گذاران باید ریسک و نوسان بالاتر بیت‌کوین را در تصمیم‌گیری‌های خود مدنظر قرار دهند.
این نتایج اهمیت استفاده از مدل‌های نوسان و معیارهای مدیریت ریسک را در تحلیل دارایی‌های مالی نشان می‌دهد.
