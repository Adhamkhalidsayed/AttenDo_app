In the modern education system, tracking attendance efficiently and accurately is crucial for both students and institutions. To address this need, an attendance application has been developed using Flutter and Dart, along with the powerful Cloud Firestore database. 

Application Features:

1. Login and Main Screen:
Upon launching the application, students are required to log in and this process happens only one time after downloading the app on the phone (no more logins). This ensures that each student can access the app securely and prevents multiple logins. Once authenticated, students are presented with the main screen. This screen offers a seamless and intuitive interface, where students can simply slide to check in or check out.

![WhatsApp Image 2023-06-13 at 20 36 02](https://github.com/Adhamkhalidsayed/AttenDo_app/assets/96948853/016d3269-1821-4d0f-96ff-b95a30299853), ![WhatsApp Image 2023-06-13 at 20 41 21](https://github.com/Adhamkhalidsayed/AttenDo_app/assets/96948853/65e8d0c6-9a50-424f-8288-ab80f4a39ac5)


2. Attendance Tracking:
The application captures attendance times and locations for each check-in and check-out event. This information is stored in the Cloud Firestore database, ensuring data reliability and scalability. By storing location data, the application allows institutions to verify student attendance from designated areas, ensuring integrity.

![WhatsApp Image 2023-06-13 at 20 43 18](https://github.com/Adhamkhalidsayed/AttenDo_app/assets/96948853/7aa149f3-00f4-4704-a7b0-52d1b4aba2dd)


4. QR Code Scanning:
To further streamline the attendance process, students can opt to scan a QR code provided in the classroom. This feature simplifies the check-in and check-out process, eliminating the need for manual interaction. The QR code contains necessary information, such as class details and timestamps, which are automatically recorded and stored in the database.

5. Calendar View:
The application includes a dedicated calendar screen, providing a comprehensive overview of attendance for the entire month. This screen displays the days attended, along with the check-in and check-out times for each day. This feature enables students to monitor their attendance patterns and identify any discrepancies or patterns.

![WhatsApp Image 2023-06-13 at 20 43 45](https://github.com/Adhamkhalidsayed/AttenDo_app/assets/96948853/e4991277-3f0e-4969-813f-6a0e8776e7f8)

7. Profile Screen:
The profile screen allows students to personalize their information and add relevant details. This feature promotes a sense of individuality and enables students to take ownership of their profiles. Students can edit their first name, last name, address, date of birth, and even upload a profile photo. By limiting profile edits to one instance, the application ensures data consistency and avoids frequent modifications.

