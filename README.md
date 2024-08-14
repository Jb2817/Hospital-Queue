Hospital Queue Management System
The Hospital Queue Management System is a Python-based application designed to manage patient queues in a hospital. Through an Object Oriented Approach the project assigns patients various levels of urgency among specific specializations; patients with the same specialization
are queued in the order of their urgency followed by the order of patients. Additionally, the program shows the average waiting time for a patient within a specialization. 
The system consists of three primary classes, each serving a specific purpose:

Patient
The Patient class represents an individual patient and includes the following attributes:

name: The name of the patient.
urgency_status: The patient's status, which can be 0 (normal), 1 (urgent), or 2 (super-urgent).
arrival_time: Time the patient walks in 
This class provides methods for string representation and status formatting for patients.

Specialization
The Specialization class manages patient queues within different specializations. It offers functionalities such as:

Adding patients with various urgency levels.
Searching for specific patients by name. 
Retrieving the next patient from the queue.
Removing patients by name.
Checking queue capacity.
PatientManagement
The PatientManagement class serves as the user interface for interacting with the Specialization instances. Users can perform actions like:

Adding new patients to specializations.
Listing patients in specializations.
Listing types of specializations
Retriving the average wait time for a specialization.
Searching for specific patients. 
Retrieving the next patient.
Removing patients.
Ending the program gracefully.
