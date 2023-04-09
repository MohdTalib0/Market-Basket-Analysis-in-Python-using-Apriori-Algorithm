<h1>Market-Basket-Analysis-in-Python-using-Apriori-Algorithm</h1>

<h3>Name of Project-</h3>

Market Basket Analysis in Python using Apriori Algorithm

<h3>Description-</h3> <p>Whenever you visit a retail supermarket, you will find that baby diapers and wipes, bread and butter, pizza base and cheese, beer, and chips are positioned together in the store for sales. This is what market basket analysis is all about - analyzing the association among products bought together by customers. Market basket analysis is a versatile use case in the retail industry that helps cross-sell products in a physical outlet and also helps e-commerce businesses recommend products to customers based on product associations. Apriori and FP growth are the most popular machine learning algorithms used for association learning to perform market basket analysis.</p>

<h2>Apriori Algorithm</h2>
<p>Apriori algorithm is given by R. Agrawal and R. Srikant in 1994 for finding frequent itemsets in a dataset for boolean association rule. Name of the algorithm is Apriori because it uses prior knowledge of frequent itemset properties. We apply an iterative approach or level-wise search where k-frequent itemsets are used to find k+1 itemsets.

To improve the efficiency of level-wise generation of frequent itemsets, an important property is used called Apriori property which helps by reducing the search space.

Apriori Property –
All non-empty subset of frequent itemset must be frequent. The key concept of Apriori algorithm is its anti-monotonicity of support measure. Apriori assumes that

All subsets of a frequent itemset must be frequent(Apriori property).
If an itemset is infrequent, all its supersets will be infrequent.</p> 
<p>Source: GeeksforGeeks</p>
