# NewsNexus
## API Gateway with JWT Authentication

This project implements an API Gateway that uses JSON Web Tokens (JWT) for secure authentication and role-based access control. The gateway acts as a centralized entry point for multiple APIs, ensuring that only authenticated and authorized users can access specific resources.  

![Project Architecture](https://github.com/user-attachments/assets/165c1ad5-f253-46d1-a763-b2512affcd2a)

### Key Features:
- JWT-based Authentication: Users log in with a username and password to obtain a JWT, which is then used to access protected endpoints.
- Role-based Access Control (RBAC): Depending on the user's role (Admin, Premium User, or Regular User), the API Gateway routes requests to different endpoints: /news/admin, /news/premium and /news/user.

- Frontend:
    - Built using Streamlit, the frontend provides a login page where users authenticate, and based on their role, they can access and view relevant news content retrieved via API calls.

- Secure API Access:
    - Ensures that only valid tokens can access the API, adding an extra layer of security to prevent unauthorized access.

- This project demonstrates how to integrate JWT authentication in a microservice architecture, providing a secure way to manage and control API access.
- It also features a dashboard for Admin users to perform sentiment analysis and filter news based on different news channels providing the analysis based on positivity and negativity of the news providing a clear and user-friendly interface.

## NewsNexus Website
### Login page  

![login page](https://github.com/user-attachments/assets/dae03b78-4c76-4c6f-8a28-41491c4ca328)  

### Admin News Dashboard  

![admin news page](https://github.com/user-attachments/assets/b42e3663-34a1-4d35-9780-0e8c6a9a82a6)  

### Admin News Statistics

![admin news page](https://github.com/user-attachments/assets/e9f3eb0c-4364-4ec5-bd87-a175ddff6473)

