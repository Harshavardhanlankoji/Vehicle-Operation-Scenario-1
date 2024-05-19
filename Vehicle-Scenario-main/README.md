
## Vehicle-Scenario CRUD App

This project is a responsive and interactive CRUD (Create, Read, Update, Delete) application designed to manage vehicle scenarios. Built using modern web technologies like React, React Router v6, React Hooks, Context API, and CSS, this app allows users to move vehicles under specified conditions. Users can create, update, and delete both scenarios and vehicles, with a user-friendly interface that adapts to various screen sizes.

---

### Features

1. Vehicle Movement:
   - Control the movement of vehicles in specified directions.
   - Set and adjust speeds for each vehicle.

2. CRUD Functionality:
   - Create: Add new scenarios and vehicles.
   - Read: View existing scenarios and the details of each vehicle.
   - Update: Modify the properties of scenarios and vehicles.
   - Delete: Remove unwanted scenarios and vehicles.

3. Responsive Design:
   - Optimized for different screen sizes to ensure a seamless experience on desktops, tablets, and mobile devices.

---

### Setup and Installation

Follow these steps to set up and run the project on your local machine:

1. Clone the Repository:
   - Open your terminal or command prompt.
   - Run the following command to clone the repository:
     ```sh
     git clone 
     ```
   - Alternatively, download the zip file from the repository and extract it to your preferred directory.

2. Navigate to the Project Directory:
   - Change your working directory to the project folder:
     ```sh
     cd /Vehicle-Scenario-main/src
     ```

3. Install Dependencies:
   - Ensure you have Node.js and npm installed on your machine.
   - Run the following command to install the necessary dependencies:
     ```sh
     npm install
     ```

4. Run the App:
   - Start the development server with the following command:
     ```sh
     npm start
     ```
   - This command will open the app in your default web browser at `http://localhost:3000`.

---

### Detailed Steps for Usage

1. Creating a Scenario:
   - Navigate to the "Create Scenario" section.
   - Fill in the required details such as scenario name and description.
   - Click the "Save" button to add the new scenario to the list.

2. Creating a Vehicle:
   - Within a scenario, go to the "Add Vehicle" section.
   - Enter vehicle details such as name, type, direction, and speed.
   - Click "Save" to add the vehicle.

3. Updating a Scenario or Vehicle:
   - Select the scenario or vehicle you want to update.
   - Modify the necessary fields.
   - Click "Update" to save the changes.

4. Deleting a Scenario or Vehicle:
   - Select the scenario or vehicle to be deleted.
   - Click the "Delete" button.
   - Confirm the deletion when prompted.

5. Viewing and Interacting:
   - View the list of scenarios and vehicles on the main dashboard.
   - Click on any scenario to view its details and the vehicles it contains.
   - Use the controls provided to simulate vehicle movements.

---

### Technology Stack

- **React:** A JavaScript library for building user interfaces.
- **React Router v6:** For handling navigation and routing within the app.
- **React Hooks:** To manage state and lifecycle methods in functional components.
- **Context API:** For state management across the application.
- **CSS:** For styling the application and ensuring responsive design.

---

This detailed guide should help users understand the functionalities of the Vehicle-Scenario CRUD app and provide clear instructions on setting up and using the app efficiently.