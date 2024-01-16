# React App with TypeScript and Vite

This repository contains a React application developed with Typescript and Vite. The application is configured with MUI (Material-UI) for styling and components. This app consists of multiple tasks, each contributing to the overall functionality and user experience.

## Live Demo

You can view a live demo of the project [here](https://wbdv.netlify.app/login).

## Application Configuration

- The application is built using Typescript and Vite. For more information about Vite, refer to [Vite Documentation](https://vitejs.dev/guide/).

- Material-UI (MUI) is integrated into the application for a consistent and visually appealing design. If you're new to MUI, you can find more information in the [MUI Documentation](https://mui.com/material-ui/getting-started/overview/).

## First Page of the Application

- A form is implemented on the first page to collect user information, including Name, Phone number, and Email.

- User details are saved in the local storage upon form completion, and users are routed to the second page.

- If the user attempts to access the second page without providing necessary information, they will be redirected back to the first page with a message prompting them to enter their details.

## Second Page of the Application [Component 1]

- The second page fetches a list of JSON details from an API. The application uses the [MUI Data Grid](https://mui.com/x/react-data-grid/) to display the data in a table.

- The retrieved JSON data is converted into a model/interface using Typescript.

## Second Page of the Application [Component 2]

- This section includes a crucial component, which is a list of departments with expandable and collapsible sub-departments.

- The provided JSON (hardcoded in the application) is used to create this component.

- Users can expand or collapse sub-departments using icons on the right/left side of each department.

- Selection functionality allows users to choose departments or sub-departments. If a department is selected, all its sub-departments get selected in the UI. If all sub-departments of a department are selected, the parent department is also selected in the UI.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

```
git clone https://github.com/rahulkumar-yadav/react-form-app-project.git
```

2. Navigate to the project directory:

```
cd react-form-app-project
```

3. Install dependencies:

```
npm install
```

4. Run the development server:

```
npm run dev
```

This will start the development server, and you can view the webpage by accessing http://localhost:3000 in your browser.

Thank you for checking out my project!
