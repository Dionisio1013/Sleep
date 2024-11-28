# Sleep - Applying Statistical Methods (Hypothesis Testing and ANOVA)

![Myair](https://github.com/user-attachments/assets/24c051dc-1863-460f-a1e6-878edacf8b12)

Sleep is essential for everyday life as it has a significant impact on both physical and mental health. 
According to the NHLBI, experts recommend that adults sleep between 7-9 hours per night. 
However, it can be difficult to consistently reach this benchmark, as many people struggle with stress, 
poor sleep habits, sleep disorders, or even lack of time.

During sleep, the body undergoes four stages:

Light Sleep (NREM)
Deeper Light Sleep (NREM)
Deep Sleep
REM Sleep (Rapid Eye Movement)
Below is what the body experiences during each stage: 


![Sleep Stages](https://github.com/user-attachments/assets/dceee533-6901-4957-9d8c-ea5a77efa81e)
Stage 1: Transition to sleep, muscle relaxation, and preparation for deeper rest.
Stage 2: Memory consolidation, body and energy conservation, and regulation of heart rate and temperature.
Stage 3: Physical restoration, muscle repair, immune system strengthening, and memory consolidation.
Stage 4: Mental restoration, emotional processing, creativity, learning, and memory consolidation.
Introduction

I suffer from sleep apnea, a sleep disorder that causes pauses in breathing or shallow breaths, which disrupts the stages of sleep. 
To manage this disorder, I have been using a CPAP machine for about a year, which helps open my airways. 
On the plus side, my CPAP machine is connected to an app called MyAir, which tracks my usage.

### i) Data Collection
MyAir allows users to download their personal data.
App -> API Call -> Sends to user email in CSV format


### ii) Descriptive Analytics
Data Shape: <525, 14>

Variables:
SORT_KEY	object
USAGE_HOURS	float64
SESSION_DATE	object
SLEEP_SCORE	int64
AHI_SCORE	int64
LEAK_SCORE	int64
MASK_SCORE	int64
USAGE_SCORE	int64
MASK_SESSION_COUNT	int64
AHI	float64
LEAK_50_PERCENTILE	float64
LEAK_70_PERCENTILE	float64
LEAK_95_PERCENTILE	float64
APPROXIMATECREATIONDATETIME	object

Target Variable:
USAGE_HOURS 

#### Null Values and 0 Data
My dataset doesn't necesairly have null values, but it has records with my sleep usage is 0.0
About 175 of my records are < 1. To prevent any skeness and drastic shifts in my mean I will remove the data
After creating a Histogram to gain greater sense, I've come across this uneven distribution


After dropping Nulls:
Bimodal Distribution:

(525, 15)

SORT_KEY	object
USAGE_HOURS	float64
SESSION_DATE	object
SLEEP_SCORE	int64
AHI_SCORE	int64
LEAK_SCORE	int64
MASK_SCORE	int64
USAGE_SCORE	int64
MASK_SESSION_COUNT	int64
AHI	float64
LEAK_50_PERCENTILE	float64
LEAK_70_PERCENTILE	float64
LEAK_95_PERCENTILE	float64
APPROXIMATECREATIONDATETIME	object


### iii) Descriptive Analytics


### iv) Hypothesis Testing 


### v) Conclusions and Key Findings




