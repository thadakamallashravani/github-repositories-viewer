GitHub Repositories Viewer
This web application allows users to explore the public GitHub repositories associated with a specific GitHub username. Users can search for a GitHub username, view the repositories, and even clone them using the provided "Git Clone" button.

Table of Contents
Features
References & Requirements
Usage
Technologies Used
Getting Started
Contributing
License
Features
Search for a GitHub username.
View a list of public repositories associated with the entered username.
Clone repositories directly from the application.
Display the total number of repositories.
References & Requirements
API Documentation: GitHub REST API Reference
Repository Topic Image: GitHub Repository Topic Image
Pagination: Server-side pagination with a default of 10 repositories per page. Users can choose up to 100 repositories per page.
Loader: Displays loaders during API calls.
Search Bar: Optional search bar to filter repositories.
Usage
Open the index.html file in a web browser.
Enter a valid GitHub username in the provided input field.
Click the "Search" button to retrieve repositories.
View the list of public repositories associated with the entered GitHub username.
Optionally, click the "Git Clone" button next to each repository to clone it.
The total number of repositories is displayed above the list.
Technologies Used
HTML
CSS
JavaScript
Bootstrap (optional)
GitHub REST API
Getting Started
To get a local copy up and running, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/NikhilaKasam/github-repositories-viewer.git
Open the project folder:

bash
Copy code
cd github-repositories-viewer
Open the index.html file in your preferred web browser.

Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
