# Auto-Ecole
This App is designed following a modular and scalable architecture, leveraging key principles to ensure maintainability, flexibility, and a seamless development experience.  

## User Side

- Users can log in with credentials provided by the admin, book appointments, take mock exams, and study driving theories, including traffic signs and priorities.

 <div>
 <p align="center">
  <img src="https://github.com/user-attachments/assets/70e7703b-466c-43ff-92f0-c0fe504a8055"height="400" >
  <img src="https://github.com/user-attachments/assets/0b14ef55-d378-4a5d-b903-90cff3b8a514" height="400" >
  <img src="https://github.com/user-attachments/assets/50e37a25-c49c-444b-8213-5d42b7061d14" height="400" >
  <img src="https://github.com/user-attachments/assets/3ebf88d0-be64-4790-bc74-f5b06b44945c" height="400" >
  <img src="https://github.com/user-attachments/assets/441d6bfa-d703-4c33-9739-db170f9adde3" height="400" >
  <img src="https://github.com/user-attachments/assets/6de9f323-1e9e-454f-877e-07f342d3097f" height="400">
   <img src="https://github.com/user-attachments/assets/2a5b0e95-9785-4fb0-b44c-194615d6ef70"height="400">
  <div>
    
## Admin Side
- Admins can log in, manage users (create, update, and delete), schedule appointments, view appointment details, and cancel appointments for users
 <div>
 <p align="center">
  <img src="https://github.com/user-attachments/assets/511c0e71-77ad-490d-902e-c2b9dc4ea142"height="400" >
  <img src="https://github.com/user-attachments/assets/6dd09ab0-3e9d-47fa-a28b-c0c12ed7117b" height="400" >
  <img src="https://github.com/user-attachments/assets/f1b4a04f-e036-4f4b-88e8-a76eab82623a" height="400" >
  <img src="https://github.com/user-attachments/assets/21a57d3b-b0d5-4320-ac7f-7fd27af200ce" height="400" >
  <img src="https://github.com/user-attachments/assets/b2daa7aa-3d46-49b8-9439-3e8acbb6a477" height="400" >
  <img src="https://github.com/user-attachments/assets/92264788-c9e6-414e-8435-3c293d40813e" height="400">
   <img src="https://github.com/user-attachments/assets/a918e9fd-c289-45eb-a231-4ffd45416aca"height="400">
   <img src="https://github.com/user-attachments/assets/0edfc5bf-7ac2-4b97-9fc2-3a30c76fee88"height="400">
  <div>
    
## Features
- **Admin & User Authentication** (Secure login for both admin and users)  
- **Appointment Management:**  
  - Admin can **schedule, update, and delete appointments**  
  - Users can **book available appointments**  
- **User Management:**  
  - Admin can **create, update, and delete users**  
- **Mock Exams:**  
  - Users can **take practice tests** with multiple-choice questions  
- **Learning Modules:**  
  - Study **traffic signs, priorities, and driving theory** 

# Architecture 
This app uses the Clean Architecture with [Bloc Pattern](https://bloclibrary.dev/architecture/), separating the app into Data, Domain, and UI layers, resulting in testable, maintainable, and flexible code.

# Tools and Libraries
- [Bloc](https://bloclibrary.dev/)
- [Firebase Cloud Firestore](https://firebase.google.com/docs/firestore)
- [GoRouter](https://pub.dev/packages/go_router)
- [GetIt](https://pub.dev/packages/get_it)
- [Hive](https://docs.hivedb.dev/#/)
- [Shared Preferences](https://pub.dev/packages/shared_preferences)
- [Equatable](https://pub.dev/packages/equatable)

  
