# Job Portal Career Bridge

A comprehensive online job portal system that connects job seekers with employers, built with PHP and MySQL.

## Features

### For Job Seekers (Employees)
- User registration and profile management
- CV/Resume builder with PDF generation
- Job search and application tracking
- Academic qualifications management
- Professional experience tracking
- Skills and language proficiency
- Training and certification records
- Reference management
- Document attachments

### For Employers
- Company profile management
- Job posting and management
- View job applicants
- Applicant filtering and selection
- Company branding

### General Features
- Responsive web design
- User authentication system
- Password reset functionality
- Email notifications
- File upload capabilities
- Search and filter functionality

## Technology Stack

- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Frameworks**: Bootstrap
- **Libraries**: 
  - jQuery
  - Font Awesome
  - FPDF (PDF generation)
  - PHPMailer (Email functionality)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Job-Portal-Career-Bridge.git
```

2. Set up a local web server (XAMPP, WAMP, or LAMP)

3. Import the database:
   - Create a new MySQL database
   - Import the SQL file from `Database/job_portal.sql`

4. Configure database connection:
   - Update database credentials in `constants/db_config.php`

5. Start your web server and navigate to the project directory

## Project Structure

```
Job-Portal-Career-Bridge/
├── OnlineJobPortal/
│   ├── Database/           # Database schema and data
│   └── System/            # Main application files
│       ├── app/           # Core application logic
│       ├── employee/      # Employee dashboard and features
│       ├── employer/      # Employer dashboard and features
│       ├── constants/     # Configuration files
│       ├── css/          # Stylesheets
│       ├── js/           # JavaScript files
│       ├── images/       # Image assets
│       └── icons/        # Icon fonts and assets
```

## Usage

### Getting Started
1. Visit the homepage
2. Register as either an Employee or Employer
3. Complete your profile setup
4. Start using the platform features

### For Job Seekers
1. Create and customize your profile
2. Build your CV using the integrated CV builder
3. Search and apply for jobs
4. Track your applications

### For Employers
1. Set up your company profile
2. Post job openings
3. Review applications
4. Manage your job listings

## Configuration

Update the following configuration files:
- `constants/db_config.php` - Database connection settings
- `constants/settings.php` - Application settings
- `mail/` - Email configuration for notifications

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request



