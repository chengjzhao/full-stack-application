## Objective: Create a full-stack application with Angular on the front-end and Node.js on the back-end. The Angular application will read data from the back-end via REST API and then render the data on the page.

---

Tasks:
  - Create an Express server
    - Create an endpoint that will read the users-data.json file and use it as the API response
  - Create an Angular page
    - Retrieve data from Express server
      - Use @ngrx/effects to handle the side effect (API request)
      - Use @ngrx/store to store the API response
    - Render data on home page
      - Determine the statistics of the data and render it on the Overview section
      - Create a table using @angular/material and with the data in @ngrx/store
        - The table should have paginations and columns are sortable
      - Create filters for the table and add it above
  - Write unit tests for the front-end and back-end