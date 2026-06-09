Database Schema

Patient

* patient_id (Primary Key)
* name
* email
* phone
* address

Hospital

* hospital_id (Primary Key)
* hospital_name
* location
* available_beds
* contact_number

BloodBank

* bloodbank_id (Primary Key)
* blood_group
* units_available
* contact_number

Ambulance

* ambulance_id (Primary Key)
* driver_name
* vehicle_number
* status

EmergencyRequest

* request_id (Primary Key)
* patient_id (Foreign Key)
* request_type
* request_status
* request_time