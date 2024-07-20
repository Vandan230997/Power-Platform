<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Power Up Challenge: Paw & Heart Animal Rescue Charity</h1><br>

![image](https://github.com/user-attachments/assets/8fafbbaf-b1fd-48a2-9aba-64e32471167a) 

![image](https://github.com/user-attachments/assets/397305de-4623-4f06-99ad-53d69e9ca8e0)


<h2>Introduction</h2>
<p>Welcome to the repository for the Power Up Challenge! This project focuses on streamlining the operations of Paw & Heart, an animal rescue charity, using Microsoft Power Platform. The goal is to enhance record-keeping, support foster families, and provide insightful reports for the marketing team.</p>

<h2>Table of Contents</h2>
<ol>
    <li><a href="#dataverse">Dataverse</a></li>
    <li><a href="#powerapps-model-driven-app">PowerApps Model-Driven App</a></li>
    <li><a href="#powerapps-canvas-app">PowerApps Canvas App</a></li>
    <li><a href="#power-automate">Power Automate</a></li>
    <li><a href="#power-bi">Power BI</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
</ol>

<h2 id="dataverse">Dataverse</h2><br>

![image](https://github.com/user-attachments/assets/d405ea32-e20d-41e3-9a2f-51e1083c5aef)

<h3>Features and Functionalities</h3>

<ul>
    <li><strong>Centralized Data Management</strong>: Dataverse serves as the core data repository, storing all information related to animals, shelters, and foster families.</li>
    <li><strong>Tables and Entities</strong>:
        <ul>
            <li><strong>Animals Table</strong>: Contains fields such as Name, Type, Age, Picture, Medical Conditions, Status, Intake Date, and Shelter Location.</li>
            <li><strong>Shelters Table</strong>: Includes Shelter Name, Address, and Contact Info.</li>
            <li><strong>Foster Families Table</strong>: Captures Family Name, Contact Info, and Animal Association.</li>
        </ul>
    </li>
</ul>

<h3>Technical Details</h3>
<ul>
    <li><strong>Data Modeling</strong>: Created custom tables and relationships to ensure data integrity.</li>
    <li><strong>Data Security</strong>: Implemented role-based security to control access to sensitive data.</li>
    <li><strong>Data Loading</strong>: Imported initial data into Dataverse tables and ensured data consistency through validation rules.</li>
</ul>

<h2 id="powerapps-model-driven-app">PowerApps Model-Driven App</h2><br>

![image](https://github.com/user-attachments/assets/53c3d2dc-2f31-41fc-8412-5839717773ab)

![image](https://github.com/user-attachments/assets/2d630e0d-39bc-4ee7-b0ed-fca5ef340770)

<h3>Features and Functionalities</h3>
<ul>
    <li><strong>Animal Management</strong>: Allows shelter staff to manage detailed records of animals.</li>
    <li><strong>User Interface</strong>: Provides an intuitive and user-friendly interface for data entry and management.</li>
    <li><strong>Custom Views and Forms</strong>: Tailored views and forms for different user roles to enhance usability.</li>
</ul>

<h3>Technical Details</h3>
<ul>
    <li><strong>Forms and Views</strong>: Configured forms for data entry and custom views for displaying animal data.</li>
    <li><strong>Business Rules</strong>: Applied business rules to enforce data validation and ensure data integrity.</li>
    <li><strong>Role-Based Access Control</strong>: Set up security roles to manage access based on user roles.</li>
</ul>

<h2 id="powerapps-canvas-app">PowerApps Canvas App</h2><br>

![image](https://github.com/user-attachments/assets/ca9d9214-2965-4b1d-a762-f60ef1c48b65)

![image](https://github.com/user-attachments/assets/fa038ab0-380d-4e8d-b976-a8c526e004b3)


<h3>Features and Functionalities</h3>
<ul>
    <li><strong>Foster Family Support</strong>: Designed for foster families to view and claim animals for fostering.</li>
    <li><strong>Shelter Selection</strong>: Dropdown menu to select a local shelter.</li>
    <li><strong>Animal Listing</strong>: Displays a list of animals available for fostering with details such as name, type, age, picture, and medical conditions.</li>
    <li><strong>Foster Application</strong>: Allows users to select an animal, enter foster family information, and update the animal's status to "claimed for foster".</li>
</ul>

<h3>Technical Details</h3>
<ul>
    <li><strong>UI Design</strong>: Created a responsive and intuitive user interface using PowerFX formulas.</li>
    <li><strong>Data Integration</strong>: Connected to Dataverse for real-time data updates.</li>
    <li><strong>Logic Implementation</strong>: Used PowerFX for implementing complex logic and functionalities.</li>
</ul>

<h2 id="power-automate">Power Automate</h2><br>

![image](https://github.com/user-attachments/assets/f1b2076a-d995-4757-93ae-b4f2097860fc)

<h3>Features and Functionalities</h3>
<ul>
    <li><strong>Automated Notifications</strong>: Sends notification emails to foster families when an animal’s status changes to ‘claimed for foster’.</li>
    <li><strong>Workflow Automation</strong>: Streamlines communication and ensures timely updates to foster families.</li>
</ul>

<h3>Technical Details</h3>
<ul>
    <li><strong>Triggers and Actions</strong>: Configured flows to trigger on status change and send emails with animal details and pick-up arrangements.</li>
    <li><strong>Conditions</strong>: Implemented conditions to check for specific status changes.</li>
    <li><strong>Connectors</strong>: Utilized Dataverse and Outlook connectors for seamless integration.</li>
</ul>

<h2 id="power-bi">Power BI</h2><br>

![image](https://github.com/user-attachments/assets/ea527d3c-e721-488b-938f-cd5b4b1f25f1)


<h3>Features and Functionalities</h3>
<ul>
    <li><strong>Dashboard for Marketing Team</strong>: Provides visualizations to showcase shelter accomplishments and trends.</li>
    <li><strong>Latest News (Last Month)</strong>:
        <ul>
            <li>Number of Pets Arrived</li>
            <li>Number of Pets Fostered</li>
        </ul>
    </li>
    <li><strong>Trends (Last 3 Months)</strong>:
        <ul>
            <li>Most Rescued Type of Animal</li>
            <li>Most Fostered Type of Animal</li>
        </ul>
    </li>
</ul>

<h3>Technical Details</h3>
<ul>
    <li><strong>Data Transformation</strong>: Used Power Query for data cleaning and transformation.</li>
    <li><strong>DAX Calculations</strong>: Created measures and calculated columns using DAX.</li>
    <li><strong>Interactive Visualizations</strong>: Designed interactive charts and graphs for detailed insights.</li>
</ul>

<h2 id="acknowledgments">Acknowledgments</h2>
<p>A big thank you to the organizers of the Power Up cohort program for this incredible learning opportunity! This experience has significantly enhanced my skills with Microsoft Power Platform, and I am excited to apply these learnings in future projects.</p>

</body>
</html>
