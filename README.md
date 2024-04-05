# Food-Chat-Bot

Chatbot Working video :-https://drive.google.com/file/d/1ulzB5_5hX3PPiDBKKOMP9MgNhaiIAbs8/view?usp=sharing
Introduction:
Our food delivery chatbot project aimed to streamline the process of ordering food and tracking orders for customers through a static food website. Leveraging cutting-edge technologies such as Dialogueflow, FastAPI, and MySQL, we developed a robust system capable of handling user queries, processing orders, and maintaining order records efficiently.

Project Description:
The chatbot offers two primary functionalities:
1.New Order placement 
2.Order Tracking
Users interact with the chatbot through the static food website, where they can initiate conversations and provide order details. The chatbot seamlessly communicates with the backend server to process orders and retrieve order status information, ensuring a smooth and user-friendly experience.

Architecture Overview:
Our system architecture consists of three main components: Dialogueflow for natural language understanding, FastAPI for backend development, and MySQL for database management. Dialogueflow interprets user messages, extracting intents and entities to understand user requests. FastAPI handles incoming requests from the chatbot, communicates with the MySQL database to retrieve or update order information, and sends responses back to the chatbot.

Technologies Used:

Dialogueflow: Trained the chatbot to recognize user intents and entities, enabling it to understand and respond to various queries related to food ordering and order tracking.
FastAPI: Developed a RESTful API using FastAPI to create endpoints for handling incoming requests from the chatbot. FastAPI efficiently processes these requests, interacts with the MySQL database, and generates appropriate responses.
MySQL: Utilized MySQL as the backend database to store and manage order data. This included information such as order details, customer information, order status, and order history, ensuring data integrity and reliability.
Implementation Details:
During the implementation phase, we focused on creating a seamless communication flow between the chatbot, server, and database. We implemented custom logic to handle user requests, validate input data, and update order statuses based on real-time information. Challenges such as ensuring data consistency and optimizing response times were addressed through rigorous testing and optimization efforts.

Integration and Deployment:
To make the chatbot accessible online and secure the server, we deployed the system using ngrok, which provided a secure tunnel to expose our FastAPI server to the internet.


Conclusion:
Our food delivery chatbot project showcased the power of modern technologies in revolutionizing the food delivery industry. By leveraging Dialogueflow, FastAPI, and MySQL, we created a seamless and efficient ordering and tracking system that enhanced the user experience and improved operational efficiency. As we continue to innovate and iterate upon our solution, we remain committed to delivering cutting-edge solutions that drive value for customers and stakeholders alike.
