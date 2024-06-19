# rn-assignment4-11124414


Project Overview

This assignment is part of the DCIT202 Mobile Application Development course. The task is to create a mobile application based on a provided UI mockup. The application comprises a login screen where users input their email and name, which are then displayed on a home screen. Additionally, the home screen includes sections that list "Popular Jobs" and "Featured Jobs," each showing a series of job cards.

Key Features

1. Login Screen:
   - User Input Fields: The login screen features two input fields where users can enter their email address and name.
   - Submit Button: There is a button that, when pressed, sends the entered information to the home screen. This action allows for the transition from the login screen to the home screen, demonstrating basic form handling and navigation.

2. Home Screen:
   - User Information Display: Upon successful login, the home screen prominently displays the email and name of the user as entered on the login screen. This is crucial for personalizing the user experience and demonstrating the data flow between screens.
   - Job Sections: The home screen is divided into two main sections, "Popular Jobs" and "Featured Jobs." Each section displays a collection of job cards, with a minimum of eight distinct job cards in each. This requirement ensures adequate representation of job listings and highlights different categories of jobs.

3. Job Cards:
   -Functional Component: The job cards are implemented as functional components that are used to populate the job sections on the home screen. These components are designed to accept properties (props) such as job title, company name, and location details. This modular approach facilitates the reuse of the job card component across different sections and screens.

4. Styling:
   - Adherence to Mockup: The application's styling closely adheres to the provided UI design mockup. This includes layout, colors, fonts, and spacing, ensuring a consistent and professional appearance that matches the expected design standards.

5.Custom Components:
   - Modular Design: Custom components are utilized throughout the application to promote consistency, reusability, and maintainability. This modular design approach enhances the organization of the code and simplifies future updates or feature additions.

Components Description

- LoginScreen: This component is responsible for handling user inputs for email and name. It provides the functionality to transition to the home screen upon form submission, passing the entered details.
- HomeScreen: This component receives the user's email and name from the login screen and displays them prominently. It also contains the sections for job cards, populating them with data.
- JobCard: A functional component used to render individual job cards. It accepts props for job details and displays them in a formatted manner. This component is used within the home screen's job sections to showcase various job listings.

#### Screenshots

- *Login Screen*:
    <img src="https://i.ibb.co/80JL3KR/Screenshot-20240619-205405.jpg" width="400" />
  - This screen captures the login interface, highlighting the input fields for email and name.

- Home Screen:
    <img src="https://i.ibb.co/58yrPBm/Screenshot-20240619-205508.jpg" width="400" />
  - This screen shows the home screen layout, including the user's email and name, as well as the job sections.

- Job Card:
  - This image illustrates a sample job card, displaying the job title, company name, and location details.

 
