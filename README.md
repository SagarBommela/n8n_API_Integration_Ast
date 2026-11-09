# Topic 1 – Setting Up Your API Development Environment

## Overview
In this topic, I learned how to set up the API development environment using Postman and n8n. I also created and tested my first GET API request using JSONPlaceholder.

## Tools Used
- **Postman** – To test API requests.
- **n8n** – To create and execute API workflows.


## API Details
- **API Name:** JSONPlaceholder
- **Method:** GET
- **Endpoint:** `https://jsonplaceholder.typicode.com/users`
- **Authentication:** None
- **Expected Status Code:** 200 OK

## Workflow Details

I created a simple n8n workflow with the following nodes:

1. **Manual Trigger** – Starts the workflow manually.
2. **HTTP Request** – Sends a GET request to the JSONPlaceholder API and retrieves user details.

## Workflow Execution
- Configured the HTTP Request node with the GET method.
- Added the JSONPlaceholder API endpoint.
- Executed the workflow successfully.
- Verified the JSON response containing 10 mock user records.
- Confirmed successful execution of both nodes.

## Workflow Structure

`Manual Trigger → HTTP Request (GET)`

## Learning Outcomes
- Understood the basics of REST APIs.
- Learned how to test GET requests using Postman.
- Learned how to configure the HTTP Request node in n8n.
- Understood how to retrieve and validate JSON responses.
- Successfully created and executed my first API integration workflow.

## Conclusion
Successfully completed Topic 1 by setting up the API development environment and creating my first GET API workflow using n8n.