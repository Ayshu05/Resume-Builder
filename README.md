# This application

● Provides a template regarding what information to include in a CV (Ex: Picture, Bio-data, Skills, Qualification, Work Experience)

● Collects the information in a form

● Presents it in a structured template in a document by placing fields in appropriate positions in the page

● Generates the document as a pdf and lends it to the user for their utility

● Stores previously entered information (in a database) and retrieves it when searched for making changes to existing CV

Developed by Ayshwarya B and C B Ananya

# Motivation to take up the problem
A candidate with apt credentials, required skill set and experience for a job often finds difficulty in presenting the same to employers. Crisp and clear format for a resume is essential in order to project the skills one has acquired. The team, being fervent in building our CV from our first year of college, saw this as an opportunity to find a solution to this common problem. We also felt that java has a programmer-friendly methodology to provide Graphical-User-Interface to create a form and provides convenient modes of connection to databases. Hence, the team decided to implement the idea in the form of a simple application with a user-friendly interface and sql connectivity for storage and retrieval of data.

# Scope and Limitations
Currently, we have provided only one template to the user to present their data. However, the scope of the project could be extended to provide multiple templates with various sets of fields to be included. Choice of color palettes could also be introduced. The project, as yet, does not have a login/signup process where a user can access only their CV. Searching for one’s CV is simply based on a search by first name. Hence, to improve the privacy of the user, we need to implement a registration/signup process, provide each user with an ID and allow them to set a password which could be stored in a database in an encrypted format. Limitations of the application also include the fact that it just takes the data as it is and helps only with the alignment, orientation and designing part of the CV and converting the input of the form into a pdf. It does not provide suggestions regarding the quality of content.

# To run the project:
Download Apache NetBeans IDE (We used Apache NetBeans IDE 16)

Open the project folder using the IDE.

Under the project, right-click on Libraries - > "Add JAR/Folder".

Add the jar files present in the "JAR FILES" folder of this repository.

In the project, go to

"Source Packages"->"cv.generator"->"CV.java" click on "Run" at the top and click the "Run File".

You are now good to go!

For a complete walkthrough of the application and other implementation details, please check out the project report.
