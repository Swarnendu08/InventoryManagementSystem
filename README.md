<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
</head>
<body>
	<h1>Abstraction</h1>
	<p>Inventory management system is an application which is helpful for management operators, where the management team keeps the records of purchase and the details of the product. Inventory Management Systems make it simple to locate and analyse inventory information in real-time with a simple database search. This inventory management system is to eliminate paperwork, human faults, unwanted damages, manual delay and speed up process. Educational institutes need to have inventories to maintain the data of various equipment. Therefore, the task of inventory management is to hold the details of inventories through <span class="keywords">QR code</span> which helps to obtain the details regarding a product instantly avoiding paperwork. This paper presents a report for assembling a real-world application which helps the operators to manage the inventories smoothly. It is proposed to use an inventory management software to decrease paper burden and to apply an agent system for automation of inventory management using QR code. This system can be used to store the details of the inventory based on the purchasing details, and this is one integrated system that contains both the user component (used by management operators, inventory managers) and the admin component (used by the administrators for performing admin level function such as adding new item to the inventory) etc. The web application is going to be made up of two parts: The frontend is developed using HTML5, CSS5 and JavaScript and the Backend from PHP and SQL server Database.</p>
	<p><span class="keywords">Keywords</span> – Inventory Management System, QR Code, Tracking Inventory, Time Saving, Database, Web Application, Update, Minimize the errors.</p>
</body>
</html>
<hr>

<h1>CONTENTS</h1>

<ol>
    <li>
        <h3><a href="#introduction">INTRODUCTION</a></h3>
        <ul>
            <li><a href="#about-project">1.1 About Project</a></li>
            <li><a href="#project-plan">1.2 Project Plan</a></li>
            <li><a href="#requirements_specification_document">1.3 Requirements Specification Document</a></li>
            <li><a href="#functional_requirement">1.4 Functional Requirement</a></li>
            <li>
                <a href="#non_functional_requirements">1.5 Non-Functional Requirements</a>
                <ul>
                    <li><a href="#analysis_design_data_requirements">1.5.1 Analysis, Design & Data Requirements</a></li>
                    <li><a href="#constraints">1.5.2 Constraints</a></li>
                    <li><a href="#guidelines">1.5.3 Guidelines</a></li>
                </ul>
            </li>
        </ul>
    </li>
    <li>
        <h3><a href="#problem_statement">PROBLEM STATEMENT</a></h3>
        <ul>
            <li><a href="#existing_system">2.1 Existing System</a>
                <ul>
                    <li><a href="#disadvantages">2.1.1 Disadvantages</a></li>
                </ul>
            </li>
            <li><a href="#proposed_system">2.2 Proposed System</a>
                <ul>
                    <li><a href="#advantages">2.2.1 Advantages</a></li>
                </ul>
            </li>
        </ul>
    </li>
    <li>
        <h3><a href="#literature_review">LITERATURE REVIEW</a></h3>
        <ul>
            <li><a href="#manual_counting">3.1 Manual Counting</a></li>
            <li><a href="#punch_card_system">3.2 Punch Card System</a></li>
            <li><a href="#the_modern_bar_code">3.3 The Modern Bar Code</a></li>
        </ul>
    </li>
    <li>
        <h3><a href="#project_design">PROJECT DESIGN</a></h3>
        <ul>
            <li><a href="#software_requirements">4.1 Software Requirements</a></li>
            <li><a href="#database_design">4.2 Database Design</a>
                <ul>
                    <li><a href="#database_tables">4.2.1 Database Tables</a></li>
                </ul>
            </li>
            <li><a href="#system_design">4.3 System Design</a>
                <ul>
                    <li><a href="#users">4.3.1 Users</a></li>
                    <li><a href="#admin_user_functions">4.3.2 Admin User Functions</a></li>
                    <li><a href="#normal_user_functions">4.3.3 Normal User Functions</a></li>
                </ul>
            </li>
            <li><a href="#uml_diagrams">4.4 UML Diagrams</a>
                <ul>
                    <li><a href="#uml_unified_modelling_language">4.4.1 UML (UNIFIED MODELLING LANGUAGE)</a></li>
                    <li><a href="#visualizing">4.4.2 Visualizing:</a></li>
                    <li><a href="#specifying">4.4.3 Specifying</a></li>
                    <li><a href="#documenting">4.4.4 Documenting</a></li>
                    <li><a href="#diagrams_in_uml">4.4.5 Diagrams in UML</a></li>
                </ul>
            </li>
            <li><a href="#modules">4.5 Modules</a>
                <ul>
                    <li><a href="#valid_users_module">4.5.1 Valid Users Module</a></li>
                    <li><a href="#inventory_module">4.5.2 Inventory Module</a></li>
                </ul>
            </li>
            <li><a href="#feasibility_analysis">4.6 Feasibility Analysis</a>
                <ul>
                    <li><a href="#technical_feasibility">4.6.1 Technical Feasibility</a></li>
                    <li><a href="#financial_feasibility">4.6.2 Financial Feasibility</a></li>
                    <li><a href="#implementation_plan">4.6.3 Implementation Plan</a></li>
                </ul>
            </li>
            <li><a href="#software_requirement_analysis">4.7 SOFTWARE REQUIREMENT ANALYSIS</a>
                <ul>
                    <li><a href="#what_is_srs">4.7.1 What is SRS?</a></li>
                    <li><a href="#role_of_srs">4.7.2 Role of SRS</a></li>
                    <li><a href="#purpose">4.7.3 Purpose</a></li>
                    <li><a href="#scope">4.7.4 SCOPE</a></li>
                </ul>
            </li>
            <li><a href="#">4.8 DIAGRAMS</a>
                <ul>
                    <li><a href="#4.8.1_class_diagram">4.8.1 Class Diagram</a></li>
                    <li><a href="#4.8.2_use_case_diagram">4.8.2 Use case Diagram</a></li>
                    <li><a href="#4.8.3_sequence_diagram">4.8.3 Sequence Diagram</a></li>
                    <li><a href="#4.8.4_activity_diagram">4.8.4 Activity Diagram</a></li>
                    <li><a href="#4.8.5_er_diagram">4.8.5 ER Diagram</a></li>
                    <li><a href="#4.8.6_database_schema">4.8.6 Database Schema</a></li>
                </ul>
            </li>
        </ul>
    </li>
    <li>
        <h3><a href="#conclusion">CONCLUSION</a></h3>
    </li>
    <li>
        <h3><a href="#references">REFERENCES</a></h3>
    </li>
