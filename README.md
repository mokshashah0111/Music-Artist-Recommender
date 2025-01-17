# Music-Artist-Recommender

While developing a collaborative filtering-based recommendation system, I initially used Apache Spark's ALS (Alternating Least Squares) to handle a large-scale dataset with millions of user interactions. However, I encountered significant challenges with scalability—Spark's overhead and resource demands made the system inefficient for such massive data.

To overcome this, I switched to Python's Implicit library, which offers a highly optimized implementation of ALS. By leveraging efficient sparse matrix operations and streamlined matrix factorization, I achieved a 40% improvement in scalability compared to the previous Spark-based implementation.

I tested the refined model on the LastFM dataset, a real-world dataset featuring millions of user-artist interactions. The recommendation engine delivered highly accurate, personalized music artist suggestions, successfully balancing speed and precision even at scale.

This project demonstrates how identifying and addressing technical bottlenecks—like reduced scalability—can significantly improve system performance, making it both faster and more efficient for real-world applications.
While developing a collaborative filtering-based recommendation system, I initially used Apache Spark's ALS (Alternating Least Squares) to handle a large-scale dataset with millions of user interactions. However, I encountered significant challenges with scalability—Spark's overhead and resource demands made the system inefficient for such massive data. To overcome this, I switched to Python's Implicit library, which offers a highly optimized implementation of ALS. By leveraging efficient sparse matrix operations and streamlined matrix factorization, I achieved a 40% improvement in scalability compared to the previous Spark-based implementation. I tested the refined model on the LastFM dataset, a real-world dataset featuring millions of user-artist interactions. The recommendation engine delivered highly accurate, personalized music artist suggestions, successfully balancing speed and precision even at scale. This project demonstrates how identifying and addressing technical bottlenecks—like reduced scalability—can significantly improve system performance, making it both faster and more efficient for real-world applications.
Skills: Apache Spark · Python (Programming Language) · Machine Learning
