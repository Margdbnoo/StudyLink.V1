# Global School Study Link Dashboard

A modern React dashboard for Global School Study Link with test preparation resources (IELTS, SAT, HSK), student profile management, habit tracking, essay management, community networking, multi-language support, and dark mode.

## Features

### Core Features
- **Dashboard**: Overview of test preparation resources (IELTS, SAT, HSK)
- **Student Profile**: Manage your profile with avatar, name, bio, skills, and hobbies
- **Habit Tracker**: Log daily routines and track your progress
- **Study Planner**: Create and manage daily study tasks with checkboxes
- **Essay Management**: Write, save, edit, and view your essays
- **Community Hub**: Connect with other students and view their profiles
- **Multi-language Support**: Switch between Mongolian, English, Chinese, Korean, and Russian
- **Dark Mode**: Toggle between light and dark themes with persistent storage
- **Data Persistence**: All data is saved to localStorage and persists after page refresh

### UI/UX Features
- **Modern Design**: Beautiful purple/white gradient theme with Tailwind CSS
- **Responsive Layout**: Fully responsive design for mobile, tablet, and desktop
- **Professional Icons**: Lucide React icons throughout the interface
- **Smooth Animations**: Transitions and hover effects for better UX

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
  ├── components/
  │   ├── Dashboard.jsx      # Main dashboard container with routing
  │   ├── Sidebar.jsx         # Sidebar with navigation and controls
  │   ├── MainContent.jsx     # Dashboard main content
  │   ├── Profile.jsx         # Student profile page
  │   ├── Habits.jsx          # Habit tracker and study planner
  │   ├── Essays.jsx          # Essay management system
  │   └── Community.jsx      # Community networking hub
  ├── App.jsx                 # Root component with dark mode state
  ├── main.jsx                # Entry point
  └── index.css               # Global styles with Tailwind
```

## Technologies Used

- **React 18**: UI library
- **Vite**: Build tool and dev server
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Beautiful icon library
- **localStorage**: Client-side data persistence

## Data Storage

All user data is stored in browser localStorage:
- `darkMode`: Dark mode preference
- `studentProfile`: User profile information
- `habits`: Daily habit tracking data
- `studyTodos`: Study planner tasks
- `essays`: Saved essays
- `connections`: Community connections

## License

MIT