</ol>

<hr>

<h2 id="introduction">1. INTRODUCTION</h2>
<h3 id="about-project">1.1 About Project</h3>
<p>
    The project Inventory Management System is a web-based application designed on HTML5, CSS3, JavaScript, PHP and SQL using Visual Studio Software. The main objective of the project is to develop an Inventory Management System Model web application in which all the information regarding the equipment of each department will be presented. It is an internet-based web application which has an admin to manage the inventory and maintenance of the inventory system. This web application is based on the management of inventory of departments. The main objective of this project is to manage equipment details. This project includes various modules and features to add, edit, view and delete stock-management-related things in the system database. The application contains general organization profile, Purchase details, product details. There is a provision of updating the inventory also. Each new equipment is created and entitled with the name and the entry date of that item, and it can also be updated any time when required as per the requirement or damaged in case. Here the login page is created to protect the management of the stock of the organization to prevent it from the security threats and misuse of the inventory.
</p>
<p>
    Inventory Control Management System is necessary for the Institute for hasslefree record keeping and retrieval of information of department equipment. The process of maintaining the information of the inventories at one stretch is very difficult. Information required should be available on demand. For this purpose, the inventory control management database is necessary. The inventory control management database can maintain proper management of a variety of items.
</p>
<p>
    Users are provided with graphical GUI for accessing inventory information by scanning QR code. This application works on a centralized database. Existing system works on manual processes where record maintenance is not an easy task. In this method it is hard to retrieve older records and there are chances of losing data. Using this new system can solve all the above problems and provide secure and user-friendly applications.
</p>


