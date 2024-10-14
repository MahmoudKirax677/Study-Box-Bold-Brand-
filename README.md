# Study Time - Educational App

**Description**:  
**Study Time** is an educational app designed to help students manage their study schedules, track their progress, and stay organized with built-in timers and personalized study plans. The app supports various features that enhance productivity, offering a seamless way for students to stay focused and achieve their academic goals. Additionally, the app allows users to purchase study courses and materials through **Google Play** and **Apple Pay**.

**Technologies Used**:
- **Flutter**: Cross-platform mobile app development.
- **Cubit (State Management)**: Efficient state management for handling complex user interactions.
- **Firebase Cloud Messaging (FCM)**: Sending notifications about upcoming study sessions, deadlines, and course updates.
- **API Integration**: Backend API for handling course purchases, user data, and progress tracking.
- **Google Play Billing & Apple Pay**: Integration for in-app purchases to allow users to buy courses, study materials, and premium features directly within the app.

**Key Features**:
- **Study Timers**: Built-in customizable timers to help students manage their study sessions efficiently.
- **Progress Tracking**: Students can track their study progress and stay organized with visual aids like charts and graphs.
- **Course Purchase**: The app allows users to purchase study courses and resources through **Google Play Billing** and **Apple Pay**, making it easy to access premium content.
- **Personalized Schedules**: Students can create and manage their own study schedules with reminders to keep them on track.
- **Push Notifications**: Users receive reminders for their upcoming study sessions, exams, or important deadlines through **Firebase Cloud Messaging**.
- **Responsive UI**: Optimized for different devices, ensuring a smooth and user-friendly experience.

**Architecture**:
- **Cubit**: The app uses **Cubit** for state management, allowing efficient handling of complex UI interactions, data updates, and user actions.
- **Repository Pattern**: Organizes API calls, database interactions, and user data in a structured way to ensure scalable and maintainable code.
- **Firebase Realtime Database**: Used for real-time updates on study progress, schedules, and reminders.

**User Flow**:
1. **Dashboard**: Users can view their study progress, upcoming sessions, and recommended courses.
2. **Set Timers**: The built-in timers help students manage their study sessions by setting up focused time periods.
3. **Purchase Courses**: Users can browse through a catalog of study materials and purchase courses directly from the app using **Google Play** or **Apple Pay**.
4. **Track Progress**: Students can track their progress in real-time, using visual charts and data stored in Firebase.
5. **Push Notifications**: Receive notifications for upcoming sessions or deadlines.
6. **Personalized Schedule**: Students can set and modify their study schedules and receive reminders when it's time to study.

**Challenges**:
- **Real-Time Data**: Ensuring that progress tracking and study schedules update in real time using **Firebase**.
- **Managing State**: Using **Cubit** to handle complex state changes while maintaining a smooth user experience.
- **In-App Purchases**: Integration of **Google Play Billing** and **Apple Pay** for purchasing courses and premium content.
- **Push Notifications**: Sending timely reminders for study sessions and course updates using **Firebase Cloud Messaging (FCM)**.

**App Links**:
- [Google Play Store - Study Time](https://play.google.com/store/apps/details?id=com.elegant.studytime.study_time)
**Live Demo**:  
Due to confidentiality, the source code is not available. However, a live demo can be provided during a meeting using an emulator like **Android Studio** or **Xcode** for iOS. You may request access to a testing environment for further review.

