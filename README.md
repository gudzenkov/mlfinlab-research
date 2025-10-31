# Research Notebooks

These notebooks provide additional theoretical elements, examples of the use of the algorithms implemented in the MlFinLab package. Research notebooks are a perfect tool to try algorithms hands-on and gain additional understanding of how they can be used on real data examples.

## Available Notebooks

The following is the directory structure for the Research notebooks with links to their abstracts.

**Quick Links to Notebook Abstracts:**

**Advances in Financial Machine Learning:**

*Backtest Statistics:*
- [Backtesting.ipynb](#backtestingipynb)
- [Chapter14_BacktestStatistics.ipynb](#chapter14backteststatisticsipynb)

*Bet Sizing:*
- [Chapter10_Exercises.ipynb](#chapter10exercisesipynb)
- [Chapter10_Exercises (mlfinlab).ipynb](#chapter10exercises-mlfinlabipynb)
- [ef3m_testing.ipynb](#ef3m_testingipynb)

*Cross-Validation in Finance:*
- [Chapter7_Exercises_CrossValidation.ipynb](#chapter7exercises_crossvalidationipynb)

*Ensemble Methods:*
- [Ensemble_Methods.ipynb](#ensemble_methodsipynb)

*Feature Engineering:*
- [NoiseReduction.ipynb](#noisereductionipynb)
- [Volatility_estimators.ipynb](#volatility_estimatorsipynb)

*Feature Importance:*
- [Chapter8_Exercises_Feature_Importance.ipynb](#chapter8exercises_feature_importanceipynb)
- [Cluster_Feature_Importance.ipynb](#cluster_feature_importanceipynb)

*Financial Data Structures:*
- [Dollar-Imbalance-Bars.ipynb](#dollar-imbalance-barsipynb)
- [ETF_trick_hedge.ipynb](#etf_trick_hedgeipynb)
- [Futures_Roll_Trick.ipynb](#futures_roll_trickipynb)
- [Getting Started.ipynb](#getting-startedipynb)
- [online_data_structures.ipynb](#online_data_structuresipynb)
- [Sample_Techniques.ipynb](#sample_techniquesipynb)

*Fractionally Differentiated Features:*
- [Chapter5_Exercises.ipynb](#chapter5exercisesipynb)

*Hyper-Parameter Tuning:*
- [Hyperparameter Tuning with CV.ipynb](#hyperparameter-tuning-with-cvipynb)

*Labelling:*
- [BBand-Question.ipynb](#bband-questionipynb)
- [Chapter3_Labeling.ipynb](#chapter3_labelingipynb)
- [Chapter3-Part1.ipynb](#chapter3-part1ipynb)
- [Meta-Labels-MNIST.ipynb](#meta-labels-mnistipynb)
- [Trend-Follow-Question.ipynb](#trend-follow-questionipynb)

*Machine Learning Asset Allocation:*
- [Chapter16.ipynb](#chapter16ipynb)

*Microstructural Features:*
- [Chapter19-Questions.ipynb](#chapter19-questionsipynb)
- [Entropy_Measures.ipynb](#entropy_measuresipynb)
- [First_Generation.ipynb](#first_generationipynb)
- [Microstructural-Features.ipynb](#microstructural-featuresipynb)
- [Second_Generation.ipynb](#second_generationipynb)
- [Third_Generation.ipynb](#third_generationipynb)

*Models:*
- [History_Weighted_Regression.ipynb](#history_weighted_regressionipynb)

*Sample Weights:*
- [Chapter4_Exercises.ipynb](#chapter4exercisesipynb)
- [Sequential_Bootstrapping.ipynb](#sequential_bootstrappingipynb)
- [Trend-Follow-Question-Extended-SB-Cross-Val.ipynb](#trend-follow-question-extended-sb-cross-valipynb)

*Understanding Strategy Risk:*
- [Chapter15_Exercises_UnderstandingStrategyRisk.ipynb](#chapter15exercises_understandingstrategyripynb)

**Backtest Overfitting:**
- [Backtest Overfitting.ipynb](#backtest-overfittingipynb)

**Codependence:**
- [Codependence_by_Marti.ipynb](#codependence_by_martiipynb)
- [Optimal_Transport.ipynb](#optimal_transportipynb)

**Data Generation:**
- [Bootstrap.ipynb](#bootstrapipynb)
- [CorrGAN.ipynb](#corrganipynb)
- [Correlated_Random_Walks.ipynb](#correlated_random_walksipynb)
- [HCBM.ipynb](#hcbmipynb)
- [Vines.ipynb](#vinesipynb)

**Labeling:**
- [Labeling_vs_Benchmark.ipynb](#labeling_vs_benchmarkipynb)
- [Labels_Excess_Over_Mean.ipynb](#labels_excess_over_meanipynb)
- [Labels_Excess_Over_Median.ipynb](#labels_excess_over_medianipynb)
- [Labels_Fixed_Horizon.ipynb](#labels_fixed_horizonipynb)
- [Labels_Matrix_Flags.ipynb](#labels_matrix_flagsipynb)
- [Labels_Raw_Return.ipynb](#labels_raw_returnipynb)
- [Labels_Tail_Sets.ipynb](#labels_tail_setsipynb)

**Networks:**
- [MST.ipynb](#mstipynb)
- [PMFG.ipynb](#pmfgipynb)

**Online Portfolio Selection:**
- [Data Selection.ipynb](#data-selectionipynb)
- [Introduction to Online Portfolio Selection.ipynb](#introduction-to-online-portfolio-selectionipynb)
- [Online Portfolio Selection - Mean Reversion.ipynb](#online-portfolio-selection---mean-reversionipynb)
- [Online Portfolio Selection - Momentum.ipynb](#online-portfolio-selection---momentumipynb)
- [Online Portfolio Selection - Pattern Matching.ipynb](#online-portfolio-selection---pattern-matchingipynb)

**Optimal Mean Reversion:**
- [OU_model.ipynb](#ou_modelipynb)

**Portfolio Optimisation Tutorials:**
- [HERC_&_HRP_Comparison.ipynb](#herc_hrp_comparisonipynb)
- [Hierarchical_Equal_Risk_Contribution (HERC).ipynb](#hierarchical_equal_risk_contribution-hercipynb)
- [Hierarchical_Risk_Parity_(HRP).ipynb](#hierarchical_risk_parity_hrpipynb)
- [Mean_Variance_Optimisation_(MVO).ipynb](#mean_variance_optimisation_mvoipynb)
- [Nested_Clustered_Optimisation_(NCO).ipynb](#nested_clustered_optimisation_ncoipynb)
- [Risk_Estimators.ipynb](#risk_estimatorsipynb)
- [Theory_Implied_Correlation_(TIC).ipynb](#theory_implied_correlation_ticipynb)

---

## Notebook Abstracts

### Advances in Financial Machine Learning

#### Backtesting.ipynb

This notebook provides a comprehensive overview of backtesting methodologies for trading strategies. It covers fundamental concepts of backtesting, common pitfalls to avoid, and best practices for realistic performance evaluation. The notebook demonstrates how to properly account for transaction costs, slippage, and market impact when evaluating strategy performance.

#### Chapter14_BacktestStatistics.ipynb

This notebook covers some of the statistics that are used for understanding the characteristics of a strategy related to levels of risk and return. It also provides tools to test if the strategy satisfies desired profitability benchmarks (Sharpe ratio in particular). Statistics in this chapter cover the following topics:

- Drawdown
- Time under water
- Herfindahl-Hirschman Index or Concentration of returns
- Sharpe ratio
- Probabilistic Sharpe ratio
- Deflated Sharpe ratio

#### Chapter10_Exercises.ipynb

Your ML algorithm can achieve high accuracy, but if you do not size your bets properly, your investment strategy will inevitably lose money. This notebook contains the worked exercises from the end of chapter 10 of "Advances in Financial Machine Learning" by Marcos López de Prado. The questions are restated here in this notebook, with the accompanying code solutions following directly below each question. All code in this notebook can be run as is and requires no external data, with the exception of the EF3M algorithm used in exercise 10.4 which can be found in mlfinlab.bet_sizing.ef3m.py.

#### Chapter10_Exercises (mlfinlab).ipynb

Same as **Chapter10_Exercises.ipynb**, but all exercises are solved using the functionality provided by mlfinlab.

#### ef3m_testing.ipynb

This notebook tests the implementation of the EF3M algorithm using synthetic data as well as the example used in the source literature. This notebook is intended to provide convincing evidence of the accuracy of this EF3M implementation.

#### Chapter7_Exercises_CrossValidation.ipynb

Cross-Validation is a Machine Learning technique aiming to determine how the performance of a model will generalize to an independent data set. Although broadly useful in all sorts of problems it generally fails when applied to a financial problem. In this chapter, we will explore why it fails, and how to apply two techniques we call purging and embargo to get around its problems.

#### Ensemble_Methods.ipynb

In this research notebook, some of the details about the two of the most popular ML ensemble methods are discussed. The goal of this notebook is to investigate the efficacy of the methods, and how to avoid common errors that lead to their misuse in finance.

#### NoiseReduction.ipynb

This notebook demonstrates noise reduction techniques for financial time series data. It covers various filtering methods including the Savitzky-Golay filter and wavelets, helping to separate signal from noise in price data. The methods shown are essential for feature engineering and improving model performance by reducing overfitting to noisy market data.

#### Volatility_estimators.ipynb

This notebook explores various volatility estimation techniques beyond simple historical volatility. It implements advanced estimators such as Parkinson, Garman-Klass, Rogers-Satchell, and Yang-Zhang volatility measures. These estimators leverage high-low-open-close price data to provide more accurate volatility estimates than standard methods, which is crucial for risk management and option pricing.

#### Chapter8_Exercises_Feature_Importance.ipynb

One of the most pervasive mistakes in financial research is to take some data, run it through an ML algorithm, backtest the predictions, and repeat the sequence until a nice-looking backtest shows up. Academic journals are filled with such pseudo-discoveries, and even large hedge funds constantly fall into this trap.

It typically takes about 20 such iterations to discover a (false) investment strategy subject to the standard significance level (false positive ratio) of 5%. This research notebook explores why such an approach is a waste of time and money, and how feature importance offers an alternative.

#### Cluster_Feature_Importance.ipynb

The goal of this notebook is to demonstrate the Clustered Feature Importance, a feature importance method suggested by Dr. Marcos Lopez de Prado in the paper, and the book Machine Learning for Asset Managers. The aim of CFI is to cluster similar features and apply the feature importance analysis at the cluster level. This way clusters are mutually dissimilar and the method is tends to tame the substitution effect and by using information theory along we can also reduce the multicollinearity of the dataset.

#### Dollar-Imbalance-Bars.ipynb

In this notebook the properties of the imbalance bars are studied - their distribution, autocorrelation. The key goal of imbalance/run bars is equal amount of information inside of each bar. That is why we should consider using information theory to research properties of imbalance bars in comparison with time/dollar bars.

#### ETF_trick_hedge.ipynb

This notebook is the ETF trick use case for SPX/EuroStoxx hedging implementation. Data used is the daily SPY and EUROSTOXX futures data and EUR/USD exchange rates. Hedging weights are recalculated on a daily basis.

#### Futures_Roll_Trick.ipynb

Building trading strategies on futures contracts has the unique problem that a given contract is for a short duration of time, for example, the 3-month contract on wheat. In order to build a continuous time series across the different contracts, we stitch them together, most commonly using an auto roll or some other function. However, a problem occurs when we do this, which is: come the expiry date, there is usually a price difference between the old contract and the new one. Often this difference is quite small, however, for some contracts it can be quite substantial (especially if the underlying asset has a high carry cost).

This notebook shows that not accounting for the differences in contract prices can add additional noise to the model.

#### Getting Started.ipynb

The purpose of this notebook is to act as a tutorial to bridge the gap between idea and implementation. In particular, we will be looking at how to create the various financial data structures and how to format your data so that you can make use of the mlfinlab package.

For this tutorial, we made use of the sample data provided by TickWrite LLC. Using S&P500 E-mini futures.

#### online_data_structures.ipynb

This notebook demonstrates online (streaming) implementations of financial data structures. Unlike batch processing methods, online data structures can be updated incrementally as new data arrives, making them suitable for real-time trading systems. The notebook covers online versions of dollar bars, volume bars, and imbalance bars, showing how to efficiently process tick data in a streaming fashion.

#### Sample_Techniques.ipynb

In this notebook data analysis is performed on a series of E-mini S&P 500 futures tick data:

- Form tick, volume, and dollar bars.
- Count the number of bars produced by tick, volume, and dollar bars on a weekly basis. Plot a time series of that bar count. What bar type produces the most stable weekly count? Why?
- Compute serial correlation of returns for the three bar types. What bar method has the lowest serial correlation?
- Apply the Jarque-Bera normality test on returns from the three bar types. What method achieves the lowest test statistic?
- Standardize & Plot the Distributions

#### Chapter5_Exercises.ipynb

In this notebook, we provide solutions to the exercises 5.1 through 5.6 from AFML by Marcos Lopez de Prado and illustrate how fractionally differentiated series can be made stationary. Exercises are particularly helpful in showing how to use fractionally differentiated series as a feature to train an algorithm.

#### Hyperparameter Tuning with CV.ipynb

Hyper-parameter tuning is an essential step in building Machine Learning algorithms. Although the ML model tuning process may seem to be no different for finance, but if not done properly the algorithm will likely to overfit and produce negative performance. As optimizing models in finance are prone to overfitting, we must consider some key points mentioned in the chapter.

#### BBand-Question.ipynb

This notebook answers question 3.5 form the textbook Advances in Financial Machine Learning.

"Develop a mean-reverting strategy based on Bollinger bands. For each observation, the model suggests a side, but not a size of the bet".

#### Chapter3_Labeling.ipynb

This comprehensive notebook covers the complete Chapter 3 from "Advances in Financial Machine Learning" on labeling methods. It includes implementations of the triple-barrier method, meta-labeling, and various labeling techniques for financial machine learning. The notebook demonstrates how to properly label financial data for supervised learning, including handling of concurrent labels and sample weights.

#### Chapter3-Part1.ipynb

This notebook answers some questions 3.1 - 3.3 from Chapter 3 of the AFML book by Marcos Lopez de Prado.

#### Meta-Labels-MNIST.ipynb

This notebook is a small MVP regarding the idea of meta labeling by Marcos Lopez de Prado, Advances in Financial Machine Learning, Chapter 3, pg 50.

The central idea is to create a secondary ML model that learns how to use the primary exogenous model. This leads to improved performance metrics, including: Accuracy, Precision, Recall, and F1-Score.

To illustrate the concept we made use of the MNIST data set to train a binary classifier on identifying the number 3, from a set that only includes the digits 3 and 5. The reason for this is that the number 3 looks very similar to 5 and we expect there to be some overlap in the data, i.e. the data are not linearly separable. Another reason we chose the MNIST dataset to illustrate the concept, is that MNIST is a solved problem and we can witness improvements in performance metrics with ease.

#### Trend-Follow-Question.ipynb

This notebook answers question 3.4 form the textbook Advances in Financial Machine Learning.

#### Chapter16.ipynb

This notebook explores the exercises at the back of Chapter-16 in the book "Advances in Financial Machine Learning". We will use the portfolio optimization algorithms in the mlfinlab package to do a comparison of their performance. The questions are restated here in this notebook, with the accompanying code solutions following directly below each question.

#### Chapter19-Questions.ipynb

Market microstructure features aim to tease out useful information from the trading behavior of market participants on exchanges. These features have become more popular with the increased amount and granularity of data provided by exchanges. As a result, multiple models of liquidity, uncertainty, and price impact have emerged from this data.

#### Entropy_Measures.ipynb

This notebook explores entropy-based measures for analyzing market microstructure. It covers Shannon entropy, plug-in entropy estimation, and Lempel-Ziv entropy complexity to quantify information content and predictability in financial time series. These entropy measures help assess market efficiency and can be used as features for machine learning models.

#### First_Generation.ipynb

This notebook implements first-generation microstructural features based on classical market microstructure theory. It includes bid-ask spread analysis, trade imbalance measures, and basic liquidity metrics. These foundational features capture fundamental aspects of order flow and market liquidity that are essential for understanding price formation.

#### Microstructural-Features.ipynb

Market microstructure features aim to tease out useful information from the trading behavior of market participants on exchanges. These features have become more popular with the increased amount and granularity of data provided by exchanges. As a result, multiple models of liquidity, uncertainty, and price impact have emerged from this data.

#### Second_Generation.ipynb

This notebook presents second-generation microstructural features that build upon classical measures. It includes VPIN (Volume-Synchronized Probability of Informed Trading), Kyle's lambda, and Amihud's illiquidity measure. These advanced features better capture information asymmetry, price impact, and market depth dynamics in modern electronic markets.

#### Third_Generation.ipynb

This notebook covers third-generation microstructural features based on recent research advances. It implements features derived from high-frequency data patterns, including microstructure noise measures, effective spread decomposition, and adverse selection components. These cutting-edge features are particularly useful for high-frequency trading strategies and market making applications.

#### History_Weighted_Regression.ipynb

This notebook demonstrates the History Weighted Regression (HWR) method for making predictions. HWR selects relevant historical instances based on similarity and informativeness to the current observation, then runs regression on this subsample. The method is based on papers by Czasonis, Kritzman, and Turkington, offering a novel approach to forecast factor returns by focusing on the most relevant historical periods rather than using all available data.

#### Chapter4_Exercises.ipynb

This notebook describes tools that handle the challenge of sampling observations (with replacement) when they are not IID (independent and identically distributed). This is especially hard in financial data sets which are rarely IID. In the framework espoused by MLDP in AFML, observations are labeled using triple-barrier method.

In this notebook, we also provide the answers to the questions at the back of Chapter 4.

#### Sequential_Bootstrapping.ipynb

In Chapter 3 notebooks, we have understood how Triple-Barrier and Meta-Labelling concepts work. The next problem in financial machine learning is non-independent samples as a result of that standard machine learning models like Random Forest and Bagging Classifier need to be modified. In this notebook, we will tackle the problem of concurrency and the solution to that - Sequential Bootstrapping.

#### Trend-Follow-Question-Extended-SB-Cross-Val.ipynb

This notebook extends Trend-Following notebook from Chapter 3 by adding sample weights, Purged Cross-Validation, MDI, MDA, SFI feature importance plots.

#### Chapter15_Exercises_UnderstandingStrategyRisk.ipynb

As the majority of the investment strategies have exit conditions (either in a form of stop loss or take profit), the outcomes can be modeled using a binomial process. This approach shows whether the strategy is sensitive to minor changes in betting frequency, odds, and payouts.

In this notebook, the exercises from Chapter-15 in the book "Advances in Financial Machine Learning" are implemented.

---

### Backtest Overfitting

#### Backtest Overfitting.ipynb

This notebook describes the Haircut Sharpe Ratios and Profit Hurdle algorithms and how they may be used in real-life applications. The algorithms were originally presented by the authors Campbell R. Harvey and Yan Liu in the paper "Backtesting" ([available here](https://papers.ssrn.com/abstract_id=2345489)).

---

### Codependence

#### Codependence_by_Marti.ipynb

GPR and GNPR distances are a part of a novel technique for measuring the distance between two random variables that allows to separate the measurement of distribution information and the dependence information. A mix of both types of information can be used in a chosen proportion.

This notebook describes the GPR and the GNPR distances how they may be used in real-life applications. These novel distances were originally presented by the Gautier Marti in the work "Some contributions to the clustering of financial time series and applications to credit default swaps" ([available here](https://www.researchgate.net/publication/322714557)).

#### Optimal_Transport.ipynb

Optimal Transport is a unique distance measure between two random variables that allows measuring the codependence with respect to similarity to the target codependence type.

This notebook describes the Optimal Transport distance measure and how it may be used in real-life applications. This distance measure was described by Marti et al. in the work "Exploring and measuring non-linear correlations: Copulas, Lightspeed Transportation and Clustering." ([available here](https://arxiv.org/pdf/1610.09659.pdf)).

---

### Data Generation

#### Bootstrap.ipynb

Bootstrapping is a statistical method used to resample a dataset with replacement to estimate its population statistics (such as mean, median, standard deviation, etc.) In machine learning applications, bootstrap bagging is an ensemble technique used in algorithms as AdaBoost, random forests, XGBoost, and more.

This technique usually leads to less overfitting and improvement of the stability of the models. Bootstrap methods draw small samples (with replacement) from a large dataset one at a time, and organizing them to construct a new dataset. In this notebook, we examine three bootstrap methods. Row, pair, and block bootstrap.

#### CorrGAN.ipynb

Generating realistic financial correlation matrices is highly complex. Correlation matrices are useful for risk management, asset allocation, hedging instrument selection, pricing models, etc. Hüttner, Mai and Mineo (2018) concluded that "To the best of our knowledge, there is no algorithm available for the generation of reasonably random [financial] correlation matrices with the Perron-Frobenius property. [...] we expect the task of finding such correlation matrices to be highly complex"

This problem was addressed by Marti (2020) by using a generative adversarial network (a GAN, named CorrGAN) that can generate realistic financial correlation matrices. CorrGAN was trained on empirical correlation matrices based on the S&P 500 returns. CorrGAN generates correlation matrices that have many "stylized facts" seen in empirical correlation matrices.

#### Correlated_Random_Walks.ipynb

Being able to discriminate random variables on a time series on both distribution and dependence distributions, is motivated by the study of financial assets returns. For example, if the returns of one asset are normally distributed, and the returns of another asset follow a heavy-tail distribution, if these two returns are perfectly correlated, are they similar? The authors assert that they are not similar from a risk perspective.

The authors proposed a distance metric called the generic non-parametric representation (GNPR) that "improves the performance of machine learning algorithms working on independent and identically distributed stochastic processes". It can successfully discriminate multiple distributions from multiple time series.

The authors provide a method to generate such time series to verify the clustering functionality of GNPR.

#### HCBM.ipynb

In their work, Marti et al, (2016) tried to answer the question, how long is enough? referring to how many days of return correlations of financial time series are needed for clustering algorithms to avoid spurious results without losing dynamics.

They provide a method to generate correlation matrices that follow a hierarchical correlation block model structure (HCBM). Price time series of traded assets have been observed and verified several times for different markets to follow this structure. The HCBM correlation matrices generated by this method can be used to generate financial time series. The underlying distributions of the generated time series can be either a gaussian random walk model or an N-variate Student's t-distribution. The former being the standard, but debated, model of quantitative finance for financial time series, and the latter being able to capture heavy-tailed behavior and tail-dependence.

#### Vines.ipynb

There is great interest in fast and efficient methods to generate positive-semidefinite financial correlation matrices. Some methods have a higher computational requirement and experience slow-downs as the dimension of the correlation matrix to generate increases. Lewandowski, Kurowicka, and Joe (2009) devised three methods based on a statistical tool called a 'vine' and on partial correlations to generate these matrices that greatly decrease the time to generate a correlation matrix.

---

### Labeling

#### Labeling_vs_Benchmark.ipynb

Labeling against benchmark is a simple method of labeling financial data in which time-indexed returns are labeled according to whether they exceed a set value. The benchmark can be either a constant value, or a pd.Series of values with an index matching that of the returns. The labels can be the numerical value of how much each observation's return exceeds the benchmark, or the sign of the excess.

This notebook presents the method to label data according to return over a given benchmark.

#### Labels_Excess_Over_Mean.ipynb

Using cross-sectional data on returns of many different stocks, each observation is labeled according to whether (or how much) its return exceeds the mean return. It is a common practice to label observations based on whether the return is positive or negative. However, this may produce unbalanced classes, as during market booms the probability of a positive return is much higher, and during market crashes they are lower (Coqueret and Guida, 2020). Labeling according to a benchmark such as mean return alleviates this issue.

This notebook presents the method to label data according to excess return over mean.

#### Labels_Excess_Over_Median.ipynb

In this notebook, we demonstrate labeling financial data according to excess over median. Returns are calculated from cross-sectional data on prices of many different stocks. Each observation is labeled according to whether its return exceeds the median return of all stocks in the given time index. The labels can be given numerically as the value of excess over median, or categorically as the sign of the numerical return. The user can also specify a resample period, and optionally lag the returns to make them forward-looking.

#### Labels_Fixed_Horizon.ipynb

Fixed Horizon is a classification labeling technique in which time-indexed data is labeled according to whether it exceeds, falls in between, or is less than a threshold. This method is most commonly used with time bars, but also be applied to any time-indexed data such as dollar or volume bars. The subsequent labeled data can then be used as training and test data for ML algorithms.

#### Labels_Matrix_Flags.ipynb

The matrix flag labeling method is a multistep labeling method meant to match a data window of price data for a single stock with a template. In the literature, the template presented is a bull flag 10 by 10 template, with the first 7 columns representing the consolidation following an initial price surge, and the final 3 represent the breakout. Each column of the template corresponds to a chronological tenth of the data, and each row corresponds to a decile relative to the entire data window. Each element contains the proportion of points in each tenth that corresponds to the appropriate decile given by row. Once the data has been transformed this way, it is multiplied element-wise with the template, and the sum of all elements in the resulting matrix is the scalar value denoting total fit for the day. The higher the fit, the better match with the template pattern.

#### Labels_Raw_Return.ipynb

Labeling data by raw returns is the most simple and basic method of labeling financial data for machine learning. Raw returns can be calculated either on a simple or logarithmic basis. Using returns rather than prices is usually preferred for financial time series data because returns are usually stationary, unlike prices. This means that returns across different assets, or the same asset at different times, can be directly compared with each other. The same cannot be said of price differences, since the magnitude of the price change is highly dependent on the preceding price, which varies with time.

#### Labels_Tail_Sets.ipynb

A tail set is defined to be a group of assets whose volatility-adjusted price change is in the highest or lowest quantile, for example, the highest or lowest 5%.

A classification model is then fit using these labels to determine which stocks to buy and sell, for a long / short portfolio.

---

### Networks

#### MST.ipynb

Network analysis can provide interesting insights into the dynamics of the market, and the continually changing behaviour. A Minimum Spanning Tree (MST) is a useful method of analyzing complex networks, for aspects such as risk management, portfolio design, and trading strategies. For example Onnela et al. (2003) notices that the optimal Markowitz portfolio is found at the outskirts of the tree. Analysing the Tree structure, as a representation of the market, can give us an idea about the stability and state of the market.

A Minimum Spanning Tree (MST) is a graph consisting of the fewest number of edges needed for all nodes to be connected by some path - where the combination of edge weights sum to the smallest total possible.

MST strongly shrinks during a stock crisis. Properties such as skewness are positive during times of market crises (such as 1987, early 2000's and 2008) and skewness and kurtosis have stabilised after 2000's. Analysing the Tree structure, as a representation of the market, can give us an idea about the stability and state of the market and predict how volatility shocks will propagate through a network.

#### PMFG.ipynb

Pozzi, Di Matteo, and Aste (2013) conclude that it is "better to invest in the peripheries" of the Planar Maximally Filtered Graph (PMFG), as investing in the peripheries lead to better returns, and reduced risk. This notebook explores the impacts of Covid-19 by simulating two investment portfolios - a portfolio consisting of peripheral stocks, versus a portfolio consisting of central stocks in the Planar Maximally Filtered Graph. This notebook also showcases how to construct PMFG visualisations, and how to create the dual interface to compare MST and Average Linkage MST (ALMST).

---

### Online Portfolio Selection

#### Data Selection.ipynb

Data selection is one of the hardest problems in research. With numerous test sets and a vast amount of resources available to the public, it is tempting to overfit and choose the data that best represent your hypothesis. However, conclusions that are reached from these weak models are more prone to outliers and can have a narrow scope for applications. Online portfolio selection also deals with the same issues as it is heavily dependent on the data available.

#### Introduction to Online Portfolio Selection.ipynb

Online Portfolio Selection is an algorithmic trading strategy that sequentially allocates capital among a group of assets to maximize the final returns of the investment. Traditional theories for portfolio selection, such as Markowitz's Modern Portfolio Theory, optimize the balance between the portfolio's risks and returns. However, OLPS is founded on the capital growth theory, which solely focuses on maximizing the returns of the current portfolio.

Through these walkthroughs of different portfolio selection strategies, we hope to introduce a set of different selection tools available for everyone. Most of the works will be based on Dr. Bin Li and Dr. Steven Hoi's book, *Online Portfolio Selection: Principles and Algorithms*, and further recent papers will be implemented to assist the development and understanding of these unique portfolio selection strategies.

#### Online Portfolio Selection - Mean Reversion.ipynb

Mean Reversion is an effective quantitative strategy based on the theory that prices will revert back to its historical mean. A basic example of mean reversion follows the benchmark of Constant Rebalanced Portfolio. By setting a predetermined allocation of weight to each asset, the portfolio shifts its weights from increasing to decreasing ones. This module will implement four types of mean reversion strategies: Passive Aggressive Mean Reversion, Confidence Weighted Mean Reversion, Online Moving Average Reversion, and Robust Median Reversion.

Through this notebook, the importance of hyperparameters is highlighted as the choices greatly affect the outcome of returns. A lot of the hyperparameters for traditional research has been chosen by looking at the data in hindsight, and fundamental analysis of each dataset and market structure is required to profitably implement this strategy in a real-time market scenario.

#### Online Portfolio Selection - Momentum.ipynb

Momentum strategies have been a popular quantitative strategy in recent decades as the simple but powerful trend-following allows investors to exponentially increase their returns. This module will implement two types of momentum strategy with one following the best-performing assets in the last period and the other following the Best Constant Rebalanced Portfolio until the last period.

In this notebook, we will dive into Exponential Gradient, and Follow the Leader momentum strategies.

#### Online Portfolio Selection - Pattern Matching.ipynb

Pattern matching locates similarly acting historical market windows and make future predictions based on the similarity. Traditional quantitative strategies such as momentum and mean reversion focus on the directionality of the market trends. The underlying assumption that the immediate past trends will continue is simple but does not always perform the best in real markets. Pattern matching strategies combine the strengths of both by exploiting the statistical correlations of the current market window to the past.

---

### Optimal Mean Reversion

#### OU_model.ipynb

An Ornstein-Uhlenbeck process is a great tool for modeling the behavior of mean-reverting portfolio prices. Tim Leung, Xin Li in "Optimal Mean reversion Trading: Mathematical Analysis and Practical Applications" (2015) present the solution to the optimal timing problems for entering and liquidating the position and the method of creating an optimal mean-reverting portfolio of two assets based on the Ornstein-Uhlenbeck model. Their findings also provide optimal solutions with respect to the stop-loss level if they are provided as an extension of a base problem.

---

### Portfolio Optimisation Tutorials

#### HERC_&_HRP_Comparison.ipynb

This tutorial notebook will demonstrate the differences between the Hierarchical Equal Risk Contribution and the Hierarchical Risk Party algorithms, applied through the MlFinLab library. Readers will be taken through how they can construct optimal portfolios utilizing both algorithms while understanding the main differences which separate them.

#### Hierarchical_Equal_Risk_Contribution (HERC).ipynb

The following notebook will explore MlFinLab's implementation of Thomas Raffinot's Hierarchical Equal Risk Contribution portfolio optimization technique. Users will be taken through how they can construct an optimal portfolio and the different risk metrics and linkage algorithms supported. Additionally, users will be able to see how they can create custom use cases with this library.

#### Hierarchical_Risk_Parity_(HRP).ipynb

Throughout this notebook, users will be taken through how they can construct optimal portfolios using the Hierarchical Risk Parity algorithm. Users will also be shown how to create custom use cases and how to build a Long/Short portfolio.

All calculations and algorithms will be implemented through the MlFinLab library.

#### Mean_Variance_Optimisation_(MVO).ipynb

The following notebook will explore MlFinLab's implementation of Harry Markowitz's modern portfolio theory. Users will be shown how they can construct optimal portfolios for different objective functions and also how to incorporate custom input in their calculations.

#### Nested_Clustered_Optimisation_(NCO).ipynb

This notebook describes the Nested Clustered Optimization (NCO) algorithm, the Monte Carlo Optimization Selection (MCOS) algorithm alongside the De-noising algorithm, and other helping functions. Also, it shows how these can be used on some real examples.

The algorithms and the descriptions were originally presented by Marcos Lopez de Prado in the paper *A Robust Estimator of the Efficient Frontier* ([available here](https://papers.ssrn.com/abstract_id=3469961)).

#### Risk_Estimators.ipynb

This notebook describes the functions implemented in the RiskEstimators class, related to different ways of calculating and adjusting the Covariance matrix. Also, it shows how the corresponding functions from the mlfinlab library can be used and how the outputs can be analyzed.

#### Theory_Implied_Correlation_(TIC).ipynb

This notebook describes the Theory-Implied Correlation (TIC) algorithm and the correlation matrix distance metric. Also, it shows how these can be used on some real examples.

The algorithms and the descriptions were originally presented by Marcos Lopez de Prado in the paper *Estimation of Theory-Implied Correlation Matrices* ([available here](https://papers.ssrn.com/abstract_id=3484152)).

---

**Last Updated:** 2025-10-31