<h2 id="project-plan">1.2 Project Plan</h2>
<p>
It has been decided to use good Software engineering principles in the
development of the web application since the Institution has quite
a large inventory management inefficiency and was aiming to manage the
inventories digitally soon. So, the following Project Plan has been drawn up:
<ol>
<li>We will interact with the institution management users to get the Requirements. As a part of this the Requirements Specification Document will be created.</li>
<li>The requirements Specifications document will contain the Analysis & Design of the system & UML will be used as the modelling language to express the Analysis & Design of the System. According to Grady Booch et al, in The Unified Modelling Language User Guide, “The Unified Modelling Language (UML) is a graphical language for visualizing, specifying, constructing, and documenting the artifacts of a software-intensive system. The UML gives you a standard way to write a system's blueprints, covering conceptual things, such as business processes and system functions, as well as concrete things, such as classes written in a specific programming language, database schemas, and reusable software components”.</li>
<li>The Analysis, Design, Implementation & testing of the System itself will be broadly based on the Rational Unified Software Development process. According to Ivar Jacobson et al, in The Unified Software Development Process (The Addison- Wesley Object Technology Series), the Unified Software Development Process contains Inception, Elaboration, Construction & Transition as the main Phases, which contain further cycles & iterations. This process will be followed to Inventory Management System to produce an incremental cycle, which will deliver milestones like the Requirements Specification Document etc., at the end of each of the iterations, Phases or cycles.</li>
<li> The Architecture & Technologies will be decided as a part of the Analysis of the requirements.</li>
<li> Once the Design is ready the Implementation & Testing strategy of the system will commence. Each will be independent of the other. The implementation of the system itself will be broken down into sub-systems following the Software Engineering principles for the development of robust software.</li>
<li>Once the implementation is ready, the System testing will take place. If the system is judged to be stable, then Acceptance testing by the Users will take place & once the Users are satisfied the System will be rolled out to the Users & they will be trained on how to use it for an initial period.</li>
</ol>
</p>
<p>
    The following chapters contain an account of how the Technology & architecture for the system were chosen.
</p>

<h2 id="requirements_specification_document">1.3 Requirements Specification Document</h2>
<p>
    The requirement specification document is produced at the end of Analysis of the system. This document is a very comprehensive document & contains all the User requirements & Analysis diagrams.
</p>
<p>
    The Requirements are broadly divided into two groups:
</p>
<ol>
    <li>Functional requirements</li>
    <li>Non-functional requirements</li>
</ol>

<h2 id="functional_requirement">1.4 Functional Requirement</h2>
<p>
    The main purpose of functional requirements within the requirementspecification document is to define all the activities or operations that take place in the system. These are derived through interactions with the users of the system. Since the Requirements Specification is a comprehensive document & contains a lot of data, it has been broken down into different Chapters in this report. The depiction of the Design of the System in UML is presented in a separate chapter. But the general Functional Requirements arrived at the end of the interaction with the Users are listed below. A more detailed discussion is presented in the Chapters, which talk about the analysis & design of the system.
</p>

<ol>
    <li>The System holds details of the all the users who are using the web application.</li>
    <li>It allows admin to register and delete users.</li>
    <li>It holds the details of all items to be recorded in the applicable departments that will use the application.</li>
    <li>The system allows the inventory manager to log into the system and enter their inwards entries related to the equipment.</li>
    <li>The inventory manager can customize the fields to be filled for each equipment, corresponding to the need of their department.</li>
    <li>It also allows them to view the list of all inward entries.</li>
    <li>The system allows the inventory manager to log into the system and update applicable fields for the inward entries.</li>
    <li>Valid users (including admins) can scan the QR code using their smartphone (either from the web application or any scanner software), log in and view the details of corresponding equipment.</li>
</ol>

<h2 id="non_functional_requirements">1.5 Non-Functional Requirements</h2>
<p>
    The non-functional requirements consist of:
</p>
<ol>
  <li>Analysis, Design &amp; Data requirements (Use-case diagrams, textual analysis,
  sequence diagrams, data dictionary etc.)</li>
  <li>Constraints</li>
  <li>Guidelines</li>
</ol>

<h3 id="analysis_design_data_requirements">1.5.1 Analysis, Design & Data Requirements</h3>
<p>
    The use case diagrams, textual analysis, and sequence diagrams fall into this category. Since each category above is of considerable importance, they have been dealt with in separate chapters. An outline is only included here.
