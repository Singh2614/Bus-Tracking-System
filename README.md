# Bus Tracking App

A mobile application designed to provide **real-time bus tracking** for college students using GPS-based location sharing. The app enhances student convenience and safety by displaying the live location of college buses and allowing updates related to bus status.

##  Features

- **Live Bus Tracking**  
  Displays the driver’s real-time location using GPS and map integration.

- **Secure User Authentication**  
  Only registered users (students and drivers) can log in and access location data.

- **In-App Status Feed**  
  Students can view or post updates about delays, bus issues, or announcements.

##  Tech Stack

- **Flutter** – Cross-platform mobile app development  
- **Firebase Authentication** – Secure user login/signup  
- **Firebase Realtime Database / Firestore** – Storing location and feed updates  
- **Google Maps API / OpenStreetMap** – For map and location rendering (as per availability)

##  How It Works

1. **Driver logs in** and shares location continuously.
2. **Students log in** and can see the bus location on a map.
3. **Feed section** lets users post or view updates related to bus status or delays.

##  Security

- User roles (driver/student) are validated during authentication.
- Location access is permission-based and limited to authorized users.

## Future Improvements

- Push notifications for arrival alerts  
- Admin panel for bus route and user management  
- Offline caching of last known location


