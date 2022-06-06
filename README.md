# CS569 Workshop 02
Update the last coding project with the following:
  
**Backend**   
- Create a `Login`, `Signup` routes to save the user credentials and send back JWT.
- Create a `Middleware` to be applied for editing an address.
  
**Frontend**   
- Create `Login`, `Signup` components and save the received JWT in a global state.
- Create an `Interceptor` to send the JWT when it's available.
- Create a `Guard` to be applied on edit address component so only logged in users can navigate to it, otherwise, they should be redirected to the `Login` component.
  
*Submission deadline 2:00 PM*

**Optional:** Optimize your list of addresses to use pagination.
