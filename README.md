Description
---

The three charts we decided on were a bar graph, Sankey chart, and bubble (circular area) chart.

![bar](img/bar.png)
![sankey](img/sankey.png)
![bubble](img/bubble.png)

After being instructed on how the experiment would proceed, our 10 participants were given 20 charts of each type, with 6 randomized data values and 2 randomly selected.
The participants were asked what percentage of the larger selection was the smaller selection, and their results were recorded into a CSV table.
Afterwards, they downloaded their CSV file and sent it to us, where we processed it into a master spreadsheet, and determined the average log2Error and CI for each visualization.
Below is the comparison of our average log2Error values to the Cleveland results.

![cleveland results](img/cleveland-results.png)

The average log2Error we receieved for the **bar chart** was **1.367**, slightly higher than the average value achieved in the Cleveland experiment, but firmly within the confidence interval.
The average log2Error we receieved for the **Sankey chart** was **2.277**, a fairly high result, around the Cleveland experiment's T4 value.
The average log2Error we receieved for the **bubble chart** was **2.532**, slightly lower than the Cleveland experiment's result but also firmly within the confidence interval.

Our confidence intervals are shown below.

![CIs](img/intervals.png)

![CI graph](img/graph.png)

```
