---
layout: default
title: Chapter 4 - Results 
parent: § Impact of Information Breaches on Health Care Records
grand_parent: Breaches
nav_order: 40 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

  -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}

.youtube-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
}
.youtube-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>

<div class="dont-break-out" markdown="1">

1. TOC
{:toc}

## Chapter 4: Results

The purpose of this quantitative study was to determine if there is a significant difference between digital and nondigital breaches of individual patient records for each of the three types of U.S. health care entities. The examination of digital and nondigital breaches amongst the three health care entities is essential to both reduce the number of data breaches and ensure proper allocation of resources to achieve that end. The independent variables were the types of information security breaches and health care entities, while the dependent variable was the number of breached individual patient records. To examine the difference between variables, I used statistical analysis of group means to estimate the differences in individual patient records affected between digital and nondigital breaches of health data in the three types of health care entities.

I developed the following research questions and corresponding hypotheses to aid in the examination of the impact of digital and nondigital security breaches on individual patient records nondigitalfor each of the three types of U.S. health care entities:

- RQ1: Is there a significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health care providers?

    - H<sub>0</sub>1: There is no significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health care providers. 

    - H<sub>a</sub>1: There is a significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health care providers. 

- RQ2: Is there a significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health plan providers? 

    - H<sub>0</sub>2: There is no significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health plan providers. 

    - H<sub>a</sub>2: There is a significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health plan providers. 

- RQ3: Is there a significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health care clearinghouses? 

    - H<sub>0</sub>3: There is no significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health care clearinghouses. 

    - H<sub>a</sub>3: There is a significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health care clearinghouses.

This chapter contains a restatement of the data collection procedures. In this chapter, I describe the samples and the results of the statistical tests conducted in this study. This chapter also includes the results of the hypothesis testing to address the research questions posed in the study. This chapter ends with a summary of the key results of the study.

### Data Collection
I collected data for this study from the historical data available in the public database of HIPAA breach and violations (breach portal) maintained by the HHS. HHS’s breach portal is a publicly available database that can be accessed and downloaded online. No permission was necessary to access the data because it is freely available to anyone who wants to use it. HHS investigates the reports submitted by individual entities and posts the results of their findings in the data breach portal. The portal includes the following information: name of the breached entity, state the entity resides in, entity type, individuals affected, breach submission date, type of breach, location of breached information, if a business associate is present, and a text description of the incident. For this study, I obtained data from the HHS breach portal in the form of a Microsoft Excel document and truncated the unnecessary data (i.e., name of the entity, date of the breach, state the entity resides in, and if a business associate is present).

This study included reports beginning in 2010 to the most recent report available in the archival section of the breach portal, a total of 2,601 reports. The data did not include newer data because the breaches are still under investigation and the reports are thus subject to change. The data did not include data older than 2010 because that data may not be relevant to the modern day due to improvements in technology and data security. I used 100% of the total population within the stated timeframes.

I imported the data from the database to Microsoft Excel and recoded it into three separate sheets for health care providers, health plan providers, and health care clearing houses. I imported the resulting data into SPSS Version 25.0 and recoded them to numerically represent categorical variables. The type of breach was recoded as 2 for nondigital and 1 for digital breach. The individuals affected variable was considered a continuous variable.

### Study Results
I gathered a total of 2,601 cases from 2010 to 2020 in database and included them in the study. The covered entity types have three categories: health care providers, health plan providers, and health care clearinghouses. The majority of the cases (*n* = 1,876, 72.13%) come under health care providers, followed by healthcare clearinghouses (*n* = 376, 14.45%). Finally, there are 349 cases (13.42%) covered by health plan providers.

Data on the types of the breach were also collected. The types of breach categories include nondigital and digital breaches. Digital breaches include hacking/IT incidents, while nondigital breaches include loss, theft, and improper disposal. Unauthorized disclosure breaches get reviewed manually to determine if the breach is digital or nondigital. Unauthorized disclosures on paper/film locations were considered as nondigital, while unauthorized disclosures on email, electronic medical records, network servers, and desktop computers were considered as digital breaches.

The results of frequencies and percentages showed that 69.59% of the cases were digital (*n* = 1,810) while 39.1% of the cases were nondigital (*n* = 791).

