Marie wants to go to football games. She starts her own travel agency. Now she wants to de-
velop ABAP programs. Please help her.
- Program 1: Display flights to a specific location and time
- Program 2: Book a specific flight
- Program 3: Cancel a booking

 SFLIGHT – flight instances (date, seats, price)
*& SPFLI – flight routes (from/to cities & airports)
*& SAPLANE – aircraft master data
*& SBOOK – bookings (for luggage weight)

SPFLI contains flight connections</br> <img width="669" height="452" alt="image" src="https://github.com/user-attachments/assets/e75bd05d-b184-4660-9e7e-527f5891d905" />

individual flights of a connection are stored in the table SFLIGHT </br> <img width="659" height="323" alt="image" src="https://github.com/user-attachments/assets/79e30b4c-c4b4-43a7-b99f-c7fd25e8cbd8" />

 SBOOK table, bookings are stored </br> <img width="663" height="514" alt="image" src="https://github.com/user-attachments/assets/aa97fd59-62a2-4c79-82b3-3e7132067beb" />

 Technical data of the airplanes is listed in the table SAPLANE. </br> <img width="454" height="368" alt="image" src="https://github.com/user-attachments/assets/a569850a-85cd-4328-a934-5ac7a4ae2eac" />

 ----------------------------------------------------------------

company’s customers can be found in the SCUSTOM table</br> <img width="607" height="348" alt="image" src="https://github.com/user-attachments/assets/2715a7ba-2fc6-4254-96d7-3194dd83336b" />

-------------------------------------------------------------------


