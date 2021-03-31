<div dir="rtl">
# موارد استفاده از علوم داده

## سابقه و زمینه ها
هر نوع تجزیه و تحلیل در ارتباط با اینکه: 
- چه مشکلی را برای چه کسی حل می کند؟
- امروز چه اتفاقی می افتد؟
- ورودی داده ها از کجاست و این داده ها از کجا می آید؟
- خروجی ها چیست و چگونه این خروجی ها مصرف می شود؟
- آیا این نشت درآمد مالی است یا مشکل رشد درآمد است؟

## Use Cases By Function

### مارکتینگ
- Predicting Lifetime Value (LTV)
  - what for: if you can predict the characteristics of high LTV customers, this supports customer segmentation, identifies upsell opportunties and supports other marketing initiatives
  - usage: can be both an online algorithm and a static report showing the characteristics of high LTV customers
- Wallet share estimation
  - working out the proportion of a customer's spend in a category accrues to a company allows that company to identify upsell and cross-sell opportunities
  - usage: can be both an online algorithm and a static report showing the characteristics of low wallet share customers
  - Churn
  - working out the characteristics of churners allows a company to product adjustments and an online algorithm allows them to reach out to churners
  - usage: can be both an online algorithm and a statistic report showing the characteristics of likely churners
  - Customer segmentation
  - If you can understand qualitatively different customer groups, then we can give them different treatments (perhaps even by different groups in the company). Answers questions like: what makes people buy, stop buying etc
  - usage: static report
  - Product mix
  - What mix of products offers the lowest churn? eg. Giving a combined policy discount for home + auto = low churn
  - کاربرد: الگوریتم آنلاین و گزارش استاتیک
  - فروش متقابل / الگوریتم های توصیه کننده
  - Given a customer's past browsing history, purchase history and other characteristics, what are they likely to want to purchase in the future?
  - کاربرد: الگوریتم آنلاین
  - فروش بیشتر
  - Given a customer's characteristics, what is the likelihood that they'll upgrade in the future?
  - usage: online algorithm and static report
  - بهینه سازی کانال
  - what is the optimal way to reach a customer with cetain characteristics?
  - usage: online algorithm and static report
Discount targeting - What is the probability of inducing the desired behavior with a discount - usage: online algorithm and static report
- Reactivation likelihood
  - What is the reactivation likelihood for a given customer
  - کاربرد: الگوریتم آنلاین و گزارش استاتیک
- بهینه سازی تبلیغات و خرید آگهی
  - calculating the right price for different keywords/ad slots

### فروش
- Lead prioritization
  - What is a given lead's likelihood of closing
  - تأثیر درآمد
  - کاربرد: الگوریتم آنلاین و گزارش استاتیک
- پیش بینی تقاضا

### لجستیک
- پیش بینی تقاضا
  - تعداد چیزهایی که نیاز دارید و در کجا موجود است را پیش بینی می کند؟
  - تأثیر درآمد: از رشد حمایت می کند و علیه نشت درآمد مبارزه می کند
  - کاربرد: الگوریتم آنلاین و گزارش استاتیک

### ریسک
- ریسک اعتباری
- ریسک مالی و خزانه داری
  - برای تأمین این نیازها به چه میزان سرمایه نیاز داریم؟
- تشخیص تقلب
  - پیش بینی کلاه برداری با کارت اعتباری
- بازیابی حساب های پرداختی
  - Predicting the probably a liability can be recovered given the characteristics of the borrower and the loan
- ضد پول شویی
  - Using machine learning and fuzzy matching to detect transactions that contradict AML legislation (such as the OFAC list)

### Customer support
- مراکز تماس
  - Call routing (ie determining wait times) based on caller id history, time of day, call volumes, products owned, churn risk, LTV, etc.
- Call center message optimization
  - Putting the right data on the operator's screen
- Call center volume forecasting
  - predicting call volume for the purposes of staff rostering


### منابع انسانی
- Resume screening
  - scores resumes based on the outcomes of past job interviews and hires
- Employee churn
  - predicts which employees are most likely to leave
- Training recommendation
  - recommends specific training based of performance review data
- Talent management
  - looking at objective measures of employee success

## Use Cases By Vertical

### Healthcare
- Claims review prioritization
  - payers picking which claims should be reviewed by manual auditors
- Medicare/medicaid fraud
  - Tackled at the claims processors, EDS is the biggest & uses proprietary tech
- تخصیص منابع پزشکی
  - مدیریت عملیات بیمارستان
  - Optimize/predict operating theatre & bed occupancy based on initial patient visits
- Alerting and diagnostics from real-time patient data
  - دستگاه های جاسازی شده یا امبدد دیوایس ها
  - Exogenous data from devices to create diagnostic reports for doctors
- انطباق با نسخه
  - Predicting who won't comply with their prescriptions
- Physician attrition
  - Hospitals want to retain Drs who have admitting privileges in multiple hospitals
- تجزیه و تحلیل بقا
  - Analyse survival statistics for different patient attributes (age, blood type, gender, etc) and treatments
- Medication (dosage) effectiveness
  - Analyse effects of admitting different types and dosage of medication for a disease
- خطر پذیرش مجدد
  - Predict risk of re-admittance based on patient attributes, medical history, diagnose & treatment

### مصرف کننده مالی
- تقلب در کارت اعتباری
  - بانک ها باید از این امر جلوگیری کنند و فروشندگان نیز باید از این امر جلوگیری کنند

### خرده فروشی
- قیمت گذاری
  - Optimize per time period, per item, per store
  - Was dominated by Retek, but got purchased by Oracle in 2005. Now Oracle Retail.
  - JDA is also a player (supply chain software)
