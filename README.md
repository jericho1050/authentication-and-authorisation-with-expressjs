# User authentication system with a twist

Implementing the delete user functionality with proper authentication and authorization is a **good idea**. However, allowing everyone to delete each other without proper authorization is a **bad idea**.

Explanation:

- **Authentication**: This is the process of verifying the identity of a user. It ensures that the user is who they claim to be. In this context, this is done using JWT tokens, which are issued upon successful login and verified in subsequent requests.

- **Authorization**: This is the process of determining whether an authenticated user has the necessary permissions to perform a specific action. It ensures that the user has the right to access certain resources or perform certain operations. In this context, this is managed by checking the user's role (e.g., user, admin) and ensuring they have the appropriate permissions.
  
**In short**:

- Authentication: "Who are you?"
- Authorization: "What are you allowed to do?"

## Example

### Authentication

![Authentication Diagram](/web-front-end/static/diagram1.png)

### Authorization

![Authentication Diagram](/web-front-end/static/diagram2.png)

