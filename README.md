# SkillShare - Connect & Learn Platform

A complete frontend-only web application for connecting people to share and learn skills. Built with pure HTML, CSS, and JavaScript with LocalStorage persistence.

## Features

### 🔐 Authentication System
- **Signup**: Register with name, email, and password
- **Login**: Secure authentication with email validation
- **Session Management**: Persistent login sessions

### 🏠 User Discovery
- **Home Page**: Browse all registered users
- **Profile Cards**: Display user info, skills, and ratings
- **Search & Filter**: Find users by skills or name

### 👤 Profile Management
- **View Profiles**: Detailed user profiles with skills
- **Skill Management**: Add, edit, and remove personal skills
- **Learn Requests**: Request to learn skills from other users

### 📚 Learning System
- **Learn Requests**: Send/receive skill learning requests
- **Request Management**: Accept or reject incoming requests
- **Contact Sharing**: Automatic bidirectional contact sharing on acceptance

### ⭐ Rating System
- **5-Star Ratings**: Rate other users (1-5 stars)
- **Average Ratings**: Calculated and displayed ratings
- **Rating History**: Track all ratings given and received

### 📊 Dashboard
- **Top Users**: Ranked list of highest-rated users
- **Statistics**: User stats and performance metrics
- **Activity Feed**: Recent platform activity

## Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Storage**: LocalStorage for data persistence
- **Design**: Responsive design with mobile-first approach
- **No Frameworks**: Built without external dependencies

## File Structure

```
skillshare-app/
├── index.html              # Main HTML file with all pages
├── styles/
│   ├── main.css            # Base styles and variables
│   ├── components.css      # Reusable component styles
│   └── pages.css           # Page-specific styles
├── scripts/
│   ├── app.js              # Main application initialization
│   ├── auth.js             # Authentication management
│   ├── navigation.js       # Page routing and navigation
│   ├── storage.js          # LocalStorage utilities
│   ├── users.js            # User management and display
│   ├── skills.js           # Skill management
│   └── ratings.js          # Rating system and dashboard
└── README.md
```

## Getting Started

1. Clone or download the project files
2. Open `index.html` in a modern web browser
3. Start with the signup page to create your account
4. Explore the platform features

## Features Overview

### User Authentication
- Secure signup with email validation
- Login with persistent sessions
- Logout functionality

### Skill Sharing
- Add unlimited skills to your profile
- Browse other users' skills
- Request to learn specific skills
- Manage incoming learning requests

### Contact Sharing System
When a user accepts a learn request:
- **Teacher's View**: Can see the student's contact information
- **Student's View**: Automatically receives the teacher's contact information
- **Bidirectional Sharing**: Both parties can contact each other
- **Organized Display**: Contacts are clearly labeled as "Student" or "Teacher"

### Rating System
- Rate users from 1-5 stars
- View average ratings for all users
- Rating-based user rankings

### Responsive Design
- Mobile-friendly interface
- Tablet and desktop optimized
- Clean, modern UI design

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Data Persistence

All user data is stored locally in the browser using LocalStorage:
- User accounts and profiles
- Skills and learning requests
- Ratings and reviews
- Session information
- Shared contact information

**Note**: Data is stored locally and will be lost if browser data is cleared.

## How Contact Sharing Works

1. **User A** requests to learn a skill from **User B**
2. **User B** receives the request in their "My Profile" page
3. When **User B** accepts the request:
   - **User B** can see **User A's** contact information in their "Shared Contacts"
   - **User A** automatically receives **User B's** contact information in their "Shared Contacts"
   - Both users can now contact each other directly

## Contributing

This is a demonstration project showcasing frontend web development skills. Feel free to use as a learning resource or starting point for similar projects.

## License

This project is open source and available under the MIT License.