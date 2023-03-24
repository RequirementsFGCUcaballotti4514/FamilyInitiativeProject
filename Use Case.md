# Use Cases for Family Initiative
## 001-0001: Staff Enters Data for Client
**Primary Actors:** Staff, Parent, client database

**Preconditions:**

- Staff must have login credentials to access the system
- Staff must navigate to the "Client" tab
- Client information must be available for RBT to input
- Parent must have login credentials to view client data
- Parent must navigate to the "Client Data" section

**Description:**

- Staff logs in to the system with their credentials
- Staff navigates to the "Client" tab
- Staff selects the client for whom they want to input data
- Staff inputs the relevant data for the client
- Staff saves the data for the client
- Parent logs in to the system with their credentials
- Parent navigates to the "Client Data" section
- Parent views the relevant data for their child

**Alternative Path:**

- If staff encounters an issue while inputting data, they can choose to save the data and come back to it later
- If the staff makes an issue after the data was input. They are able to edit the save file. 
  - [Edit Data Entry](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/blob/main/Use%20Case.md#010-0001-edit-data-entry).
- If the system is experiencing technical difficulties and the data cannot be saved, RBT will be prompted to try again later
- If the parent encounters an issue while viewing the data, they can choose to contact the RBT or the system support team for assistance

**Postconditions:** 
- Data for the client is saved in the system. 
- Parent is able to view relevant data for their child
- staff is able to continue providing services for the client using the inputted data.

### Summary
The majority of the throughput in the system will be from the RBT as they will be interacting with the client the most. As they interact with the client
they collect data and enter behavior data for patients undergoing behavioral therapy. 
The staff must be able to access the software system, input client data, select the appropriate behavior category, record the behavior occurrence and duration, 
and save the data. The staff must be able to do this quickly and easily, as time constraints can be a factor. 
The system should be designed to allow for easy access and efficient navigation to reduce the time taken to input data. 
The data entered must be accurate and secure, as it will be used by therapists to develop treatment plans. In addition, 
the system should provide appropriate data visualization and reports to enable therapists to make informed decisions 
and track patient progress over time. Overall, the staff data inputting use-case is critical for effective behavioral therapy and requires a software system 
that is user-friendly, accurate, secure, and provides useful data insights.

The staff working with a client needs to be able to login to thier account after a session and have access to the client's profile and input promted data.
1) Login through staff page
2) Locate client tab
3) Select client
4) Input data
5) save changes

 The data entered by the RBT will be saved in the system and can be accessed by authorized personnel for further analysis and use. 
 After entering the data, the staff may continue with their other duties or enter more data if needed. 
 The system may also generate reports or alerts based on the data entered, which can be reviewed and acted upon by authorized personnel. 
 Additionally, the system may provide feedback to the RBT regarding the accuracy or completeness of the data entered, 
 allowing for any necessary corrections to be made.
 
 
## 010-0001: Edit Data Entry
**Primary Actors:** Staff, client database

**Pre-conditions:** The staff must have previously entered data into the system and needs to make a correction to the data.
 
**Disctiption:** This use case describes the steps for an staff to edit a mistake they have made in their data input.

- The staff logs into the system.
- The staff navigates to the data entry page where the mistake was made.
- The staff locates the incorrect data entry and selects the option to edit it.
- The system displays the previously entered data for the RBT to make the correction.
- The staff modifies the data entry with the correct information.
- The staff submits the corrected data entry.
- The system confirms that the data entry has been successfully updated.

**Alternative Path:**

- If the staff cannot locate the incorrect data entry, they may use the search functionality to find it.
- if the staff encounters an error while attempting to edit the data entry, they may contact the system administrator for assistance.

### Summary 
The "Edit Input Data" use case is aimed at enabling staff to correct errors in their recorded data. The preconditions for this use case are that the staff must have already recorded data and made mistakes in the process. They must also have access to the software system where the data was entered.

When the RBT realizes that they have made an error in their data input, they will initiate the "Edit Input Data" use case. The software will provide a form that allows the staff to search for and select the specific data entry containing the mistake. The form will display the recorded data for the staff to review and edit. The staff will then make the necessary changes, and the software will validate the new data entered. If validation is successful, the updated data will be saved in the system.

The goal of this use case is to provide staff with an efficient and user-friendly way to correct mistakes made during data input. This use case ensures that accurate data is maintained in the system, which is crucial for effective treatment planning and decision-making.

The overall goal of the use case is to allow the RBT to correct any mistakes they made in the input data so that the data accurately reflects the client's progress and can be used to make informed decisions about the client's treatment plan.
- the staff navigates to the input data page.
- the staff identifies the mistake they made in the data and clicks on the "Edit" button next to the data point they want to change.
- The system opens an edit form pre-populated with the current value of the data point.
- The staff modifies the data in the edit form to correct the mistake.
- The staff submits the edit form
- The system validates the input data and updates the database with the new value of the data point.
- The system confirms that the edit was successful by displaying a message to the RBT.

the system will update the information with the corrected data and save it. The staff will be able to view the corrected data in the system, 
and the correction will be reflected in any reports or analyses that are generated from the data. FI wants to retain the original document as well
to reflect on why the correction was make if they need it. 
The staff may choose to review the corrected data to ensure that it is accurate and complete. 
The goal of this use case is to allow RBTs to correct any errors or omissions in their input data to ensure that it is reliable and 
useful for future analysis and decision-making.
 
![Use Case Diagram](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/blob/main/Diagrams/use%20case.JPG)
Created with Lucidchart.
