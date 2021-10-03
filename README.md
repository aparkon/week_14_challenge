# week_14_challenge

_**Overview**_</br>
  <sub>It analyses actual and strategy return performances by using different SMA period, ML models, and training period.  It particularly focuses on performance differences between SVC classifier model and AdaBoost model.</sup>
 
_**Summary**_</br>

**RESULT 1**</br>
<sup>Model used : SVC classifier model</br>
Short window = 4</br>
Loing window = 100</sup>
![result1](https://user-images.githubusercontent.com/31017911/135743661-f3388e36-7ade-4248-a906-a0f0d71cb560.png)

--------------------------------------------------------------------------------------------------------------------------
**RESULT 2**</br>
<sup>Model used : AdaBoost model</br>
Short window = 50</br>
Loing window = 100</br></sup>
![result2](https://user-images.githubusercontent.com/31017911/135745944-7d0b1008-0a4f-4840-a1dc-d0720a84fbe7.png)

--------------------------------------------------------------------------------------------------------------------------

**RESULT 3**</br>
<sup>Model used : AdaBoost model</br>
Short window = 4</br>
Loing window = 100</br></sup>
![result3](https://user-images.githubusercontent.com/31017911/135769089-1c5f6282-a2a3-4c6f-84ac-e1a5c8aa7e77.png)

--------------------------------------------------------------------------------------------------------------------------




__Answer the following question: What impact resulted from increasing or decreasing the training window?__</br>
<sup>A : Changes in training window affcted earnings before 2016 (used 1 month, 3 months, 12 months) 
  but did not change big flow after 2016.</sup>


__Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?__</br>
<sup>A : Increasing or decreasing both short SMA dratically changed performance of AdaBoost model algo returns.  Applying different short SMA did not change performance in SVC classifier model. </sup>

_**General Assessment**_</br>
<sup> Compared to the AdaBoost model, the classifier model underperformed. In a highly volatile market after the stock market crash of early 2020, both models had similar actual returns and strategy returns. Yet the AdaBoost model responded and predicted much better. Furthermore, a longer short window (used 50, Result 2) displayed a significantly higher algo return rate than a shorter short window (used 4; Result 3). The bottom line is that a shorter SMA facilitates a faster reaction in stock consolidation, which results in a short stop loss in trading, whereas a longer short SMA has more leeway for holding during consolidation. The results from RESULT2 and RESULT 3 suggest that using shorter short SMA's is more effective in an expansionary or bull market period, particularly when using the AdaBoost model. </sup>
