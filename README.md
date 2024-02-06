# CityArt
CityArt is an application designed to showcase and manage monuments within a city. It provides users with a comprehensive platform to explore, learn about, and interact with various historical landmarks. Here's an overview of its key features and functionality:

## Key Features
- Map Display: App offers an interactive map interface that displays the locations of all monuments within the city. Users can easily navigate the map to explore different areas and discover nearby landmarks.

- Monument Details: Users can select individual monuments on the map to view detailed information about each landmark. This includes the monument's name, location, type, curator, author, year of production, material, state, description, and other relevant details.

- Search Functionality: The app includes a search feature that allows users to search for specific monuments by name or location. This enables quick and easy access to information about particular landmarks of interest.

- Damage Reporting: Users have the ability to report any damage or issues they encounter with a monument directly through the app. This feature facilitates community engagement and helps authorities prioritize maintenance and restoration efforts.

- Status Management: Administrators and authorized users can manage the status of monuments within the app. This includes updating the state of a monument (e.g., "In Good Condition", "Under Repair", "Damaged") to reflect its current condition accurately.

- Admin Tools: Admin users have access to additional tools and functionalities for managing monuments. This includes the ability to add new monuments, delete existing ones, and modify monument information as needed.

## User
![User](https://github.com/JanPeregrim/CityArt/assets/130740859/55efe913-946b-4ec9-a86a-85e9610cac0d)

## Admin
![Admin](https://github.com/JanPeregrim/CityArt/assets/130740859/08a9ab05-951c-40f4-a274-d0ae0a78c056)

## Curator
![Curator](https://github.com/JanPeregrim/CityArt/assets/130740859/8499947c-2214-49a3-915f-55daa753cf73)





## Technologies Used
- Backend: The backend of app is built using Python and the Flask framework. It utilizes Azure App Services for hosting and Azure Storage Account for storing monument data.

- Frontend: The frontend of app is developed using the Flutter framework, allowing for cross-platform compatibility across iOS, Android, and web browsers. Android Studio is used as the primary IDE for Flutter development.

- Database: Monument data is stored in a Microsoft Azure Storage Account, providing scalable and reliable storage solutions. Microsoft Azure Storage Explorer is used for managing and interacting with the database.

- Version Control and CI/CD: The project is managed using Azure DevOps, which includes version control, issue tracking, and CI/CD pipelines for automated build and deployment processes.

## Installation and Deployment
To deploy app:

- Backend Setup: Run the backend pipeline in Azure DevOps to deploy the backend server and API.

- Frontend Setup: Run the frontend pipeline in Azure DevOps to build the Flutter application for deployment on iOS, Android, or web browsers.

- Database Configuration: Use Microsoft Azure Storage Explorer to configure and manage the monument database stored in Azure Storage Account.