This respository contains the online appendix of "Improving Code Example Recommendations on Informal Documentation Using BERT and Query-Aware LSH: A Comparative Study".
For those interested in replicating this study, the data folder contains CSV files that incorporate the list of recommended code examples based on the query types: Natural Language-based and API Names-based. These results are based on the two implemented algorithms, namely Random Hyperplane-based (RH) LSH and Query Aware (QA) LSH. Inside the Result folder, there are the generated samples of code examples from the Query Aware approach.
In order to compare our work with baselines such as PostFinder and FaCoY, we have provided a set of recommended code examples for the 10 most popular Java libraries. These libraries include Jackson, SWT, MongoDB driver, Javax Servlet, JDBC API, JDT core, Apache Camel, Apache Wicket, Twitter4j, and Apache POI. We have utilized the input queries from the PostFinder work, which are accessible from the following link:

https://github.com/MDEGroup/PostFinder.



In addition, our Stack Overflow dataset has been uploaded to the following link. This dataset comprises Stack Overflow posts labeled as Java; however, some of them are also tagged with other programming languages. We have preprocessed the Stack Overflow posts by filtering posts that have Java labels, which reduced the number of posts from over 57 million to around 600K. 

<!--- This dataset could be helpful for researchers. --->

https://drive.google.com/file/d/19BBTy_57mgXe2zCxbV_SNwtC5PGVglY1/view?usp=drive_link