</p>
<p>
    The Analysis &amp; Design phases of the system yield Use Case diagrams, textual analysis, Sequence Diagrams, and Class diagrams.
</p>

<h3 id="constraints">1.5.2 Constraints</h3>
<p>These are the requirements that are not directly related to the functionality of
the system. These should be considered as mandatory when the system is
developed. The following Constraints were arrived at for the system:</p>
<ol>
    <li>For entering the system the admin should register user email id and the user should be able use login for gaining access to the system.</li>
    <li>The system should be easy to understand and organized in a structured way. The users should also receive feedback about any errors that occur.</li>
    <li>There should be minimal limitation about the hardware platform that is to be used to run the system.</li>
    <li>Data integrity should be maintained if an error occurs or the whole system comes down.</li>
</ol>

<h3 id="guidelines">1.5.3 Guidelines</h3>
<p>We have discussed mandatory requirements in the previous section. The
requirements in this section should be taken as suggestions & they should be
thought of as recommendations to further enhance the usability of the system.</p>
<ol>
    <li>The system should display a user-friendly menu for use.</li>
    <li>The system should display department name and details of the equipment scanned.</li>
    <li>Services of the system should be available 24 hours a day.</li>
    <li>The system should be designed in such a way that it is easy to enhance it with more functionality. It should be scalable & easily maintainable.</li>
</ol>

<hr>

<h1 id="problem_statement">2. PROBLEM STATEMENT</h1>
<p>
    To develop a web application to manage and record of product purchased by the Institution and retrieve them using QR Code.
</p>
<h2 id="existing_system">2.1 Existing System</h2>
<p>
    Current system is a manual one in which users are maintaining book register records to store details like item name, bill number, date of purchase, quantity purchased, cost of purchase, remarks.
</p>
<h3 id="disadvantages">2.1.1 Disadvantages</h3>
<p>
    The following are the disadvantages of current system:
</p>
<ol>
    <li>It is difficult to maintain important information in books.</li>
    <li>More manual hours need to generate required reports.</li>
    <li>It is inefficient and to manage data in a way which needs much space, cost, paper.</li>
    <li>It takes time and effort to manually search for individual equipment on demand.</li>
    <li>Books are susceptible to damage and data could be lost and manual hours wasted.</li>
</ol>
<h2 id="proposed_system">2.2 Proposed System</h2>
<p>
    Proposed system is a software application which avoids more manual hours that need to spend in record keeping and generating reports. This application keeps the data in a centralized way which is available to valid users simultaneously. It is very easy to manage data in database. No specific training is required for the employees to use this application. They can easily use the tool that decreases manual hours spending for normal things and hence increases the performance. As the data is centralized it is very easy to maintain the details of the various of all applicable departments.
</p>
<h3 id="advantages">2.2.1 Advantages</h3>
<ol>
    <li>Easy to add, update and view entries.</li>
    <li>Can generate details of the required item easily using a QR code scanner software available in smartphones.</li>
    <li>Easy to manage data in a secure manner.</li>
    <li>Easy to use GUI that does not require specific training.</li>
</ol>

<hr>

<h1 id="literature_review">3. LITERATURE REVIEW</h1>
<p>
    Inventory management is an integral part of any organization. Whenever an organization purchases some equipment, its information has to be kept as a record for the future use. Organizations always try to manage their inventory with utmost convenience and efficiency. Inventory management continues to evolve. Like many other processes, the evolution is driven by the need for greater efficiency and accuracy.
</p>

<h2 id="manual_counting">3.1 Manual Counting</h2>
<p>
    Inventory management was very primitive before the Industrial Revolution. Some of the first people to rely on inventory management were shopkeepers and merchants, who would count the number of units at the end of each day, determine how many were sold and do their best to forecast future needs. The process of manually counting the physical inventory and keeping all the records in writing was a very time consuming and tedious work.
</p>

