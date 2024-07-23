# PayEm Home Assignment

## Welcome, Candidate!

Welcome to the PayEm Home Assignment! We're thrilled to have you here. This assignment is designed to give you a glimpse into the type of work you'll be tackling daily in this role, while also providing an opportunity for you to showcase your thought process and skill set. Rest assured, your solution will be used solely for evaluation purposes. We hope you find this experience both challenging and rewarding.

**Note:** For the backend portion of this assignment, please choose to implement either **Node.js** or **Python**, based on your preference.

## The Task

In this assignment, you will be working on an application that handles a request object. You can find an example of this request object in `db.py` or `db.js`.

Your task is to enhance the existing application with both front-end and back-end features:

### 1. Implement Filters Logic

- Implement the logic for filters based on the filters available in the UI.

### 2. Request Details Page

- When clicking on a request on the requests page, you will be directed to a new route.
- Implement a form to display all fields of the request object.
- Develop the front-end and back-end logic for approving or declining a request.

### 3. Extend Request Object

- Add a new field to the Request object named `type`.
- The `type` field can be one of the following:
  - **Purchase Request**
  - **Fund Request**
  - **Reimbursement Request**

## Current App State

Here's an overview of the current application state:

- **Create Requests Page**
  - Allows the creation of requests with a `/post` endpoint implemented.

- **Fetch Requests Page**
  - Fetches requests from the server with a `/get` endpoint implemented.

- **Backend**
  - Simulates a database using a file where all reads and writes are performed.

## Repository Structure

For your convenience, we have prepared a template to help you get started. The template includes the following folders:

- **frontend**
  - Contains the UI code, with routing to create requests, display requests, and view a single request.

- **backend-node**
  - Backend code implemented in Node.js. Includes endpoints for creating and fetching requests.

- **backend-python**
  - Backend code implemented in Python. Functionality is equivalent to the Node.js backend.

## What are we looking in the solution

- **Readability:** Ensure that your code is clean and well-documented, making it easy to understand and maintain.
- **Testing:** Consider writing tests (BE only) to verify the functionality of your implementation.
- **Error Handling:** Implement proper error handling to ensure the application runs smoothly under various conditions.
- **User Experience:** While styling is less emphasized, consider how the user experience can be enhanced through intuitive design and interactions.

---

**Good luck with your assignment!**

---

If you have any questions or need further clarification, feel free to reach out. We look forward to seeing your solution!
