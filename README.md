# programming-homework-3-financial-ratio-quantile-strategies-solved
**TO GET THIS SOLUTION VISIT:** [Programming Homework 3-Financial Ratio Quantile Strategies Solved](https://www.ankitcodinghub.com/product/programming-homework-3-financial-ratio-quantile-strategies-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97958&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming Homework 3-Financial Ratio Quantile Strategies Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
HW: Financial Ratio Quantile Strategies

1 Introduction

Here you will consider a few financial accounting ratios, as an approxima- tion of “quantamental” models that typically take much more numerous and carefully defined financial accounting into consideration. You will then in- vestigate profit opportunity of a quantile-based long-short scheme.

2 Understand Your Data

Read all documentation webpages for Zacks Fundamentals B. You will see they supply 6 related tables, FC, FR, MT, MKTV, SHRC and HDM 1. The strategy coding for this assignment will be reasonably easy. The data assembly, deliberately, is the difficult part.

3 Define the Universe

Choose at least 200 tickers2 of US equities such that3 they satisfy the follow- ing:

• end-of-day adjusted closing prices are available , over the entire period Jan 2014 through Jan 2021

1It is easiest to download your data through full-table downloads. Use URLs such as https://www.quandl.com/api/v3/datatables/ZACKS/MT?qopts.export=true

2You can find the full list of available tickers online

3We will not concern ourselves with selection bias in this exercise.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
4

</div>
</div>
<div class="layoutArea">
<div class="column">
• • •

</div>
<div class="column">
debt/market cap ratio is greater4 than 0.1 somewhere in the period Jan 2014 through Jan 2021 (preferably more than fleetingly)

not in the automotive, financial or insurance sector , over the entire period Jan 2014 through Jan 20215

has feasible calculation of the ratios specified below , over the en- tire period Jan 2014 through Jan 2021, including for at least one PER END DATE no more than one year old. Debt ratio of zero is OK.

Select Financial Ratios

</div>
</div>
<div class="layoutArea">
<div class="column">
For this assignment, we will work with the following ratios: • debt to market cap6.

• return on investment7

• price to earnings8

Note that these data items are reported (at best) quarterly. Use annual numbers only when quarterly ones do not exist. As the equity price changes day-to-day, each ratio changes accordingly9, so ultimately the time series you have will be on daily data10. Recall that we did not know any of these numbers until the FC/FILING DATE .

4This is about 1000-2000 companies, including ASH, VTOL, ISUN and VIVO.

5See the Quandl ZFB fields ZACKS SECTOR CODE, ZACKS X IND CODE, and the classifi- cation list

6 FR/TOT DEBT TOT EQUITY in Quandl. In this homework we pretend that it is OK to

treat market capitalization and book equity as equivalent, though they are not the same

thing.

7

8 Compute this based on FC/EPS DILUTED NET, BASIC NET EPS, SHRS/SHARES OUT, MKTV/MKT VAL, use the basic version (GAAP) if no diluted number is available. Treat negative earnings per share as 0.001.

9In many cases PER END DATE is not a trading day, so go ahead and forward fill equity price from the previous trading day.

10If you have memory errors when joining data, you are probably mistakenly creating a combinatorial explosion in your merging code.

2

</div>
</div>
<div class="layoutArea">
<div class="column">
Based on FR/RET INVST, MKTV/MKT VAL, FC/NET LTERM DEBT, FC/TOT LTERM DEBT. Investment is defined here as market cap plus long term debt. Use net debt where available, total debt otherwise. Quandl will report debt as NaN if it was 0.0, but be careful about net versus tot debt.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
As an example, consider V , return on investment. Say that our entity had successive report dates of March 31 and June 30, V 3−31 and V 6−30 and those numbers were known on filing dates April 4 and July 7. Our equity price series, which we take (also a bit problematically) as adjusted close prices, will be Pt. We have a debt number D for each report date as well.

We can infer the “return” R for a given report date as the unknown

</div>
</div>
<div class="layoutArea">
<div class="column">
element in

</div>
<div class="column">
V=R D+M

</div>
</div>
<div class="layoutArea">
<div class="column">
and we assume it doesn’t change day-to-day. Rather only the market value element M changes daily, and we estimate the corresponding V ̃ values ac- cording to the filing dates. So for example our inferred values look like

V ̃7-6 = R3-31 D3-31 +M7-6

but the next day is the filing date so we have V ̃7-7 = R6-30

</div>
</div>
<div class="layoutArea">
<div class="column">
where

and

5 Analysis

</div>
<div class="column">
D6-30 +M7-7 M7-6 = M3-31 P7-6

</div>
</div>
<div class="layoutArea">
<div class="column">
M

</div>
<div class="column">
7-7

</div>
<div class="column">
P 3-31 6-30 P7-7

</div>
</div>
<div class="layoutArea">
<div class="column">
= M P 6-30 .

</div>
</div>
<div class="layoutArea">
<div class="column">
Study performance of weekly or monthly quantile trading strategies using each of these single ratios as well as your choice of least one nontrivial com- bination of them11.

Set initial capital to be 10 times the gross notional of your first month’s set of positions. You may assume zero trading costs, that trading fractional shares and arbitrary positions sizes are possible, that all securities are easy to borrow with a repo rate equal to your funding rate minus 100bp12, and that

11That is to say, at least 4 types of scores. 12This number may sometimes become negative.

3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
the portfolio capital is equal to the initial capital, adjusted for all realized and unrealized PL to date. Choose either a constant funding rate, or rolling 3-month LIBOR.

Analyze performance of a top-and-bottom decile trading strategy. Now rank based on changes in your ratios rather than the ratios themselves. Play with the effects of sizing positions by rank.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
6 Data Example

Here is recent sample data for Eli Lilly (ticker LLY):

</div>
</div>
<div class="layoutArea">
<div class="column">
6.0.1 SEC Reports

</div>
</div>
<div class="layoutArea">
<div class="column">
per end date

filing date

tot revnu

eps diluted net

basic net eps

tot lterm debt

net lterm debt

net curr debt

zacks x ind code

zacks sector code

zacks metrics ind code tot debt tot equity

ret invst

free cash flow per share shares out

pertype

mkt val

6.0.2

</div>
<div class="column">
2020-06-30 2020-09-30

2020-07-31 2020-10-28 5499.4 5740.6 1.55 1.33

1.55 1.33 15064.4 16334.6 712.3 1786.0 -235.4 -914.3 225.0 225.0

</div>
<div class="column">
2020-12-31 2021-03-31 2021-06-30

2021-02-17 2021-04-30 2021-08-03 7440.001 6805.6 6740.1 2.31 1.49 1.53

2.32 1.49 1.53 16586.6 16199.6 14736.6 1785.8 NaN NaN -1494.2 -3.7 196.3 225.0 225.0 225.0

</div>
<div class="column">
2021-09-30

2021-10-27 6772.8 1.22

1.22 15522.4 505.5

</div>
</div>
<div class="layoutArea">
<div class="column">
Date

2019-10-25 2019-10-28 2019-12-31 2020-01-02 2020-02-19 2020-02-20 2020-03-31 2020-04-01 2020-05-01 2020-05-04 2020-06-30 2020-07-01 2020-07-31 2020-08-03 2020-09-30 2020-10-01 2020-10-28 2020-10-29 2020-12-31 2021-01-04 2021-02-17 2021-02-18 2021-03-31 2021-04-01 2021-04-30 2021-05-03 2021-06-30 2021-07-01 2021-08-03 2021-08-04

</div>
<div class="column">
73.467766 79.176659 92.631604 93.181347 99.774689 77.868328 76.069679 74.808431 84.245853 92.984654

100.062297 99.525966 91.596800 96.155810 93.581421 91.223235 83.017001 97.662767

125.053966 122.580143 153.559427

86.126239 80.002505 79.325897 78.268161

123.433215 153.043896 154.117443 170.694087 170.439396

</div>
</div>
<div class="layoutArea">
<div class="column">
Ratios On Key Dates

</div>
</div>
<div class="layoutArea">
<div class="column">
4.0 4.0 4.0 13.0 13.0 13.0 2.8489 2.2825 2.4784 9.445 5.817 6.4962 5.6018 1.5312 3.066 956.58 959.03 959.03

</div>
<div class="column">
-1.5 225.0 4.0 13.0 2.148 4.7286 4.4859 956.59

</div>
</div>
<div class="layoutArea">
<div class="column">
4.0 4.0

13.0 13.0

3.8221 3.3871

7.3023 5.6651

2.5664 4.1159

956.47 956.58 QQQQQQ 157033.3 141593.2 161509.22 179165.14 220115.53 221020.67

</div>
</div>
<div class="layoutArea">
<div class="column">
(Using MKTV/MKT VAL, FC/NET LTERM DEBT to infer operating income)

</div>
</div>
<div class="layoutArea">
<div class="column">
Debt To Mkt Cap

5.554480 4.352354 3.720165 3.698217 3.453830 5.225211 5.348760 5.438939 4.829656 4.877282 4.532301 4.556724 4.951182 4.105682 4.218627 4.327682 4.755473 3.782411 2.953930 3.013544 2.405588 2.381655 2.563957 2.585826 2.620772 2.293549 1.849797 1.836912 1.658523 2.167266

</div>
<div class="column">
Return On Inv

8.048674 7.249701 6.227653 6.191987 5.794008 8.356740 8.549034 8.689238 7.739485 7.671248 7.127691 7.166169 7.787704 7.841469 8.056110 8.263302 9.075546 6.317094 4.948484 5.047243 4.038046 7.910124 8.509632 8.581494 8.696299 5.842814 4.789536 4.758436 4.324818 5.725783

</div>
<div class="column">
Price To Earnings

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