<h2 id="punch_card_system">3.2 Punch Card System</h2>
<p>
    The Industrial Revolution completely transformed the inventory management process as efficiency and mass production became the main goals. The punch card system was the “next big thing”, designed by a team at Harvard University in the early 1930’s. The tiny holes in sheets of paper allowed punch cards to correspond with catalogue items that were readable by computers. The information would be passed to employees in the storeroom, who would then bring the item up front to the customer. Companies could keep track of which products were being ordered and record inventory and sales data based on the punch cards customers filled out. Unfortunately, this process was too expensive and too slow to remain widely used and to keep up with rising challenges.
</p>

<h2 id="the_modern_bar_code">3.3 The Modern Bar Code</h2>
<p>
    The first version of the modern bar code was created in the 1940’s and 1950’s and was composed of ultraviolet light-sensitive ink and a reader to track items for sale. As technology improved in the 1980’s and 1990’s, the bar code system became more efficient, affordable and widely adopted. The implantation of more advanced computers and software allowed the modern bar code to flourish for years. At this point, inventory tracking by hand was replaced by scanning products, but inputting information into computers was still done by hand.
</p>
<p>
    QR (Quick Response) code are advanced barcodes that are easily scannable via a smartphone. They are a matrix of black-and-white squares/data modules invented by Denso Wave, a Japanese company in 1994 that was initially used in production control of automotive parts. Currently it has widespread use in various aspects of human life. It is basically a two-dimensional figure defining data in a visual, system-readable form. Through the 1970s-1980s, the amount and the type of data stored evolved. From 13 digits numeric storage Universal Product Code (UPC)to Code 39 (approx. 30 alphanumeric characters) to multistage symbol codes Code 16kK and Code 49 (approx. 100 characters). As demand rose to store more information and represent other languages, QR code which can store 7000 characters including languages that required higher density than the previous versions such as the Chinese characters required by Denso Wave.
</p>
<p>
    Apart from the large volume of data storage and high density QR code has highspeed reading and is superior in both performance and functionality.
</p>
<p>
    Elements of QR Code. <br> The shape of QR Codes must always be square.
</p>
<ol>
    <li><strong>Positioning marking:</strong><br> This indicates the direction in which the QR code is printed so that scanning/ reading the code is possible with your camera at any angle.</li>
    <li><strong>Alignment marking:</strong><br> This helps to orient the image.</li>
    <li><strong>Timing pattern:</strong><br> This helps to determine the size of the data matrix in the QR Code.</li>
    <li><strong>Quiet zone:</strong><br> The most crucial part of the QR Code, it helps the scanner/ reader to differentiate QR code from the surroundings.</li>
    <li><strong>Version information:</strong><br> These markers are present in QR code to specify the code version being used. There are 40 different versions of QR Code. The most common ones are versions 1 to 7.</li>
    <li><strong>Format information:</strong><br> This consists of information about the error tolerance that makes it easier to scan the code.</li>
    <li><strong>Data and error correction module:</strong><br> It is the central part of the QR code consisting of black and white modules which stores the data and has space.</li>
</ol>
<h3><strong>Some special features of QR Code</strong></h3>
<ol>
    <li><strong>All-direction high-speed reading:</strong>
        <br>Existing two-dimensional symbols took much time to detect the position/angle/size and used to give less accurate readings compared to the existing one-dimensional symbols. QR code has Finder patterns (mentioned in Elements of QR Code) for notifying the position of the symbol oriented within the three of its corners to enable high-speed reading in all directions (360 degrees). There is a fixed ratio of black to white (1:1:3: 1:1) in the scan line in the finder patterns. Using this ratio, finder pattern is detected to identify the code in short time. As soon as the position/size/angle of the symbol is detected, decoding is implemented.</li>
    <li><strong>Resistant to distorted symbols:</strong>
        <br>Symbols get distorted in a curved surface or the positioning of the reader or the scanner. QR code has alignment patterns (mentioned in the Elements of QR Code) arranged in regular interval within the range of the symbol. The variance between the centre position of the pattern estimated from the outer shape of the symbol and the centre of the alignment pattern is calculated to have the mappings corrected, thus making the non-linear symbols.</li>
</ol>

<hr>

<h1 id="project_design">4. PROJECT DESIGN</h1>