I performed the descriptive statistics of individuals affected by the breach. Because the individuals affected variable was continuous in nature, I used measures of central tendencies, such as the mean, standard deviation, and range values, to present the data. The minimum number of affected was 500 individuals, while the maximum number of affected was 78,800,000 individuals. The mean number of affected is 74,323 individuals (*SD* = 1,593,587).

For the first research question, I performed two samples *t*-test (i.e., individual samples *t*-test) analyses. The first set of hypotheses considered the type of breach as the independent variable, while the individuals affected in the health care providers was the dependent variable. The type of breach was recoded into dummy variables for digital and nondigital.

Levene’s test results for equality of variances has a significance of 0.002, based on which the hypothesis of equal variances was rejected in favor of the alternative hypothesis of unequal variances.

Table 1 shows the descriptive statistics of the original number of individuals affected in the health care provider entity. The results showed that the number of individuals affected is higher for digital types of the breach (*M* = 27,893.63, **SD** = 208,563.29) as compared to nondigital types of the breach (*M* = 8,917.79, *SD* = 57,863.41).

**Table 1**
*Descriptive Statistics of the Raw Number of Individuals Affected Based on the Type of Breach*

Based on this, I conducted an independent samples t test by considering the equal variances are not assumed. The results in Table 2 show that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 3.073, p = .002). Therefore, there is sufficient evidence to reject the null hypothesis, which stated that there is no significant difference between the average number of individual patient records affected by digital breaches and nondigital breaches for health care providers.

**Table 2**
*Independent Samples t-Test Results of the Number of Individuals Affected Based on the Type of Breach for Raw Data*

A histogram of the data helped to identify the skewness of the data. As shown in Figure 1, it is evident that the data are very highly skewed.

**Figure 1**
*Histogram of Raw Data of Health Care Providers*

![Histogram of Raw Data of Health Care Providers](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-1.png)

Because the raw data are highly skewed with a very long tail, I decided to trim the upper tail by removing the top 10% of the individual values. The results of the Levene’s test for the equality of the variances of the raw data. The level of significance of Levene’s test is 0.000, based on which the hypothesis of equal variances was rejected. Table 3 shows the descriptive statistics of the original number of individuals affected in the health care provider entity. The results showed that the number of individuals affected is higher for digital types of the breach (*M* = 4,094.74, *SD* = 4,590.11) as compared to nondigital types of the breach (*M* = 2,435.91, *SD* = 3,053.12).

**Table 3**
*Descriptive Statistics of the 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*

Based on the results, as shown in Table 4, I conducted an independent samples t test by considering that equal variances are not assumed. The result showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 8.568, p = .000). This also shows that there is sufficient evidence to reject the null hypothesis, which stated that there is no significant difference between the average number of individual patient records affected for digital breach and nondigital breach for health care providers. In Table 9, the 90% confidence interval for digital and nondigital are shown.

**Table 4**
*Independent Samples t-Test Results of the Number of Individuals Affected Based on the Type of Breach for 10% Trimmed Raw Data with 90% Confidence Interval*

While comparing this value with the raw data, the value of the 10% trimmed value is less skewed. I analyazed a histogram of the data to see the skewness of the data. As shown in Figure 2, the skewness is much smaller with the top 10% excluded in comparison to the original raw data.

**Figure 2**
*Histogram When Top 10% of the Values are Excluded*

![Histogram When Top 10% of the Values are Excluded](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-2.png)

In order to improve this further, the loge of raw data excluding the top 10% of the values is considered. Since the trimmed data are still highly skewed, I decided to consider loge transformation. 

As shown in Table 5, the loge of the raw data excluding top 10% was analyzed for the equality of the variances. Levene’s test for equality of variances had a significance of 0.002, based on which the null hypothesis of equal variances was rejected.

**Table 5**
*Independent Samples t-Test Results of the Number of Individuals Affected Based on the Type of Breach for Loge of 10% Trimmed Raw Data With 90% Confidence Interval*

Based on this, as shown in Table 6, the independent samples t-test was conducted by considering the equal variances are not assumed. The result showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 8.204, p = .000). This shows that there is sufficient evidence to reject the null hypothesis, which stated that there is no significant difference between the average number of individual patient records affected for digital breach and nondigital breach for healthcare providers.

