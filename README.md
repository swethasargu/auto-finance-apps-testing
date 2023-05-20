# auto-finance-apps-testing
This repository documents my insights gained from my extensive experience in testing Auto Finance Applications. As a Software Test Lead, I played a key role in this project for a period of 2 years.


Project: Testing Captiva OCR (Optical Character Recognition) Application
Description: 
The goal of this project is to test the accuracy and functionality of scanned documents in relation to the database, front-end application, and Captiva application.

Auto finance clients scan customer documents, which are then stored in centralized repositories. These documents are classified by an internal application and stored in Documentum. As a test engineer, my role is to ensure that this application correctly tags the documents with a 99% accuracy rate.

The development team configures the Captiva application to process the classified documents according to business requirements. Captiva utilizes Optical Character Recognition to extract the necessary information and saves it in the Oracle Customer database.

The front-end application retrieves data from the database and also provides links to access the scanned documents within Documentum.

The scope of testing involved validating the data displayed in the front-end user interface against the corresponding data in the database and the accuracy of the scanned documents.

In summary, this project aims to verify the correct tagging and extraction of information from scanned documents, ensuring data consistency between the front-end UI, the database, and the Documentum repository.

Tools used: Documentum Query Language, Captiva, HP ALM