<h2 id="software_requirements">4.1 Software Requirements</h2>
<p>
    Front end: HTML, CSS, Java Script<br> Back End: PHP, SQL<br> Database: MySQL<br> Editor: Visual Studio Code
</p>
<h2 id="database_design">4.2 Database Design</h2>
<h3 id="database_tables">4.2.1 Database Tables</h3>
<p>
    The total number of database tables that were identified to build the system is 3. The Tables are:
</p>
<ul>
    <li>Admin table: Here in this the details of the admin will be stored like name, Email etc.</li>
    <li>User table: Here in this component the details of the users will be stored like name, Email etc.</li>
    <li>Item table: Here in this the details of the items will be stored like item name, bill number, bill date, cost etc.</li>
</ul>
<h2 id="system_design">4.3 System Design</h2>
<h3 id="users">4.3.1 Users</h3>
<p>
    The major functionality of this product is divided into two categories.
</p>
<ol>
    <li>Admin User Functions.</li>
    <li>Normal User Functions.</li>
</ol>
<h3 id="admin_user_functions">4.3.2 Admin User Functions</h3>
<p>
    Admin can perform the following task:
</p>
<ul>
    <li>Create new users</li>
    <li>Can remove a user</li>
    <li>Add the information of the Inventory purchased</li>
    <li>Can view the information of the Inventory</li>
    <li>Can update the information of the Inventories</li>
    <li>Can view the list of all Inventories</li>
    <li>Can generate unique QR Code for each new Inventory</li>
    <li>Can scan the QR Code and see all the information about that Inventory</li>
    <li>Can view the list of all users</li>
</ul>
<h3 id="normal_user_functions">4.3.3 Normal User Functions</h3>
<p>Normal users can perform the following task:</p>
<ul>
    <li>Can scan the QR Code</li>
    <li>Can view the information of the inventory</li>
</ul>
<h2 id="uml_diagrams">4.4 UML Diagrams</h2>
<h3 id="uml_unified_modelling_language">4.4.1 UML (UNIFIED MODELLING LANGUAGE)</h3>
<p>
    The unified modelling language is a standard language for specifying, Visualizing,
    Constructing and Documenting the software system and its components. It is a
    graphical language which provides a vocabulary and set of semantics and rules.
    The UML focuses on the conceptual and physical representation of the system.
    It captures the decisions and understandings about systems that must be
    constructed. It is used to understand, design, configure, maintain and control
    information about the systems.
</p>
<h3 id="visualizing">4.4.2 Visualizing:</h3>
<p>
    Through UML we see or visualize an existing system and ultimately, we
    visualize how the system is going to be after implementation. Unless we think
    we cannot implement.
    UML helps to visualize how the components of the system communicate and
    interact with each other.
</p>
<h2 id="specifying">4.4.3 Specifying:</h2>
<p>
    Specifying means building models that are precise, unambiguous and complete. UML addresses the specification of all the important analysis, design, and implementation decisions that must be made in developing and deploying a software system. Forward engineering and reverse engineering are possible through UML. UML’s models can be directly connected to a variety of programming languages through mapping a model from UML to a programming language like Java, C++, or VB.
</p>
<h2 id="documenting">4.4.4 Documenting:</h2>
<p>
    The deliverables of a project, apart from coding, are some artifacts which are critical in controlling, measuring, and communicating about a system during its development, such as requirements, architecture, design, source code, project plans, tests, prototypes, and releases, etc.
</p>
<h2 id="diagrams_in_uml">4.4.5 Diagrams in UML</h2>
<p>
    Diagrams are graphical presentations of a set of elements. Diagrams project a system or visualize a system from different angles and perspectives. The UML has nine diagrams, which can be classified into the following groups.
</p>
<h3>4.4.5.1 Static</h3>
<ol>
  <li>Class diagrams.</li>
  <li>Object diagrams.</li>
  <li>Component diagrams.</li>
  <li>Deployment diagrams.</li>
</ol>
<h3>4.4.5.2 Dynamic</h3>
<ol>
  <li>Use case diagram.</li>
  <li>Sequence diagram.</li>
  <li>Collaboration diagram.</li>
  <li>State chart diagram.</li>
  <li>Activity diagram.</li>
