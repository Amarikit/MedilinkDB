# MedilinkDB - Clinic Management system.
##Project Title:
**#MedilinkDB**

##Description:
MediLink DB is a relational database management system (RDBMS) built to streamline the management of medical clinic operations. This database allows for the efficient tracking and organization of critical data such as:

- **Patient details**: Storing personal information and medical history.
- **Doctor profiles**: Including specialization, qualifications, and availability.
- **Appointments**: Scheduling and tracking patient consultations with doctors.
- **Treatment records**: Managing information related to treatments administered after each consultation.

##Setting Up:
1.Open MySQL Workbench or your preferred SQL interface.
2.Open the 'medilink_db.sql' file.
3.Execute the script to create the database schema.

##Database Structure:

MediLink DB consists of the following key tables, each designed to handle a specific aspect of clinic management:

- **Patient**: Stores personal and medical information for each patient.
- **Doctor**: Contains details about doctors, including their specialization and availability.
- **Specialization**: A list of medical specialties that doctors may have.
- **DoctorSpecialization**: A junction table that links doctors to their specializations.
- **Appointment**: Tracks patient appointments, including date, time, and assigned doctor.
- **Treatment**: Captures treatment details administered to patients during their visits.

link to ERD:
https://dbdiagram.io/d/68237b4a5b2fc4582f6f2abe







