# College ERP System

A comprehensive Educational Resource Planning (ERP) system designed for colleges and universities to manage students, faculty, courses, and administrative operations.

## Features

### 🎓 **Multi-Role Access**
- **Admin Dashboard**: Complete system management and oversight
- **Student Portal**: Course enrollment, grades, attendance, fees
- **Faculty Portal**: Course management, student tracking, grade submission

### 📚 **Core Modules**
- **Student Management**: Registration, profiles, academic records
- **Faculty Management**: Staff profiles, course assignments, schedules
- **Course Management**: Curriculum planning, course creation, enrollment
- **Attendance Tracking**: Real-time attendance monitoring and reports
- **Examination System**: Exam scheduling, grade management, results
- **Fee Management**: Fee structure, payment tracking, receipts
- **Timetable Management**: Class scheduling and calendar integration
- **Notice Board**: Announcements and communication system
- **Reports & Analytics**: Comprehensive reporting dashboard

## Project Structure

```
EduERP/
├── index.html              # Main login page
├── assets/
│   ├── css/
│   │   └── common.css      # Shared styles for all pages
│   └── js/
│       └── common.js       # Shared JavaScript functions
└── pages/
    ├── admin/              # Admin role pages (13 files)
    │   ├── dashboard.html
    │   ├── students.html
    │   ├── faculty.html
    │   ├── courses.html
    │   ├── course_management.html
    │   ├── attendance.html
    │   ├── timetable.html
    │   ├── exams.html
    │   ├── fees.html
    │   ├── notices.html
    │   ├── reports.html
    │   ├── profile.html
    │   └── settings.html
    ├── student/            # Student role pages (9 files)
    │   ├── dashboard.html
    │   ├── courses.html
    │   ├── attendance.html
    │   ├── timetable.html
    │   ├── exams.html
    │   ├── fees.html
    │   ├── notices.html
    │   ├── profile.html
    │   └── settings.html
    └── faculty/            # Faculty role pages (9 files)
        ├── dashboard.html
        ├── courses.html
        ├── students.html
        ├── attendance.html
        ├── timetable.html
        ├── exams.html
        ├── notices.html
        ├── profile.html
        └── settings.html
```

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **CSS Framework**: Bootstrap 5.3.0 + Tailwind CSS
- **Icons**: Font Awesome 6.0
- **Charts**: Chart.js for data visualization
- **Responsive Design**: Mobile-first responsive layout

## Quick Start

1. **Open the Application**
   ```
   Open index.html in your web browser
   ```

2. **Demo Login Credentials**
   - **Admin**: `admin@college.edu` / `admin123`
   - **Student**: `student@college.edu` / `student123`
   - **Faculty**: `faculty@college.edu` / `faculty123`

3. **Use Quick Demo Buttons**
   - Click any "Demo" button on the login page for instant access

## Key Features

### 🔐 **Authentication System**
- Role-based login (Admin/Student/Faculty)
- Demo credentials for testing
- Secure logout functionality
- Password visibility toggle

### 📊 **Dashboard Analytics**
- Real-time statistics and KPIs
- Interactive charts and graphs
- Role-specific data visualization
- Quick action buttons

### 👥 **User Management**
- Student profile management
- Faculty information system
- Administrative user controls
- Profile picture upload

### 📋 **Academic Operations**
- Course enrollment and management
- Attendance tracking with filters
- Exam scheduling and grading
- Timetable management

### 💳 **Financial Management**
- Fee structure configuration
- Payment tracking
- Fee receipt generation
- Outstanding balance alerts

### 📢 **Communication**
- Notice board system
- Announcement categories (Urgent, Important, Events)
- Email notification preferences
- Multi-channel communication

### ⚙️ **Settings & Configuration**
- System-wide settings (Admin)
- Personal preferences (All users)
- Security settings
- Notification preferences
- Privacy controls

## File Organization

### **Shared Resources**
- `assets/css/common.css`: Unified styling across all pages
- `assets/js/common.js`: Shared JavaScript functionality

### **Role-Based Structure**
Each role has its dedicated folder with consistent navigation and functionality:
- Consistent sidebar navigation
- Role-appropriate color schemes
- Responsive design patterns

## Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## Development Notes

- All pages use consistent Bootstrap and Font Awesome CDNs
- Responsive design with mobile-first approach
- Clean, semantic HTML5 structure
- Modular CSS and JavaScript organization
- Cross-role navigation consistency

## Future Enhancements

- Database integration (MySQL/PostgreSQL)
- Backend API development (Node.js/Python)
- Real-time notifications
- Mobile app development
- Advanced reporting features
- Integration with external systems

## License

This project is developed for educational purposes. Feel free to use and modify as needed.

---

**College ERP System** - Streamlining educational institution management with modern web technologies.