**Table 6**
*Descriptive Statistics of the Loge of 10% trimmed Raw Number of Individuals Affected Based on the Type of Breach*

Table 6 shows the descriptive statistics of the original number of individuals affected in the healthcare provider entity. The results showed that for the loge scale, the number of individuals affected is higher for digital types of the breach (*M* = 7.7622, *SD* = 1.05) as compared to nondigital types of the breach (*M* = 7.3491, *SD* = 0.87). To bring this back to the original scale, the exponential of the mean values of digital and nondigital breaches in the healthcare entity was obtained and the results are displayed in Table 13. The results of the original highly skewed raw data for digital types of the breach (90% lower CI = 18712, 90% upper CI = 37075) as compared to nondigital types of the breach (90% lower CI = 4556, 90% upper CI = 13280). Whereas after the exponential of the loge of the 10% trimmed data for digital types of the breach (90% lower CI = 2237, 90% upper CI = 2469) as compared to nondigital types of the breach (90% lower CI = 1454, 90% upper CI = 1663).

**Table 7**
*Descriptive Statistics of the Exponential of Loge of 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*

In Table 7, the 90% confidence interval for digital and nondigital are shown. shown in Figure 3, there is skewness in the histogram with the loge of the top 10% excluded data. However, the skewness is lower on loge scale than the original scale.

**Figure 3**
*Histogram of Loge of Top 10% Excluded Data*

![Histogram of Loge of Top 10% Excluded Data](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-3.png)

The last set of confidence intervals shown in Table 13 are the shortest confidence intervals, as they are based on the loge transformation which yields the best histograms shown in Figure 3. This graph still shows some skewness in the two histograms, but it is much smaller than those based on the raw data. In addition, the normal probability curve shows the typical patten for both the breaches. For the digital breaches, the average frequency is around 50, whereas the average frequency is at 25 for the nondigital breaches as shown in Figure 3.

In Table 8, the summary is shown with the difference based on the raw data, top 10% trimmed data, and the transformed data. These values come from the Tables 1, 3, and 6. It is evident that the trimming of the top 10% data and the transformation helped to make the data less skewed, as shown in Figure 3.

**Table 8**
*Summary Table for Healthcare Providers*

As shown in Table 8, the width of the 90% confidence interval has narrowed considerably by transforming the data. As the significance of the tests shown in Tables 1, 3, and 6 is 0.000, we can reject the null hypothesis that there is no significant difference between the average number of individual patient records affected for digital breaches and nondigital breaches for healthcare providers.

For the second research question, two samples t-test (individual samples t-test) analyses were performed. The second set of hypotheses considered the type of breach as the independent variable while the individuals affected in the health plan providers as the dependent variable. The type of breach was recoded into dummy variables for digital and nondigital.

The results of Levene’s test for equality of variances has a significance of 0.016, based on which the hypothesis of equal variances was rejected in favor of the alternative hypothesis of unequal variances.

Table 9 shows the descriptive statistics of the original number of individuals affected in the healthcare provider entity. The results showed that the number of individuals affected is higher for digital types of the breach (*M* = 616,066.07, *SD* = 6032878.13) as compared to nondigital types of the breach (*M* = 24,935.24, *SD* = 132296.62).

**Table 9**
*Descriptive Statistics of the Raw Number of Individuals Affected Based on the Type of Breach*

Based on this, an independent samples t-test was conducted by considering the equal variances are not assumed. The results in Table 10 showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 1.30, p = .195). Therefore, there is no sufficient evidence to reject the null hypothesis, which stated that there is significant difference between the average number of individual patient records affected for digital breach and nondigital breach for health plan providers.

**Table 10**
*Independent Samples t-Test Result for the Number of Individuals Affected Based on the Type of Breach for Raw Data*

The histogram of the data helped to identify the skewness of the data. As shown in Figure 4, it is evident that the data are very highly skewed.

**Figure 4**
*Histogram of Raw Data Health Plan Providers*

![Histogram of Raw Data Health Plan Providers](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-4.png)

Because the data are highly skewed with a very long tail, I decided to trim the upper tail by removing the top 10% of the individual values. The results of the Levene’s test for the equality of the variances of the raw data. The signidviance of Levene’s test is 0.000, based on which the hypothesis of equal variances was rejected.

