# Expense Reimbursement System

## ***\*This project is for learning purposes only and does not include proper security or full functionality***

  This is an expense reimbursement system that includes a backend server, a frontend website, and a mobile application.
- project1.md contains the minimum requirements for the system.

### [Backend](https://github.com/wrkagel/Revature-Project-1-Backend)
- The backend is an express server that can take http requests and communicate with an Azure Cosmos DB and Azure storage container.
  - Handles all http requests from the frontend.
  - Uses multer to handle files sent over as multi-part form-data.
  - Uses express-winston to log all requests and errors.
  - Programmed in Typescript.
  - Tested using Jest.
- Repo: [https://github.com/wrkagel/Revature-Project-1-Backend](https://github.com/wrkagel/Revature-Project-1-Backend)

### [Browser Frontend](https://github.com/wrkagel/Revature-Project-1-Frontend)
- The frontend handles the user interaction, displays reimbursements, and sends the appropriate requests to the backend.
  - Single page application built using React.
  - Programmed in Typescript.
  - Uses fetch to make calls to the backend.
  - Allows employees to view their reimbursements and create new reimbursements.
  - Allows managers to also view reimbursements for employees they manage and approve, deny, or set back to pending any reimbursements that have not yet been paid.
  - Managers can also see statistics about reimbursements for the company and for the employees they manage.
  - User experience testing done by hand.
  - Some functional testing done using Jest and testing-library/react.
- Repo: [https://github.com/wrkagel/Revature-Project-1-Frontend](https://github.com/wrkagel/Revature-Project-1-Frontend)
- url: [https://white-meadow-0ceb2eb0f.azurestaticapps.net](https://white-meadow-0ceb2eb0f.azurestaticapps.net)

### [Mobile Application](https://github.com/wrkagel/Revature-Project-1-Mobile)
- A mobile application only for managers that allows them to view reimbursements for employees they manage and approve, deny, or set pending any reimbursements that are not already paid.
  - Built using Expo and React Native.
  - Programmed in Typescript.
  - User experience tested by hand using Expo development environment and Android Studio.
  - Some functional testing done using Jest and testing-library/react-native.
- Repo: [https://github.com/wrkagel/Revature-Project-1-Mobile](https://github.com/wrkagel/Revature-Project-1-Mobile)
- apk: download from this repo