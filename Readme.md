# MScFE 600 FINANCIAL DATA

## Group Work Project # 1

Below you will find four separate scenarios and each one includes a set of questions that you are required to answer in words, using code, or both words and code. The 'Submission requirements and format' section on Page 4 provides a detailed explanation on how to complete and submit the assignment through the online platform.

---

## Tasks

### 1. Data Quality

One of the important components of financial data is ensuring good quality data. However, it is helpful to understand what poor quality data looks like.

**a.** Provide an example of poor quality structured data

**b.** How would you recognize this poor quality? Write 3 - 4 sentences that show how the data fails to include properties of good quality data.

**c.** Provide an example of poor quality unstructured data

**d.** Unstructured data can be more difficult to assess than structured data. Just as you did in part b, write 3 - 4 sentences that show how this unstructured data fails to check requirements of good quality data.

---

### 2. Yield Curve Modeling

**a.** Pick government securities from a country. The country selected should be one of the countries from your group so that you can fit a Nelson-Siegel model.

**b.** Be sure to pick maturities ranging from short-term to long-term (e.g. 6 month maturity to 20 or 30 year maturities).

**c.** Fit a Nelson-Siegel model.

**d.** Fit a Cubic-Spline model.

**e.** Compare the models in terms of 1) fit and 2) interpretation.

**f.** Be sure to specify at the levels of model parameters (ex. Alpha1).

**g.** In Module 2 Lesson 4 ('Smoothing Data'), we said smoothing data can be unethical. If Nelson-Siegel is smoothing the yield curve, is this considered unethical? Why or why not?

---

### 3. Exploiting Correlation

Financial Data is meant not only to process data but to understand how meaningful factors can be used to summarize or represent the data. Let's understand the role that correlation and principal components play.

**a.** Generate 5 uncorrelated Gaussian random variables that simulate yield changes (they can be positive or negative with a mean close to 0 and a standard deviation that is small).

**b.** Run a Principal Components using EITHER the correlation OR covariance matrix.

**c.** Write a paragraph explaining how the variances of each component compare with each other. In this paragraph, you will address the following question: how much variance is explained by Component 1, Component 2, Component 3?

**d.** Produce a screeplot (see [Scree Plot](https://en.wikipedia.org/wiki/Scree_plot)) of the variance explained for each component.

**Now let's work with real data:**

**e.** Collect the daily closing yields for 5 government securities, say over 6 months.

**f.** Be sure to compute the daily yield changes!

**g.** Re-run the Principal Components using EITHER the correlation or covariance matrix.

**h.** How do the variances of each component compare? In other words, how much variance is explained by Component 1, Component 2, Component 3, etc.?

**i.** Produce a screeplot of the variance explained for each component.

**j.** How does the screeplot from the uncorrelated data compare with the screeplot from the government data?

---

### 4. Empirical Analysis of ETFs

Pick a sector ETF (in the US, for example, XLRE)

**a.** Find the 30 largest holdings.

**b.** Get at least 6 months of data (~ 120 data points).

**c.** Compute the daily returns.

**d.** Compute the covariance matrix.

**e.** Compute the PCA.

**f.** Compute the SVD.