Table 11 shows the descriptive statistics of the original number of individuals affected in the health plan provider entity. The results showed that the number of individuals affected is higher for digital types of the breach (M = 6458.78, SD = 8766.68) as compared to nondigital types of the breach (M = 4001.19, SD = 5386.52).

**Table 11**
*Descriptive Statistics of the 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*

Based on this, as shown in Table 12, the independent samples t-test was conducted by considering that equal variances are not assumed. The result showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 2.968, p = .003). This shows that there is sufficient evidence to reject the null hypothesis, which stated that there is no significant difference between the average number of individual patient records affected for digital breach and nondigital breach for health plan providers. In Table 9, the 90% confidence interval for digital and nondigital are shown.

**Table 12**
*Independent Samples t-Test Result for the Number of Individuals Affected Based on the Type of Breach for 10% Trimmed Raw Data With 90% Confidence Interval*

While comparing this value with the raw data, the value of the 10% trimmed value is less skewed. The histogram of the data was analyzed to see the skewness of the data. As shown in Figure 5, the skewness is much better with the top 10% excluded in comparison to the original raw data.

**Figure 5**
*Histogram of Top 10% Excluded Data*

![Histogram of Top 10% Excluded Data](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-5.png)

In order to improve this further, the loge of raw data excluding the top 10% of the values is considered. Since the trimmed data are still highly skewed, I decided to consider loge transformation. 

As shown in Table 13, the loge of the raw data excluding top 10% was analyzed for the equality of the variances. Levene’s test for equality of variances had a significance of 0.003, based on which the null hypothesis of equal variances was rejected.

**Table 13**
Independent Samples t-Test Result for the Number of Individuals Affected Based on the Type of Breach for Loge of 10% Trimmed Raw Data With 90% Confidence Interval

Based on this, as shown in Table 14, the independent samples t-test was conducted by considering the equal variances are not assumed. The result showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 2.979, p = 0.000). This shows that there is sufficient evidence to reject the null hypothesis, which stated that there is no significant difference between the average number of individual patient records affected for digital breach and nondigital breach for healthcare providers.

**Table 14**
*Descriptive Statistics of the Loge of 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*

Table 14 shows the descriptive statistics of the original number of individuals affected in the healthcare provider entity. The results showed that for the loge scale the number of individuals affected is higher for digital types of the breach (*M* = 8.0242, *SD* = 1.215) as compared to nondigital types of the breach (*M* = 7.6336, *SD* = 1.105). To bring this back to the original scale, the exponential of the mean values of digital and nondigital breaches in the health plan provider entity was obtained and the results are displayed in Table 24. The results of the original highly skewed raw data for digital types of the breach (90% lower CI = -1135904, 90% upper CI = 1368036) as compared to nondigital types of the breach (90% lower CI = 8,252, 90% upper CI = 41,518). Whereas after the exponential of the loge of the 10% trimmed data for digital types of the breach (90% lower CI = 2592, 90% upper CI = 3605) as compared to nondigital types of the breach (90% lower CI = 1790, 90% upper CI = 2392).

**Table 15**
*Descriptive Statistics of the Exponential of Loge of 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*

In Table 15, the 90% confidence interval for digital and nondigital are shown. As shown in Figure 6, there is skewness in the histogram with the loge of the top 10% excluded data. However, the skewness is lower on loge scale than the original scale.

**Figure 6**
*Histogram of Loge of Top 10% Excluded Data*

![Histogram of Loge of Top 10% Excluded Data](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-6.png)

The last set of confidence intervals shown in Table 15 are the shortest confidence intervals, as they are based on the loge transformation which yields the best histograms shown in Figure 6. This graph still shows some skewness in the two histograms, but it is much smaller than those based on the raw data. In addition, the normal probability curve shows the typical pattern for both the breaches. For the digital breaches, the average frequency is around 10, whereas the average frequency is at 12 for the nondigital breaches as shown in Figure 6.

In Table 16, the summary is shown with the difference based on the raw data, top 10% trimmed data, and the transformed data. These values come from the Tables 9, 11, and 14. It is evident that the trimming of the top 10% data and the transformation helped to make the data less skewed, as shown in Figure 6.

**Table 16**
*Summary Table for Health Plan Providers*

