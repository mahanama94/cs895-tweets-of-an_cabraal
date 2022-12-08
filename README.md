# Sri Lankan Economic Crisis and the ex-Governor of Central Bank

The Sri Lankan economic crisis in 2022 is regarded significant event in post-independent Sri Lanka.
Among many alleged factors leading to the economic crisis, [Ajith Nivard Cabraal](https://en.wikipedia.org/wiki/Ajith_Nivard_Cabraal) played 
a controversial role in setting economic policies as a member of parliament and the governor of [Central Bank of Sri Lanka](https://www.cbsl.gov.lk/) 
([@CBSL](https://twitter.com/CBSL)). 
Following anti-government protests, he resigned from his post as the governor of CBSL in April 2022.
In June 2022, [Transparency International Sri Lanka](https://www.tisrilanka.org/) 
([@tisrilanka](https://twitter.com/tisrilanka)) filed a fundamental rights petition in the Suprement Court of Sri Lanka holding him accountable for his actions. 

In October 2022, the Supreme Court ordered the Auditor General to conduct an audit and submit an audit report in respect of
1. Decision to peg USD/LKR
2. Delay in seeking Internationl Monetary Fund (IMF) assistance
3. Settlement of sovereign bonds in January 2022

In the forensic study, we use archived tweets of now inactive ex-governor ([@an_cabraal](https://twitter.com/an_cabraal)) and attempt to 
find supplementary evidences on actions of the governor and to construct the series of events. 

## Dataset 

The dataset comprise of ~1800 archived tweeets of @an_cabraal manually picked and manually assigned their relationship to the aspects of the court order. 

| File name           | Description                                             |
|---                  |---                                                      |
| `memento-sample.csv`| Sample of all mementos used in the study                |
| `q-1.csv`           | Manually selected mementos associated with USD/LKR peg  |
| `q-2.csv`           | Mementos associated with delaying IMF assistance        |
| `q-3.csv`           | Mementos mentioning sovereign bond settlements          |

Each `csv` file contains details of mementos in each sample.

|Column               | Description                           |
|---                  |---                                    |
| `memento-datetime`  | Datetime of the memento               |
| `tweet-url`         | URL of tweet (from memento url)       |
| `memento-url`       | URL of memento (archived tweet)       | 
| `tweet-content`     | Contents of the tweet (from memento)  |


-- Bhanuka Mahanama([@mahanama94](https://twitter.com/mahanama94))
