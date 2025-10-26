# FiitPeeps

🧩 Microservices Repository — Overview

This repository serves as a global hub for all the microservices developed as part of my distributed system architecture.
Each service is designed, built, and will be  deployed independently, following microservice principles such as modularity, scalability, and loose coupling.
The Deployment of these Microservices are still in under working condtion.

🚀 About This Global Repository

This repository acts as an index and documentation point for all the microservices that together form a complete application ecosystem.
Here, you’ll find links to each microservice’s dedicated GitHub repository along with brief descriptions of their functionality, technologies used, and deployment details.

🧱 Microservices List
#	Service Name	Description	Repository Link
1	Activity Service	Handles activity of the User and communicate with the AI-service to find AI-driven solution through Rabbit MQ.	🔗 [Activity Service Repo](https://github.com/praveendwievedi/ActivityService)

2	User Service	Manages user profiles, account settings, and user-related operations.	🔗[ User Service Repo](https://github.com/praveendwievedi/userService)

3	AI Service	Responsible for Providing AI driven solutions to the User.	🔗 [AI Service Repo](https://github.com/praveendwievedi/ai-service)

4	 Service resgistry Handles the main part of the Microservice where services will register and also find other services to communicate with.	🔗 [Eureka Server Repo](https://github.com/praveendwievedi/eureka_server)

5	Gateway / API Gateway	Acts as the single entry point for all client requests and routes them to respective microservices.	🔗 [Gateway Repo](https://github.com/praveendwievedi/Gateway)
⚙️ Tech Stack Overview

Backend: Spring Boot

Database: MongoDB / PostgreSQL (varies per service)

Communication: REST APIs / RestTemplate / Message Queues

Authentication: JWT / OAuth2

Version Control: Git & GitHub

🧭 Architecture Overview

Each microservice in this ecosystem:

Runs independently with its own database and server instance.

Communicates with other services via Web client and Rabbit MQ.

Can be deployed, scaled, and maintained separately.

A Gateway service (or API gateway) handles all client requests and routes them appropriately to ensure smooth interaction among the microservices.


🧑‍💻 Author

Praveen Kumar
Full Stack Developer | Spring Boot | Microservices Enthusiast