As shown in Table 16, the width of the 90% confidence interval has narrowed considerably by transforming the data. As the significance of the tests shown in Tables 9, 11, and 14 is 0.003, I reject the null hypothesis that there is no significant difference between the average number of individual patient records affected for digital breaches and nondigital breaches for health plan providers.

For the third research question, two samples t-test (individual samples t-test) analyses were performed. The first set of hypotheses considered the type of breach as the independent variable while the individuals affected in the healthcare clearinghouses as the dependent variable. The type of breach was recoded into dummy variables for digital and nondigital.

Levene’s test results for equality of variances has a significance of 0.05, based on which the hypothesis of equal variances was considered in favor of the alternative hypothesis of equal variances.

Table 17 shows the descriptive statistics of the original number of individuals affected in the healthcare provider entity. The results showed that the number of individuals affected is higher for digital types of the breach (*M* = 27893.63, *SD* = 208563.29) as compared to nondigital types of the breach (*M* = 8917.79, *SD* = 57863.41).

**Table 17**
*Descriptive Statistics of the Raw Number of Individuals Affected Based on the Type of Breach*

Based on this, an independent samples t-test was conducted by considering the equal variances are not assumed. The results in Table 28 showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 1.154, p = .249). Therefore, there is no sufficient evidence to reject the null hypothesis, which stated that there is significant difference between the average number of individual patient records affected for digital breach and nondigital breach for healthcare clearinghouses.

**Table 18**
*Independent Samples t-Test Result for the Number of Individuals Affected Based on the Type of Breach for Raw Data*

The histogram of the data helped to identify the skewness of the data. As shown in Figure 7, it is evident that the data are very highly skewed.

**Figure 7**
*Histogram of Raw Data of Health Care Clearing Houses*

![Histogram of Raw Data of Health Care Clearing Houses](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-7.png)

Because the raw data are highly skewed with a very long tail, I decided to trim the upper tail by removing the top 10% of the individual values. Table 29 shows the results of the Levene’s test for the equality of the variances of the raw data. The significance of Levene’s test is 0.000, based on which the hypothesis of equal variances was rejected.

Table 19 shows the descriptive statistics of the original number of individuals affected in the healthcare provider entity. The results showed that the number of individuals affected is higher for digital types of the breach (*M* = 6,986.52, *SD* = 9,023.08) as compared to nondigital types of the breach (*M* = 4,592.81, *SD* = 5,935.37).

**Table 19**
*Descriptive Statistics of the 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*

Based on this, as shown in Table 20, the independent samples t-test was conducted by considering that equal variances are not assumed. The result showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 2.941, p = .003). This also shows that there is sufficient evidence to reject the null hypothesis, which stated that there is no significant difference between the average number of individual patient records affected for digital breach and nondigital breach for healthcare clearinghouses. In Table 29, the 90% confidence interval for digital and nondigital are shown.

**Table 20** 
*Independent Samples t-Test Result for the Number of Individuals Affected Based on the Type of Breach for 10% Trimmed Raw Data With 90% Confidence Interval*

While comparing this value with the raw data, the value of the 10% trimmed value is less skewed. The histogram of the data was analyzed to see the skewness of the data. As shown in Figure 8, the skewness is much better with the top 10% excluded in comparison to the original raw data.

**Figure 8**
*Histogram of Top 10% Excluded Data*

![Histogram of Top 10% Excluded Data](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-8.png)

In order to improve this further, the loge of raw data excluding the top 10% of the values is considered. Since the trimmed data are still highly skewed, I decided to consider loge transformation. 

As shown in Table 21, the loge of the raw data excluding top 10% was analyzed for the equaity of the variances. Levene’s test for equality of variances had a significance of 0.007, based on which the null hypothesis of equal variances was rejected.

**Table 21**
*Independent Samples t-Test Result for the Number of Individuals Affected Based on the Type of Breach for Loge of 10% Trimmed Raw Data With 90% Confidence Interval*

Based on this, as shown in Table 22, the independent samples t-test was conducted by considering the equal variances are not assumed. The result showed that there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (t = 2.726, p = .007). This shows that there is sufficient evidence to reject the null hypothesis, which stated that there is no significant difference between the average number of individual patient records affected for digital breach and nondigital breach for healthcare providers.

**Table 22**
*Descriptive Statistics of the Loge of 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*

