# Learning Data Science on the Ethereum Blockchain with [@OmniAnalytics](https://twitter.com/OmniAnalytics)

<p align="center">
<img src="images/cover_art.png">
</p>

## Description

We want to share our joy of data science with the Ethereum eco-system through an informative set of online courses and case studies that merge data analysis, blockchain analytics and statistical programming.

We aspire to create a modular online course to help new blockchain developers understand the principles and best practices of data science. Using open data sources from across the Ethereum landscape (think StateoftheDApps, UniSwap, & Etherscan), the course will teach the topics of data munging, data visualization, exploratory data analysis, machine learning, and dabble in a bit of deep learning and artificial intelligence.  As the course grows, we intend to create case studies around how to apply data science to specific DApps (think machine learning techniques for predicting markets with Numer.ai data or analyzing traits in CryptoKitties).

Our ultimate vision is to spur and inspire the next generation of developers through interesting applications of data science to emerging blockchain technologies.

## Tentative Course Outline

Module 1 - Basic Data Structures and Munging
* Setting up your R environment
* Basics of syntax
* Importing data
* Data structures
* Reshaping with dplyr

Data Sources: *Gitcoin Grants, State of the DApps*

Module 2 - Statistical Graphics and Visualization
* Why graph?
* Thinking in layers
* Basic graph types
* Advanced statistical graphics

Data Sources: *Etherscan*

Module 3 - Supervised and Unsupervised Machine Learning
* The ML workflow
* Supervised learning for classification
* Unsupervised learning for grouping
* Forecasting what's next
* Deep learning for sequences

Data Sources: *Numerai Tournament Data, UniSwap*

Module 4 - Case Studies
* [Clustering and segmenting Ethereum validator performance](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/validators/1-1-Case-Study-Validator.html) ([R], [Python], [Video](https://youtu.be/2JLRnKmlV8I))
* Visualizing slashings in the Ethereum Medalla testnet ([R](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/slashers/2-1-Case-Study-Slashed.html#1), [Python])
* [Using R Shiny to explore Numerai tournament data](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/)
* [Reconstructing the Crypto Sentiment Investment Curve in ggplot2]() 
* [Interacting with and Analyzing Numerai Network Growth with GraphQL and ggplot2]()
* [Tornado.Cash Initial Distribution Analysis]()
* [Stable Coin Analysis]()

Data Sources: *Beaconscan, Numerai Tournament Data*

## Updates

*Gitcoin Grant Round 8*

Like everything else in the world, 2020 flipped our course development plans upside down.  Instead of building the course from the bottom up, we chose to repurpose and refactor our Medalla research into motivating case studies on how to perform data analysis on Ethereum 2.0 blockchain data.  The case studies walk through, in detail, how we performed the analysis that ultimately netted us a [bronze prize](https://blog.ethereum.org/2020/11/17/medalla-data-challenge-results/). We also included a tutorial on how to use R Shiny as an exploration tool for understanding the Numer.ai dApp's tournament data.

Change log
* Restructured the repository for clarity
* Added 3 case studies

*Gitcoin Grant Round 9*

More detail forthcoming!

Change log

* Updated course aesthatics
* Module 1 completed
* 5 New case studies
* First video lecture published to Youtube

## FAQ

*Do you all have experience in this stuff?*  
Why yes, we do! Omni Analytics Group is a team of PhD level statistical consultants that have been teaching and solving difficult data science problems for nearly a decade. We are passionate about data science and blockchain technologies. Just check out [our twitter](https://twitter.com/OmniAnalytics).

*Do I need any prior experience before taking this course?*  
Our intention is to start from the beginning and build up not only your data chops, but your statistical intuition and programming knowledge. At the end of these courses, you should be able to match a statistical technique to a blockchain data problem, write a basic script to analyze it and confidently search online for more advanced knowledge.

*What programming languages will the course focus on?*  
We'll initially focus on the statistical language R, but then expand to Python. As the course grows, we hope to include examples with contracts written in Solidity.

*Can I request a topic?*  
Sure! Once we flesh out the initial course material. If funding persists, we'd be more than happy to take suggestions on case studies or topics.