</ol>
<h2 id="modules">4.5 Modules</h2>
<p>
    The system, after careful analysis, has been identified to present with the following modules.
</p>
<h3 id="valid_users_module">4.5.1 Valid Users Module:</h3>
<p>
    This module maintains the email IDs of valid users approved by the admin of the corresponding department. It allows the admin to add or remove an inventory manager and other valid users to record to the database very easily, and it allows to view the list of valid users in tabular format out of which he can edit a particular employee.
</p>
<h3 id="inventory_module">4.5.2 Inventory Module:</h3>
<p>
    This module maintains all the information related to the equipment that is recorded to the database. All the purchases are recorded to the database by the assigned inventory manager/admin and can be viewed as a report that displays all the items under the department corresponding to the inventory manager. It allows a valid user to view details corresponding to the item scanned.
</p>
<h2 id="feasibility_analysis">4.6 Feasibility Analysis:</h2>
<p>
    Feasibility study is an important phase in the software development process. It enables the developer to have an assessment of the product being developed. It refers to the feasibility study of the product in terms of outcomes of the product, operational use, and technical support required for implementing it. Feasibility study should be performed based on various criteria and parameters. The various feasibility studies are:
</p>
<ul>
  <li>Technical Feasibility</li>
  <li>Economic Feasibility</li>
</ul>
<h3 id="technical_feasibility">4.6.1 Technical Feasibility</h3>
<p>
    The system is self-explanatory and does not need any extra sophisticated
    training. As the system has been built by concentrating on the Graphical User
    Interface Concepts, the application can also be handled very easily with a novice
    user. The overall time that is required to train the users upon the system is less
    than half an hour.
    The System has been added with features of menu-driven and button interaction methods, which makes the user the master as he starts working
    through the environment. The net time the customer should concentrate is on
    the installation time and adding/updating entries of equipment to be recorded.
</p>
<h3 id="financial_feasibility">4.6.2 Financial Feasibility</h3>
<p>
    i) Time Based: In manual system it is too difficult to maintain data which become
    easier in this system. Time consumed to add new records or to view the reports
    is very less compared to manual system. So, this project is feasible in this point
    of view.
</p>
<p>
    ii) Cost Based: No special investment needs to manage the tool for general
    users. From the institute’s part investment is required for generating QR code
    stickers, hosting in server and maintenance. The software used in this project is
    freeware so the cost of developing the tool is minimal and hence the overall
    cost.
</p>
<h3 id="implementation_plan">4.6.3 Implementation Plan</h3>
<p>
    The main plan for the system developed is to mimic the existing system as it is
    in the proposed system.
</p>
<h2 id="software_requirement_analysis">4.7 SOFTWARE REQUIREMENT ANALYSIS</h2>
<h3 id="what_is_srs">4.7.1 What is SRS?</h3>
<p>
    Software Requirement Specification (SRS) is the starting point of the software developing activity. As system grew more complex it became evident that the goal of the entire system cannot be easily comprehended. Hence the need for the requirement phase arose. The software project is initiated by the client needs. The SRS is the means of translating the ideas of the minds of clients (the input) into a formal document (the output of the requirement phase.)
</p>
<p>
    The SRS phase consists of two basic activities:
</p>
<ol>
    <li>Problem/Requirement Analysis:<br>
        The process is order and more nebulous of the two, deals with understand the
        problem, the goal and constraints.
    </li>
    <li>Requirement Specification:<br>
        Here, the focus is on specifying what has been found giving analysis such as
        representation, specification languages and tools, and checking the
        specifications are addressed during this activity.
    </li>
</ol>
<p>
    The Requirement phase terminates with the production of the validate SRSdocument. Producing the SRS document is the basic goal of this phase.
</p>
<h3 id="role_of_srs">4.7.2 Role of SRS:</h3>
<p>
    The purpose of the Software Requirement Specification is to reduce the communication gap between the clients and the developers. Software Requirement Specification is the medium though which the client and user needs are accurately specified. It forms the basis of software development. A good SRS should satisfy all the parties involved in the system.
