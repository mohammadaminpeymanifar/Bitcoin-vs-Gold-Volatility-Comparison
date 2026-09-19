=============================== Bitcoin vs Gold Volatility Comparison ================================
This project compares the volatility and risk characteristics of Bitcoin and Gold using quantitative finance and time-series analysis techniques.
The analysis focuses on understanding how these two assets differ in terms of risk, return behavior, volatility persistence, and downside risk.

## Objectives
* Compare Bitcoin and Gold historical price behavior
* Calculate and analyze log returns
* Perform stationarity testing using ADF
* Measure annualized volatility
* Analyze rolling volatility
* Examine correlation between assets
* Model conditional volatility using GARCH(1,1)
* Calculate Value at Risk (VaR)
* Calculate Expected Shortfall (ES)

## Dataset
Data Source: Yahoo Finance
Assets:
* Bitcoin (BTC-USD)
* Gold Futures (GC=F)
Period:
* January 2020 – September 2026
Frequency:
* Daily Prices


## Methodology

### Data Preparation
* Download historical daily prices
* Align common trading dates
* Calculate log returns

### Statistical Analysis
* Descriptive Statistics
* ADF Stationarity Test

### Volatility Analysis
* Annualized Volatility
* 30-Day Rolling Volatility
* Return Distribution Analysis

### Correlation Analysis
* Pearson Correlation Matrix

### GARCH Modeling
* GARCH(1,1)
* Conditional Volatility
* Volatility Persistence

### Risk Analysis
* Value at Risk (95%)
* Expected Shortfall (95%)


## Key Findings

### Annualized Volatility
| Asset   | Volatility |
| ------- | ---------- |
| Bitcoin | 60.87%     |
| Gold    | 19.18%     |
Bitcoin exhibited approximately 3.14 times higher volatility than Gold.

### Correlation
Bitcoin-Gold Correlation:
0.1180
This suggests a weak positive relationship between the two assets.

### Value at Risk (95%)
| Asset   | VaR    |
| ------- | ------ |
| Bitcoin | -5.47% |
| Gold    | -1.87% |

### Expected Shortfall (95%)
| Asset   | ES     |
| ------- | ------ |
| Bitcoin | -8.96% |
| Gold    | -2.92% |

### Volatility Persistence
| Asset   | Persistence |
| ------- | ----------- |
| Bitcoin | 0.9571      |
| Gold    | 0.9625      |
Both assets demonstrate strong volatility clustering behavior.



## Conclusion
The analysis shows that Bitcoin carries substantially higher risk than Gold across multiple risk measures.
While Bitcoin and Gold exhibit only weak correlation, Bitcoin experiences significantly larger volatility and downside risk.
The GARCH results indicate that volatility shocks persist over time for both assets, highlighting the importance of volatility modeling in financial risk management.



## Author
Financial Analytics Portfolio Project
Developed using Python for quantitative risk and volatility analysis.
=========================================================================================================
================================== مقایسه نوسان‌پذیری بیت‌کوین و طلا =====================================
این پروژه با هدف مقایسه ویژگی‌های ریسک و نوسان‌پذیری بیت‌کوین و طلا با استفاده از روش‌های تحلیل سری زمانی و مالی انجام شده است.
در این تحلیل تلاش شده است تفاوت این دو دارایی از نظر بازده، ریسک، نوسان‌پذیری، پایداری نوسان و ریسک نزولی بررسی شود.


## اهداف پروژه
* مقایسه رفتار تاریخی قیمت بیت‌کوین و طلا
* محاسبه و تحلیل بازده‌های لگاریتمی (Log Returns)
* بررسی ایستایی داده‌ها با آزمون ADF
* اندازه‌گیری نوسان‌پذیری سالانه
* تحلیل نوسان‌پذیری متحرک (Rolling Volatility)
* بررسی همبستگی بین دو دارایی
* مدل‌سازی نوسان شرطی با استفاده از GARCH(1,1)
* محاسبه Value at Risk (VaR)
* محاسبه Expected Shortfall (ES)


## داده‌های مورد استفاده
منبع داده:
Yahoo Finance
نمادها:
* Bitcoin (BTC-USD)
* Gold Futures (GC=F)
بازه زمانی:
* ژانویه 2020 تا سپتامبر 2026
تناوب داده:
* روزانه



## مراحل انجام تحلیل

### آماده‌سازی داده‌ها
* دریافت داده‌های تاریخی
* همگام‌سازی روزهای معاملاتی
* محاسبه بازده‌های لگاریتمی

### تحلیل آماری
* آمار توصیفی
* آزمون ADF

### تحلیل نوسان‌پذیری
* نوسان‌پذیری سالانه
* نوسان‌پذیری متحرک 30 روزه
* بررسی توزیع بازده‌ها

### تحلیل همبستگی
* ماتریس همبستگی پیرسون

### مدل‌سازی GARCH
* مدل GARCH(1,1)
* نوسان شرطی
* پایداری نوسان

### تحلیل ریسک
* Value at Risk (95%)
* Expected Shortfall (95%)



## مهم‌ترین نتایج
### نوسان‌پذیری سالانه
| دارایی   | نوسان‌پذیری |
| -------- | ----------- |
| بیت‌کوین | 60.87%      |
| طلا      | 19.18%      |

بیت‌کوین حدود 3.14 برابر نوسان بیشتری نسبت به طلا داشته است.


### همبستگی
همبستگی بازده بیت‌کوین و طلا:
0.1180
این مقدار نشان‌دهنده رابطه مثبت اما ضعیف بین این دو دارایی است.


### Value at Risk (95%)
| دارایی   | VaR    |
| -------- | ------ |
| بیت‌کوین | -5.47% |
| طلا      | -1.87% |


### Expected Shortfall (95%)
| دارایی   | ES     |
| -------- | ------ |
| بیت‌کوین | -8.96% |
| طلا      | -2.92% |


### پایداری نوسان (Volatility Persistence)
| دارایی   | Persistence |
| -------- | ----------- |
| بیت‌کوین | 0.9571      |
| طلا      | 0.9625      |
نتایج نشان می‌دهد که در هر دو بازار، شوک‌های نوسان برای مدت نسبتاً طولانی باقی می‌مانند و پدیده Volatility Clustering مشاهده می‌شود.



## جمع‌بندی
نتایج این پروژه نشان می‌دهد که بیت‌کوین در مقایسه با طلا دارای ریسک و نوسان‌پذیری بسیار بیشتری است.
در حالی که همبستگی بین این دو دارایی ضعیف است، بیت‌کوین در اکثر معیارهای ریسک از جمله نوسان‌پذیری، Value at Risk و Expected Shortfall مقادیر بزرگ‌تری را نشان می‌دهد.
همچنین مدل GARCH نشان داد که شوک‌های نوسان در هر دو دارایی ماندگار هستند و مدل‌سازی نوسان می‌تواند نقش مهمی در مدیریت ریسک مالی ایفا کند.



## توسعه‌دهنده
پروژه پورتفولیوی Financial Analytics
پیاده‌سازی شده با Python در حوزه تحلیل ریسک، نوسان‌پذیری و مالی کمی (Quantitative Finance).
