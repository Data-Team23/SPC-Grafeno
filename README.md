# SPC-Grafeno



# Summary
* [Context](#contexto)
* [Team](#team)
* [Product Backlog](#product-backlog)
* [Sprint 01](#sprint-01)
* [Sprint 02](#sprint-02)
* [Sprint 03](#sprint-03)
* [Technologies Used](#technologies-used)
  
# Contexto
[SPC Grafeno](https://spcgrafeno.com.br/)
 You've been hired by a financial asset registrar to create innovative new financial products using machine learning techniques. The company will provide a diverse database, containing historical information on a variety of financial assets, transactions and market behaviors. Its challenge is to explore this database, identify patterns and opportunities, and develop one or more financial products that can add value to both the company and its customers.
 You will be expected to use machine learning techniques to predict trends, identify risks or even propose methods for qualifying assets. Your solution must be implemented in a proof of concept that demonstrates the viability of the proposed feasibility of the proposed product, including a description of the model used, justification for the techniques used and an evaluation of the model's performance.
 At the end, you must present your results in a report, accompanied by a presentation that explains clearly and objectively how your solution can be used by the company and what benefits it can bring to the registrar and its customers.

# Team

> _Product Owner_ - [Alan Morato](https://www.linkedin.com/in/alan-morato-37b214154/)

> _Scrum Master_ - [Lucas Emanoel](https://www.linkedin.com/in/lucas-emanoel-teixeira-engracio-da-silva-ab5611234/)

> _Dev. Team_ - [Ariane Cristina](https://www.linkedin.com/in/ariane-sousa77/)

> _Dev. Team_ - [Elizabeth Cristina Alves Leite](https://www.linkedin.com/in/elizabeth-cristina-alves-leite-176a9416a)

> _Dev. Team_ - [Tobias Fernandes Bezerra Sousa](https://www.linkedin.com/in/tobias-sousa-23bba822a)

> _Dev. Team_ - [Julia Quitério](https://www.linkedin.com/in/j%C3%BAlia-quit%C3%A9rio-934894205/)

> _Dev. Team_ - [Murilo Junior](https://www.linkedin.com/in/murilo-jos%C3%A9-de-brito-junior-32403b157/)

> _Dev. Team_ - [Silas Prado](https://www.linkedin.com/in/silasprd/)

# Product Backlog
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> <td><b>Sprint</b></td> </tr> <tr> <td>High</td> <td>Creation of initial dashboards for data analysis</td> <td>5</td> <td>1</td> </tr> <tr> <td>High</td> <td>Application of statistical analysis to data</td> <td>5</td> <td>1</td> </tr> <tr> <td>High</td> <td>Creation of user CRUD operations</td> <td>5</td> <td>1</td> </tr> <tr> <td>High</td> <td>Preparation of the database for model training</td> <td>10</td> <td>1</td> </tr> <tr> <td>High</td> <td>Implementation of user profile</td> <td>10</td> <td>1</td> </tr> <tr> <td>High</td> <td>Development of the machine learning model</td> <td>15</td> <td>2</td> </tr> <tr> <td>High</td> <td>Development of a place for dataset visualization</td> <td>5</td> <td>2</td> </tr> <tr> <td>Medium</td> <td>Development of health indicators for the machine learning model</td> <td>5</td> <td>3</td> </tr> <tr> <td>Medium</td> <td>User data exportation</td> <td>5</td> <td>3</td> </tr> </table> </div>

<h2>Non-Functional Requirements</h2>

<h3>Explicit Consent</h3>
<strong>Objective:</strong> Collect and record explicit user consent for the processing of their personal data.

<strong>Frontend</strong>
<ul>
    <li>Create a consent page/modal.</li>
    <li>Display clear information about what will be collected and how it will be used.</li>
    <li>Provide buttons for "Accept" or "Reject," or a checkbox.</li>
    <li>Store the user's response (Accept/Reject).</li>
    <li>Store User Response: Use Pinia (to manage state) or direct API calls with Axios to send the response to the backend.</li>
</ul>

<strong>Backend</strong>
<ul>
    <li>Create a model in Django to store consent data.</li>
    <li>API to save/query user consent.</li>
    <li>Secure consent data (encryption).</li>
    <li>Create a route for consent withdrawal and implement logic in the backend.</li>
    <li>Consent Data Security: Implement encryption using the <code>cryptography</code> library or Django encrypted fields. Enable user creation and interaction with the system using tokens.</li>
    <li>Route for Consent Withdrawal: Configure a route in DRF for users to revoke their consent, and manage the revocation logic in Django.</li>
</ul>

<h3>Right to Access and Correction</h3>
<strong>Objective:</strong> Allow users to access, correct, and update their personal data.

<strong>Frontend</strong>
<ul>
    <li>Create a profile page where users can view their data.</li>
    <li>Add buttons for "Edit Data" and "Save Changes."</li>
    <li>Interface to request data deletion or modification.</li>
    <li>API to Return Personal Data: Use Django Rest Framework to create endpoints that return user data.</li>
    <li>API for Data Updates: Implement an API with DRF to edit user data, validating the information before saving.</li>
    <li>Validations and Data Protection: Use Django Forms or DRF serializers for validations and secure routes with authentication (e.g., JWT).</li>
    <li>Change Notifications: Use Django Signals or Celery to send email notifications using libraries like <code>django-smtp</code> or SendGrid.</li>
</ul>

<strong>Backend</strong>
<ul>
    <li>Create an API to return user personal data.</li>
    <li>Create an API for updating personal data.</li>
    <li>Implement validations and protection for updated data.</li>
    <li>Notify users of changes via email or in-app notifications.</li>
</ul>

<h3>Data Portability</h3>
<strong>Objective:</strong> Allow users to export their personal data in a structured and machine-readable format.

<strong>Frontend</strong>
<ul>
    <li>Create an option in the profile for "Export My Data."</li>
    <li>Add a button to initiate the export.</li>
    <li>Display success/failure messages for the export process.</li>
</ul>

<strong>Backend</strong>
<ul>
    <li>Create an API to export data in formats like JSON/CSV.</li>
    <li>Secure the export process (authentication, temporary links).</li>
    <li>Implement logs to monitor data exports.</li>
    <li>API for Data Export: Create endpoints in Django Rest Framework to generate and provide data in JSON or CSV formats.</li>
    <li>Export Security: Implement authentication and authorization in DRF, generate temporary download links, and ensure secure data export.</li>
    <li>Export Logs: Use Django's logging framework to record data exports, monitoring access and activities.</li>
</ul>

  
# Backlog Sprint 01
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> </tr> <tr> <td>High</td> <td>Creation of initial dashboards for data analysis</td> <td>5</td> </tr> <tr> <td>High</td> <td>Application of statistical analysis to data</td> <td>5</td> </tr> <tr> <td>High</td> <td>Creation of user CRUD operations</td> <td>5</td> </tr> <tr> <td>High</td> <td>Preparation of the database for model training</td> <td>10</td> </tr> <tr> <td>High</td> <td>Implementation of user profile</td> <td>10</td> </tr> </table> </div>

# Backlog Sprint 02
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> </tr> <tr> <td>High</td> <td>Development of the machine learning model</td> <td>15</td> </tr> <tr> <td>High</td> <td>Development of a place for dataset visualization</td> <td>5</td> </tr> </table> </div>


# Backlog Sprint 03
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> </tr> <tr> <td>Medium</td> <td>Development of health indicators for the machine learning model</td> <td>5</td> </tr> <tr> <td>Medium</td> <td>User data exportation</td> <td>5</td> </tr> </table> </div>

# Technologies Used
- ``Python``
- ``JavaScript``
- ``Vue``
- ``HTML``
- ``CSS``
- ``Mongo DB``
- ``Postgres``

<h1>Sprint 01</h1>
<h2>User Stories</h2>
<div>
    <table border="1" cellpadding="5" cellspacing="0">
        <tr>
            <td><b>User Story</b></td>
            <td><b>Acceptance Criteria</b></td>
            <td><b>DoD</b></td>
            <td><b>Priority</b></td>
            <td><b>Backlog</b></td>
            <td><b>Estimate in days</b></td>
        </tr>
        <tr>
            <td>As a Front-end Developer, I want to create a user data editing interface so that administrators can easily update user information.</td>
            <td>- The interface should allow editing all user data fields.<br>- Validation for required fields must be implemented.<br>- The interface should be user-friendly and intuitive.</td>
            <td>- Editing interface tested and validated.<br>- Validation functionalities verified.<br>- Visual feedback for input errors implemented.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>As a Front-end Developer, I want to create an interface for registering new users in the system so that administrators can add new users intuitively and securely.</td>
            <td>- The registration interface must include all required fields.<br>- Data validation with user-friendly error messages.<br>- Registration confirmation at the end of the process.</td>
            <td>- Registration interface implemented and tested.<br>- All field validations functional.<br>- User experience tests completed.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>As a Back-end Developer, I want to implement the user deletion operation in the system so that profiles that should no longer exist in the system can be removed.</td>
            <td>- API must allow secure deletion of users.<br>- Deletion should be restricted to authorized users.<br>- Deletion must be confirmed before the final action.</td>
            <td>- User deletion endpoint implemented and documented.<br>- Permissions and restrictions tested.<br>- Deletion activity logs generated.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>As a Back-end Developer, I want to implement the user creation operation in the system so that users can be properly registered with all necessary validations, allowing new profiles to be added to the system.</td>
            <td>- Creation endpoint must validate all required fields.<br>- Should generate an error if data is missing or incorrect.<br>- Successful creation should be confirmed.</td>
            <td>- Creation endpoint implemented and documented.<br>- Validation tests completed.<br>- Creation logs recorded.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>As a Front-end Developer, I want to implement the user deletion functionality in the system so that administrators can remove user profiles that are no longer needed.</td>
            <td>- The deletion interface must display a confirmation before proceeding.<br>- Deletion should be restricted to administrators.<br>- Visual feedback after deletion with a success message.</td>
            <td>- Deletion functionality implemented in the interface.<br>- Confirmation and success messages displayed.<br>- Functionality and permission tests completed.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>As a Front-end Developer, I want to create an interface that lists all users in the system with filter and search functionalities so that administrators can view and manage existing user profiles.</td>
            <td>- The interface must list all registered users.<br>- Should allow filtering and searching users by attributes.<br>- Responsive and easy-to-navigate interface.</td>
            <td>- Listing and filtering functionality tested.<br>- User search functional.<br>- Responsive interface validated on different resolutions.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>As a Back-end Developer, I want to implement the user read operation so that it is possible to list, view, and obtain details of registered user profiles in the system.</td>
            <td>- Read endpoint must return a list of users with full details.<br>- Should allow searches by identifiers.<br>- Fast and consistent responses.</td>
            <td>- Read endpoint implemented and documented.<br>- Search and performance tests completed.<br>- Access and search logs enabled.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>As an SPC user, I want proper handling of my database so that the probability of success for my machine learning model increases.</td>
            <td>- The database must be optimized for storing large datasets.<br>- Data structure should meet model requirements.<br>- Easy data retrieval must be enabled.</td>
            <td>- Database optimized and reviewed.<br>- Validation of compatibility with the machine learning model.<br>- Retrieval and performance tests completed.</td>
            <td>High</td>
            <td>Preparation of the database for model training</td>
            <td>10</td>
        </tr>
        <tr>
            <td>As an SPC user, I want a dashboard for data analysis that includes client analysis so that I can understand the metrics of our transactions.</td>
            <td>- The dashboard must display transactional metrics in real-time.<br>- Should allow segmentation and detailed client analysis.<br>- Intuitive graphical visualizations.</td>
            <td>- Dashboard implemented and tested.<br>- Functional visualizations and filters.<br>- Accessible and optimized for performance.</td>
            <td>High</td>
            <td>Creation of initial dashboards for data analysis</td>
            <td>5</td>
        </tr>
    </table>
</div>


## Burndown

![image](https://github.com/user-attachments/assets/b0fe6471-e82f-4e0a-ae3c-f2b298fdefa7)



# Sprint 02
## User Stories
<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th><b>User Story</b></th>
    <th><b>Acceptance Criteria</b></th>
    <th><b>Definition of Done (DoD)</b></th>
    <th><b>Priority</b></th>
    <th><b>Estimate (days)</b></th>
  </tr>
  <tr>
    <td>As a backend engineer, I want to integrate the database with the application, so datasets are persistently stored and can be used by the machine learning model.</td>
    <td>
      - The database must allow efficient storage and querying of datasets.<br>
      - It must support large volumes of data.<br>
      - The integration must allow data updates and deletions.
    </td>
    <td>
      - The database connection is configured and functional.<br>
      - CRUD operations are tested and working.<br>
      - Database load tests are validated.
    </td>
    <td>High</td>
    <td>5</td>
  </tr>
  <tr>
    <td>As a machine learning engineer, I want to deploy the final version of the model into production, so it is available for use through the backend API.</td>
    <td>
      - The model must be converted to a format suitable for production (e.g., pickle, TensorFlow SavedModel).<br>
      - The model must load quickly.<br>
      - The production version must be monitored for performance.
    </td>
    <td>
      - The model is successfully running in a production environment.<br>
      - Performance is monitored and validated under various load conditions.<br>
      - Execution logs are configured to track failures.
    </td>
    <td>High</td>
    <td>4</td>
  </tr>
  <tr>
    <td>As a developer or machine learning engineer, I want to document the machine learning model and supporting software, so other team members and future developers can understand, maintain, and evolve the system with clarity.</td>
    <td>
      - The system architecture must be described with clear diagrams.<br>
      - Key components of the code must be documented.<br>
      - A detailed explanation of the ML model’s functioning must be provided.<br>
      - Instructions for installing, configuring, and using the software must be present.
    </td>
    <td>
      - Technical documentation is clear and standardized.<br>
      - Updated diagrams are included.<br>
      - All API endpoints are documented with examples.<br>
      - Documentation has been reviewed and is accessible in the project repository.
    </td>
    <td>High</td>
    <td>6</td>
  </tr>
  <tr>
    <td>As a machine learning engineer, I want to train and tune the machine learning model, so it can provide accurate predictions based on the provided datasets.</td>
    <td>
      - The model must achieve a minimum accuracy of X%.<br>
      - Overfitting and underfitting must be avoided.<br>
      - Training logs and performance metrics must be available.
    </td>
    <td>
      - The model has been tested and tuned in a development environment.<br>
      - Accuracy reached the defined threshold.<br>
      - The model results have been validated with test data.
    </td>
    <td>High</td>
    <td>7</td>
  </tr>
  <tr>
    <td>As a backend developer, I want to create the user table and the LGPD terms table in the database, so the system securely stores user information and term consent, meeting legal data protection requirements.</td>
    <td>
      - The User table must include essential fields with integrity constraints.<br>
      - The LGPD Terms table must support multiple versions of the term.<br>
      - The table relationships must ensure association with the latest term version.
    </td>
    <td>
      - The tables were created in the database with integrity constraints.<br>
      - Relationships between tables were implemented correctly.<br>
      - Structure documented and reviewed for LGPD compliance.
    </td>
    <td>High</td>
    <td>8</td>
  </tr>
  <tr>
    <td>As a frontend developer, I want to create a user interface to view datasets, so users can visualize, filter, and explore the loaded data.</td>
    <td>
      - The interface must list the available datasets.<br>
      - It must allow filtering and sorting of data.<br>
      - It must be responsive and easy to navigate.
    </td>
    <td>
      - Interface tested on different resolutions.<br>
      - Filtering and sorting functionalities validated.<br>
      - Visual feedback on errors or empty results.
    </td>
    <td>High</td>
    <td>3</td>
  </tr>
  <tr>
    <td>As a frontend developer, I want to create a user CRUD interface with LGPD compliance, so the system efficiently manages user data while meeting legal data protection requirements.</td>
    <td>
      - The registration interface must allow the addition of new users with mandatory fields.<br>
      - User data editing and querying must be allowed.<br>
      - User deletion must ensure anonymization according to LGPD.
    </td>
    <td>
      - CRUD view implemented.<br>
      - LGPD acceptance logic integrated.<br>
      - Functional tests performed, and backend routes documented.
    </td>
    <td>High</td>
    <td>2</td>
  </tr>
  <tr>
    <td>As a backend/frontend developer, I want to implement terms of service and revocation functionality in the system, so users can accept or revoke terms of use and consent in compliance with LGPD.</td>
    <td>
      - Clear interface to display and accept the term.<br>
      - History of accepted terms recorded.<br>
      - Visible interface for consent revocation.<br>
      - Administration management of terms available.
    </td>
    <td>
      - Acceptance and revocation functionalities implemented and tested.<br>
      - Complete documentation with examples and flow diagrams.<br>
      - Reviewed for LGPD compliance.
    </td>
    <td>High</td>
    <td>5</td>
  </tr>
  <tr>
    <td>As a machine learning engineer, I want to study and compare different machine learning algorithms, so I can select the model that offers the best performance and accuracy for the problem.</td>
    <td>
      - Test at least 3 different algorithms.<br>
      - Evaluate models using the same metrics.<br>
      - Select the model based on performance and complexity.
    </td>
    <td>
      - Comparative report of the models produced.<br>
      - Best model validated with test data.<br>
      - Experiment logs generated for each model.
    </td>
    <td>High</td>
    <td>4</td>
  </tr>
</table>


## Burndown

![image](https://github.com/user-attachments/assets/aea70066-2a2b-4a71-918a-91cdcd86d89e)

# Sprint 03
## User Stories
<table border="1" cellpadding="10" cellspacing="0">
  <thead>
    <tr>
      <th>ID</th>
      <th>User Story</th>
      <th>Acceptance Criteria</th>
      <th>Definition of Done (DoD)</th>
      <th>Priority</th>
      <th>Estimate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>As a backend engineer, I want to develop an API to expose the machine learning model so that the frontend can securely and efficiently consume the generated results.</td>
      <td>
        <ul>
          <li>The API must receive data in the correct format (e.g., JSON).</li>
          <li>Call the ML model and return results.</li>
          <li>Use basic authentication (e.g., OAuth 2.0).</li>
          <li>Implement error logs.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Documentation available (Swagger or similar).</li>
          <li>Unit and integration tests passing.</li>
          <li>Security validated.</li>
          <li>Performance tested to ensure acceptable response times.</li>
        </ul>
      </td>
      <td>High</td>
      <td>2d</td>
    </tr>
    <tr>
      <td>2</td>
      <td>As a user of SPC Grafeno, I want to visualize an interactive RFM chart to facilitate customer behavior analysis.</td>
      <td>
        <ul>
          <li>Interactive chart with R, F, and M axes.</li>
          <li>Filters by period and customer segment.</li>
          <li>Tooltip/hover with customer details.</li>
          <li>Data export to CSV or Excel.</li>
          <li>Responsive and fast, even with large data volumes.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Chart displayed correctly with interactivity.</li>
          <li>Filters and export working.</li>
          <li>Performance validated for large data volumes.</li>
          <li>Tested on different devices.</li>
        </ul>
      </td>
      <td>High</td>
      <td>10d</td>
    </tr>
    <tr>
      <td>3</td>
      <td>As a frontend developer, I want to consume the ML model API so that the user can submit datasets and receive results.</td>
      <td>
        <ul>
          <li>Data upload and submission to the API.</li>
          <li>Clear display of predictive results.</li>
          <li>User-friendly error messages.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>API connection validated.</li>
          <li>Interface tests conducted.</li>
          <li>Visual feedback consistent with the user experience.</li>
        </ul>
      </td>
      <td>High</td>
      <td>3d</td>
    </tr>
    <tr>
      <td>4</td>
      <td>As a data analyst, I want to improve the dashboard visualization to make it clearer and more understandable.</td>
      <td>
        <ul>
          <li>Dashboard data matches the backend.</li>
          <li>Design improvements applied.</li>
          <li>Changes to correct concepts.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Dashboard with implemented improvements.</li>
          <li>Updated data and linked to the system.</li>
          <li>Positive feedback from the team.</li>
        </ul>
      </td>
      <td>High</td>
      <td>5d</td>
    </tr>
    <tr>
      <td>5</td>
      <td>As a user, I want to view a table grouping customers with RFM metrics and clusters, to facilitate segmented analysis.</td>
      <td>
        <ul>
          <li>Table displays Name, RFM, and Clusters correctly.</li>
          <li>Visual grouping by cluster.</li>
          <li>Filters and sorting available.</li>
          <li>Responsive design aligned with the system style.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Table implemented and functional.</li>
          <li>Tested on different devices.</li>
          <li>Feedback from stakeholders implemented.</li>
        </ul>
      </td>
      <td>High</td>
      <td>2d</td>
    </tr>
    <tr>
      <td>6</td>
      <td>As a developer, I want to update the PUT user profile endpoint to log changes in LGPD terms and optional items.</td>
      <td>
        <ul>
          <li>Log with date and time for LGPD term updates.</li>
          <li>Record of optional items changed with new values.</li>
          <li>Persistence of the log in the LGPD table associated with the user.</li>
          <li>Accessibility for auditing by the administrator.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Endpoint updated with working logs.</li>
          <li>Complete change history available.</li>
          <li>Tests validated.</li>
        </ul>
      </td>
      <td>High</td>
      <td>3d</td>
    </tr>
    <tr>
      <td>7</td>
      <td>As a developer, I want to configure asynchronous tasks with Celery for LGPD data backups in MinIO, ensuring security and recovery.</td>
      <td>
        <ul>
          <li>Configure Celery task for periodic backups.</li>
          <li>Data export to MinIO with encryption.</li>
          <li>Error handling and retries.</li>
          <li>Failure notification to the administrator.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Backup in MinIO implemented and tested.</li>
          <li>Encrypted and versioned data.</li>
          <li>Complete documentation.</li>
        </ul>
      </td>
      <td>High</td>
      <td>3d</td>
    </tr>
    <tr>
      <td>8</td>
      <td>As a product manager, I want to improve customer clusters to prioritize those with higher conversion and retention potential.</td>
      <td>
        <ul>
          <li>Clusters created based on historical data.</li>
          <li>Priority labels for each cluster.</li>
          <li>Interpretable separation based on relevant variables.</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Clustering model implemented and trained.</li>
          <li>Documentation reviewed and accessible.</li>
          <li>Validation by stakeholders completed.</li>
        </ul>
      </td>
      <td>Medium</td>
      <td>5d</td>
    </tr>
  </tbody>
</table>


## Burndown

![Imagem do WhatsApp de 2024-11-24 à(s) 17 08 26_814a1312](https://github.com/user-attachments/assets/12ec6c79-b668-4f72-8dc5-c41515a91c02)


### Tools Used
Tool   | Description
--------- | ------
Notion | Brainstorming notes and feature definition  
Miro | Journey mapping, information flow, and feature prioritization  
Figma | Low and high-fidelity prototyping  
Hotjar | Usability testing and data analysis  
VSCode | Feature programming  
Postgres | Database creation and programming  
MongoDB | Database creation and programming  




## Data Model
### DER
![modelo_logico_api_spc](https://github.com/user-attachments/assets/7aef590f-efc9-4a80-ba2b-22118d91f195)


