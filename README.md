# Analysis-on-Best-Selling-Books-in-India
Abstract
Books can be sources of knowledge, entertainment or both. The demand for books is something that is still present in todays society. Similar to many other products, books are being increasingly sold on Ecommerce platforms. This project seeks to analyze data sourced from the Ecommerce site Paytm.com. The goal is to reveal trends and understand what factors contribute to the popularity of certain books. The data set utilized is a 1500 row csv file detailing the infromation from each sale. We found that price and genre were some of the main factors that determine book popularity.

##1. Introduction
This project is focused on analyzing the perceived value and popularity of books being sold online in India. This data set was taken as subset of a larger dataset that was created by extracting data from paytm.com, which is a leading eCommerce store in India. The initial steps will be to clean, wrangle and reshape the data to get all the columns we need to do our analysis.

To analyze the data a quantitative method will be utilized. For example, common statistical methods such as mean, median, frequency, and percentage will be employed to provide further insight into the data. This univariate analysis will be useful when analyzing single variables.

Also being used is inferential analysis. The main inerential tool being utlized will be correlation. Correlation describes the relationship between two variables. If a correlation is found, it means that there is a relationship among the variables. For example, taller people tend to have a higher weight. Of course, correlation does not imply causation but it can still be useful to identify certain correlations.

Combining univariate and bivariate analysis will provide the maximum depth of analysis. This will produce patterns and connections that can be followed to draw conclusions on the data. Creating visualizations will aid the human eye in recognizing these patterns and connections while also providing a convenient way to present the data.

##2. Problem Definition
What are the factors that make a book popular? The answer to this question is often based on personal opinion. Authors and booksellers everywhere would derive great benfit from this knowledge. This project seeks to solve this problem by taking a data driven approach to analyzing perceived value and popularity. Examining factors such as genre, author, price, and publisher may offer more insight. Visualizing the data allows patterns and trends to be more easily identified.

##3. Data Sources
(Describe the origin of the data sources. What is the format of the original data? How to access the data?)

The dataset utilized in this project was obtained from Kaggle in a csv format. There are 1500 rows and 23 columns but there are 3 fields (desc, specifications, and other_sellers) with dictionaires. This dataset is a subset of a larger dataset obtained from paytm.com. The columns included in the dataset are as follows: amtsave, brand, breadcrumbs, country, desc, discount, domain, gallery, image, insertedon, list_price, model, name, other_sellers, payment_methods_supported, productcode, selling_price, specifications, type, uniq_id, url, weight. In order to access the data, importing it from a csv will be the optimal solution.