- محل فروشگاه های جدید
- چیدمان محصول در فروشگاه ها
  - این "طرح و برنامه ریزی" نامیده می شود
- تجارت
  - when to start stocking & discontinuing product lines
- Inventory Management (how many units)
  - In particular, perishable goods
- Shrinkage analytics
  - Theft analytics/prevention (http://www.internetretailer.com/2004/12/17/retailers-cutting-inventory-shrink-with-spss-predictive-analytic)
- تجزیه و تحلیل گارانتی
  - Rates of failure for different components
    - And what are the drivers or parts?
  - What types of customers buying what types of products are likely to actually redeem a warranty?
- آنالیز سبد بازار
- تجزیه و تحلیل بهترین پیشنهاد بعدی
- الگوهای حمل و نقل فروشگاه

### بیمه
- پیش بینی ادعاها
  - Might have telemetry data
- Claims handling (accept/deny/audit), managing repairer network (auto body, doctors)
- حساسیت به قیمت
- سرمایه گذاری ها
- Agent & branch performance
- دیجیتال مارکتینگ

### ساخت و ساز
- Contractor performance
  - Identifying contractors who are regularly involved in poor performing products
- Design issue prediction
  - Predicting that a construction project is likely to have issues as early as possible

### علوم زیستی
- Identifying biomarkers for boxed warnings on marketed products
- کشف و تجزیه و تحلیل دارو / مواد شیمیایی
- Crunching study results
- Identifying negative responses (monitor social networks for early problems with drugs)
- تشخیص توسعه ی تست ها
  - دستگاه های سخت افزاری
  - نرم افزار
- هدف گذاری تشخیصی سیستم مدیریت ارتباط با مشتری
- Predicting drug demand in different geographies for different products
- Predicting prescription adherence with different approaches to reminding patients
- سیگنال های ایمنی
- بازاریابی شبکه های اجتماعی در مورد رقبا
- Image analysis or GCMS analysis in a high throughput manner
- Analysis of clinical outcomes to adapt clinical trial design
- بهینه سازی قیمت تمام شده کالاها
- Leveraging molecule database with metabolic stability data to elucidate new stable structures

### خدمات مهمان داری
- مدیریت موجودی کالا / قیمت گذاری پویا
- تبلیغات / ارتقا / پیشنهادات
- جدول مدیریت و رزرو
- مدیریت نیروی کار

### توزیع شبکه برق
- فرکانس AC را تا حد ممکن ثابت نگه می دارد
- به نظر می رسد یک الگوریتم واقعی "آنلاین" است

### ساخت
- داده های سنسور برای بررسی خرابی ها
- مدیریت کیفیت
  - شناسایی تولید خارج از محدوده
    - بازرسی بصری / بینایی کامپیوتر
  - سرعت اجرای بهینه
- پیش بینی تقاضا / مدیریت موجودی کالا
- ضمانت / قیمت گذاری

### مسافرت
- برنامه ریزی هواپیما
- Seat mgmt, gate mgmt
- برنامه ریزی خدمه هوایی
- قیمت گذاری پویا
- Customer complain resolution (give points in exchange)
- موارد مرکز تماس
- بهینه سازی نگهداری و تعمیر
- پیش بینی گردشگری

### کشاورزی
- مدیریت عملکرد

### اپراتورهای مرکز خرید
- Predicting tenants capacity to pay based on their sales figures, their industry
- Predicting the best tenant for an open vacancy to maximise over all sales at a mall

### آموزش
- امتیازدهی خودکار به مقالات

### خدمات رفاهی
- Optimise Distribution Network Cost Effectiveness (balance Capital 7 Operating Expenditure)
- Predict Commodity Requirements

### دیگر
- تحلیل احساسات
- برنامه های وفاداری
- داده های حسگرها و سنسورها
  - هشدار دادن
  - چه چیزی شکست خواهد خورد؟
- تکثیر
- تهیه و خرید تدارکات

## Use Cases That Need Fleshing Out

### تهیه و خرید تدارکات
- مذاکره و انتخاب فروشنده
  - آیا ما از بهترین تولید کننده خرید می کنیم؟

### بازاریابی
- بازاریابی مستقیم
  - نرخ پاسخ
  - تقسیم بندی برای نامه های پستی
  - احتمال فعال سازی مجدد
  - تحلیل ارزش مشتری
  - هدف گذاری تخفیف
  - صنعت خدمات مالی
  - بازاریابی تلفنی
    - Generally as a follow-up to a DM or a churn predictor
  - بازاریابی ایمیلی
- آفلاین
  - Call to action w/ unique promotion
  - Why are people responding- How do I adjust my buy (where, when, how)?
  - "I'm sure we are wasting half our money here, but the problem is we don't know which ad"
- Media Mix Optimization
  - Kantar Group and Nielson are dominant
  - Hard part of this is getting to the data (good samples & response vars)

### مراقبت های بهداشتی
- سیستم مدیریت مشتری و بهینه سازی مصرف
- Claims coding
- تعیین فرمول قیمت گذاری
- چگونه می توانم شما را مجبور کنم که از کارت من برای پرداخت خودکار استفاده کنید؟
- مالی
  - تحلیل ریسک
- گزارش های اتوماتیک مختصر

## منابع
- Kaggle
- http://web.archive.org/web/20130818062926/https://www.kaggle.com/wiki/DataScienceUseCases

## ترجمه ها
This is also available in other languages:
- [انگلیسی](https://github.com/amirshnll/Data-Science-Use-Cases/blob/main/README-EN.md)
- [فارسی](https://github.com/amirshnll/Data-Science-Use-Cases/blob/main/README.md)
</div>
