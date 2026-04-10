## Echo Server Requirements

### Backend API
- Implement a REST API that accepts a query parameter where the key is `name`.
- The API must respond with a JSON object containing the value of the passed parameter.
- **Response Format:** `{"name": "<VALUE_PASSED_IN_QUERY_PARAM>"}`

### Frontend UI
- Create a simple user interface with an input field to submit a name.
- Upon submission, call the backend API with the input value.
- Display the data returned from the API response to the user.