Table 22 shows the descriptive statistics of the original number of individuals affected in the healthcare provider entity. The results showed that for the loge scale the number of individuals affected is higher for digital types of the breach (*M* = 8.1367, *SD* = 1.21) as compared to nondigital types of the breach (*M* = 7.7843, *SD* = 1.12). To bring this back to the original scale, the exponential of the mean values of digital and nondigital breaches in the healthcare entity was obtained and the results are displayed in Table 35. The results of the original highly skewed raw data for digital types of the breach (90% lower CI = 58972, 90% upper CI = 185438) as compared to nondigital types of the breach (90% lower CI = -968, 90% upper CI = 122190). Whereas after the exponential of the loge of the 10% trimmed data for digital types of the breach (90% lower CI = 2981, 90% upper CI = 3944) as compared to nondigital types of the breach (90% lower CI = 2039, 90% upper CI = 2836).

**Table 23**
*Descriptive Statistics of the Exponential of Loge of 10% Trimmed Raw Number of Individuals Affected Based on the Type of Breach*


In Table 23, the 90% confidence interval for digital and nondigital are shown.. As shown in Figure 9, there is skewness in the histogram with the loge of the top 10% excluded data. However, the skewness is lower on loge scale than the original scale.

**Figure 9**
*Histogram of Loge of Top 10% Excluded Data*

![Histogram of Loge of Top 10% Excluded Data](https://statics.bsafes.com/images/papers/impact-of-information-breaches-on-health-care-records-fig-9.png)

The last set of confidence intervals shown in Table 23 are the shortest confidence intervals, as they are based on the loge transformation, which yields the best histograms shown in Figure 9. This graph still shows some skewness in the two histograms, but it is much smaller than those based on the raw data. In addition, the normal probability curve shows the typical pattern for both breaches. For the digital breaches, the average frequency is around 12, whereas the average frequency is at 8 for the nondigital breaches as shown in Figure 9.

In Table 24, the summary is shown with the difference based on the raw data, top 10% trimmed data, and the transformed data. These values come from the Tables 17, 19, and 22. It is evident that the trimming of the top 10% data and the transformation helped to make the data less skewed, as shown in Figure 3.

**Table 24**
*Summary Table for Healthcare Clearinghouses*

As shown in Table 36, the width of the 90% confidence interval has narrowed considerably by transforming the data. As the significance of the tests shown in Table 22 is 0.007, I reject the null hypothesis that there is no significant difference between the average number of individual patient records affected for digital breaches and nondigital breaches for healthcare clearinghouses.

### Summary
The purpose of this quantitative study was to determine if there was a significant statistical difference between digital and nondigital breaches of individual patient records for each of the three types of healthcare entities in the United States. The examination of digital and nondigital breaches amongst the three healthcare entities is essential to both reducing the number of data breaches and ensuring proper allocation of resources to achieve that end. This study included reports beginning in 2010 to the most recent report available in the archival section of the breach portal, which was a total of 2,601 reports.

Most of the cases (*n* = 1876, 72.13%) were covered with healthcare providers, followed by healthcare clearinghouses (*n* = 376, 14.45%), and 349 cases (13.42%) were covered by health plan providers. When it comes to the healthcare providers, there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (*t* = 8.204, p = .000). For the health plan providers, there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (*t* = 2.979, *p* = .003). For the healthcare clearinghouses, there is a significant difference between the average number of individuals affected in digital and nondigital types of breaches (*t* = 2.726, *p* = .007).

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/breaches/impact-of-information-breaches-on-health-care-records-1/">Chapter 1 - Introduction to the Study</a></li><li> <a href="/docs/breaches/impact-of-information-breaches-on-health-care-records-2/">Chapter 2 - Literature Review</a></li><li> <a href="/docs/breaches/impact-of-information-breaches-on-health-care-records-3/">Chapter 3 - Research Method</a></li><li> <a href="/docs/breaches/impact-of-information-breaches-on-health-care-records-4/">Chapter 4 - Results</a></li><li> <a href="/docs/breaches/impact-of-information-breaches-on-health-care-records-5/">Chapter 5 - Discussion, Conclusions, and Recommendations</a></li><li> <a href="/docs/breaches/impact-of-information-breaches-on-health-care-records-6/">References</a></li></ul>

***

</div>