</p>
<p>
<h3 id="purpose">4.7.3 Purpose:</h3>
    <p>
        The purpose of this document is to describe all external requirements for the Inventory Manage System. It also describes the interfaces for the system. The Basic purpose of developing this project to cater to the needs of the institut to record details of the equipment in different departments.
    </p>

<h3 id="scope">4.7.4 SCOPE:</h3>
<p>
    This document is the only one that describes the requirements of the system. It is meant for the use by the developers and will also be the basis for validating     the final delivered system. Any changes made to the requirements in the future will have to go through a formal change approval process. The developer is responsible for asking for clarifications, where necessary, and will not make any alterations without the permission of the client. The scope of this system to allow the departments to manage inventory and generate the reports dynamically by scanning QR code of the corresponding equipment.
</p>

<hr>
<h1 id="diagrams">4.8 DIAGRAMS</h1>
<h2 id="4.8.1_class_diagram">4.8.1 Class Diagram</h2>
<figure>
  <img src="/images/readme_images/4.8.1_class_diagram.png" alt="Class Diagram">
  <figcaption>Fig: Class Diagram</figcaption>
</figure>
<h2 id="4.8.2_use_case_diagram">4.8.2 Use case Diagram</h2>
<figure>
  <img src="/images/readme_images/4.8.2_use_case_diagram.png" alt="Use case Diagram">
  <figcaption>Fig. Use Case Diagram of Inventory management System</figcaption>
</figure>
<h2 id="4.8.3_sequence_diagram">4.8.3 Sequence Diagram</h2>
<h3>Admin</h3>
<figure>
  <img src="/images/readme_images/4.8.3_sequence_diagram_admin.png" alt="Admin Sequence Diagram">
  <figcaption>Fig. Admin Side Sequence Diagram</figcaption>
</figure>
<h3>User</h3>
<figure>
  <img src="/images/readme_images/4.8.3_sequence_diagram_user.png" alt="User Sequence Diagram">
  <figcaption>Fig. User Side Sequence Diagram</figcaption>
</figure>
<h2 id="4.8.4_activity_diagram">4.8.4 Activity Diagram</h2>
<h3>Admin</h3>
<figure>
  <img src="/images/readme_images/4.8.4_activity_diagram_admin.png" alt="Admin Activity Diagram">
  <figcaption>Fig. Admin Side Activity Diagram</figcaption>
</figure>
<h3>User</h3>
<figure>
  <img src="/images/readme_images/4.8.4_activity_diagram_user.png" alt="User Activity Diagram">
  <figcaption>Fig. User Side Activity Diagram</figcaption>
</figure>
<h2 id="4.8.5_er_diagram">4.8.5 ER Diagram</h2>
<figure>
  <img src="/images/readme_images/4.8.5_er_diagram.png" alt="ER Diagram">
  <figcaption>Fig. ER Diagram</figcaption>
</figure>
<h2 id="4.8.6_database_schema">4.8.6 Database Schema</h2>
<figure>
  <img src="/images/readme_images/4.8.6_database_schema.png" alt="Database Schema">
  <figcaption>Fig. Database Schema</figcaption>
</figure>

<h1 id="conclusion">7. CONCLUSION</h1>
<p>
    This document outlines the problem, scope and necessary information to a reallife working web application for the inventory management system where the admin/inventory will be able to record all the necessary information about the product purchased by the department and it will generate a unique QR code. Valid user will be able to scan the QR code and after successful login can see the details of that equipment.
</p>

<h1 id="references">8. REFERENCES</h1>
<ol>
  <li><a href="https://www.odysseydcs.com">https://www.odysseydcs.com</a></li>
  <li>A Review of Inventory Management System, International Journal of Advanced Research in Computer and Communication Engineering</li>
  <li>A QR code technology for centralized inventory management system, International Research Journal of Engineering and Technology (IRJET), <a href="https://www.irjet.net">https://www.irjet.net</a></li>
  <li>Mobile based inventory management system using QR code, International Journal of Research Publication and Reviews, <a href="https://ijrpr.com">https://ijrpr.com</a></li>
  <li>Recognition of QR Code with mobile phones, Yue Liu, Ju Yang and Mingjun Liu, <a href="https://ieeexplore.ieee.org">https://ieeexplore.ieee.org</a></li>
</ol>
