<!-- Headings -->
![markdown logo](https://digital.hbs.edu/platform-digit/wp-content/uploads/sites/2/2019/02/LC-Logo-Official-min.png)
# _Capstone Project- Lending Club_
# >*Introduction*
<hr>
<p1>
In the last few years, applying for different types of loans through online peer-to-peer lending platforms such as the<a href = "https://www.lendingclub.com/"> LendingClub</a> is raising. What is the LendingClub?</p1>

<br>
<br>
<p2>"LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform."
<a href ="https://en.wikipedia.org/wiki/LendingClub">wikipeida-lending club</a></p2>
<br>
<br>
<p3>
On the LendingClub platform, people invest on other people loan through an online secured system. On these types of platforms, in the most cases, the main criteria of giving loans to costumers is solely based on their credit scores, so that a customer with lower credit score (more risky) get higher rate and customer with higher credit score (less risky) get lower interest rate for their loan. Obviously, from the investor point of view, the loans with higher interest rate are more attractive due to their higher return of investment. However, it also has high risk of being not returned at all.
</p3>
<br>
<br>
<p4>
So, investing on "Bad loans" or charged-off, which means you loose your asset, is more worse than loosing an opportunity to gain more profit
</p4>
<br>
<br>
<p5>
The machine learning/deep learning model that could predict which of the high interest loans are more likely to be returned, would bring added value by minimizing the associated risks. Also, using other factors along with credit score may help us to identify the high risky loans and minimize the investors loss of money more accurately.
</p5>
<hr>
<h1>> Our goal</h1>
<p6>
In this capstone project, You will going to work on<a href="https://www.kaggle.com/wordsforthewise/lending-club"> LendingClub Dataset obtained from Kaggle</a> and the goal is to try find a better prediction model to prevent investing on '"bad loans". To do that, First, going to implement some data engineering and preprocessing on LendingClub dataset to prepare data for analysis and modeling. Second, you need to apply explanatory data analysis (EDA) to investigate the features. At the end, you use preprocessed data on LendingClub loans labeled on whether or not the borrower defaulted (charged-off) to develop a model and predict whether or not a borrower will pay back their loan. This way in the future when we get a new potential customer who assigned with higher interest loan, we can assess whether or not they are likely to pay back the loan.
</p6>
<hr>
<h1>>Dataset</h1>
<p7>
There are different datasets for LendingClub loans in Kaggle but some of them missed some features. Thus, I used <a href="https://www.kaggle.com/wordsforthewise/lending-club">LendigClub Dataset</a> possessing almost all features including FICO scores. This dataset contains more than several millions data and because, here, I only use a normal laptop to analyze and model this dataset, thus, I only selected the loans issued in 2018 (almost 0.5 million data) to reduce the processing time.
</p7>
<br>
<br>
<p8>
Moreover, some of the features in this dataset are only relevant after loans are issued and thus, not available at the moment of investing. For this reason, I used features list from <a href = "https://www.kaggle.com/wendykan/lending-club-loan-data">here</a> that are available and visible to investors before issuing a loan. To match this feature list to the main dataset, I did some simple and primary cleaning, whitespace removing, and spell corrections using dropping and “regular expression” technique. Also, it requires to check the unmatched features to see if some of them could be matched manually.
<p8>
<br>
<br>
<p9>
After the first step of preprocessing, we have 109 features and around 0.5 million of data. Below you can explore the features and their description. TRY IT!
<p9>
<br>
<br>
<p10>
Before starting explanatory data analysis, it is a good idea to do some data engineering and preprocessing to prepare data for analysis and modeling.
<p10>
<br>
<br>
<hr>
<h1>Data Set Link:</h1>
<p11><a href="https://www.kaggle.com/wordsforthewise/lending-club/download">Kagle: your home for data science</a><p11>




