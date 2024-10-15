# Book Recommendation System Using ML, Flask and AWS EC2
In an era of information abundance, where readers are inundated with countless book options, the need for personalized recommendations has never been more critical. Collaborative filtering, a prominent technique in recommendation systems, offers a powerful solution to this challenge. Collaborative filtering operates on the principle of collective intelligence, leveraging the wisdom of the crowd to make personalized recommendations. Unlike content-based approaches that analyse book characteristics, collaborative filtering focuses on user behaviour, specifically user-item interactions. It identifies patterns and similarities among users based on their past interactions with books to predict preferences and generate recommendations. In the digital age where access to vast libraries of books is at our fingertips, personalized book recommendation systems have become essential tools for assisting readers in discovering content aligned with their interests. This report provides an overview of a book recommendation system implemented using collaborative filtering, highlighting its methodology, performance evaluation, and potential applications.

The primary goal of the project was to build a recommendation system that provides personalized book recommendations to users. It employs collaborative filtering, content-based filtering, or a hybrid approach to recommend books based on user preferences, ratings, or other metadata.

![Screenshot 2024-10-15 111106](https://github.com/user-attachments/assets/3d80e8f3-987e-4d12-bc31-688f41648117)

![Screenshot 2024-10-15 111142](https://github.com/user-attachments/assets/d8867454-9692-452b-a7ea-a3a24380afa1)

# Recommendation system
A recommendation system is a subclass of Information filtering Systems that seeks to predict the rating or the preference a user might give to an item. In simple words, it is an algorithm that suggests relevant items to users. Eg: In the case of Netflix which movie to watch, In the case of e-commerce which product to buy, or in the case of kindle which book to read, etc.

![image](https://github.com/remona19/machine-learning-project---book-recommendation-system/assets/147992703/3ae7c1c8-c7d0-46ce-a55f-ab0cae67c435)

# Development Environment (PyCharm):
PyCharm was used to develop and test the system, enabling smooth debugging and handling the Python-based Flask application. Local tests and simulations of the recommendation engine were carried out in this IDE before deployment.

# Deployment Environment (AWS EC2):
AWS EC2 Instance: The Flask application was hosted on an EC2 instance, which provides scalable, cloud-based infrastructure. This allowed the recommendation system to be publicly accessible over the web.
Setup & Configuration: The EC2 instance was configured with the necessary environment (Python, Flask, and required libraries), and security settings were applied to allow HTTP/HTTPS traffic.
Database Integration: If required, AWS RDS or a similar cloud-based database service could be connected to the EC2 instance to manage and store book-related and user data at scale.

# Main Functionalities:

User Input: Users can search for books, rate them, or input preferences.

Recommendation Output: The system generates personalized book recommendations based on the input using the implemented algorithms.

User Management: Depending on the implementation, users could log in and store preferences, or interact with the system anonymously.

# Conclusion:
The Book Recommendation System demonstrates the integration of Flask for backend development and AWS EC2 for scalable deployment, providing personalized book recommendations based on user preferences. With its modular architecture, the system can be easily enhanced with more advanced algorithms and features. Future improvements could include refining the recommendation models, improving the user interface, and integrating real-time updates. This project exemplifies the use of web technologies and cloud infrastructure to deliver an efficient and user-friendly recommendation system.
