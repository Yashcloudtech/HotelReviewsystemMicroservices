# HotelReviewsystemMicroservices
Hotel review microservices, comprised of the Hotel Service, User Service, and Review Service, play a crucial role in managing and presenting hotel reviews in a distributed and scalable manner. These services work together to provide a seamless and efficient system for users to submit, retrieve, and interact with hotel reviews. Here is an overview of the purpose and functionality of each microservice:
•	Purpose and Functionality: -

1.	Hotel Service: The Hotel Service is responsible for managing information related to hotels. It acts as a central repository for hotel details, including their names, locations, and amenities.

	Functionality:
	Hotel Information: Stores and manages data about hotels, such as their names, locations, contact information, and descriptions.
	Hotel Search: Provides functionalities to search for hotels based on various criteria like location, price, rating, and more.

2.	User Service: The User Service manages user-related functionalities. It handles user registration, authentication, and profile management.

	Functionality:
	User Registration: Allows users to create accounts with unique usernames and passwords.
	Authentication: Provides user authentication services to ensure secure access to the system.
	Profile Management: Manages user profiles, including user preferences and personal information.
	Security: Ensures that user data and access are secure through authentication and authorization mechanisms.

3.	Review Service: The Review Service is responsible for collecting, storing, and retrieving hotel reviews submitted by users.

	Functionality:
	Review Submission: Allows users to submit reviews for hotels, including ratings, comments, and optional media attachments (e.g., photos).
	Review Retrieval: Provides APIs for retrieving reviews for specific hotels, users, or based on various criteria (e.g., top-rated reviews, most recent reviews).
	User Interaction: Enables users to like, comment on, or report reviews, promoting user engagement.
