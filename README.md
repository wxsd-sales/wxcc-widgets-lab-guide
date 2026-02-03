# WXCC Widget Integration Lab Guide

An interactive, step-by-step lab guide for learning how to integrate Webex Contact Center (WXCC) widgets into web applications.

## 🎯 Features

- **Interactive Lab Guide**: 14 comprehensive lab sections covering WXCC widget integration
- **Sidebar Navigation**: Easy navigation with visual progress tracking
- **Progress Tracking**: Automatically saves user progress using localStorage
- **Multi-User Support**: Individual progress tracking for up to 16 users
- **Copy-to-Clipboard**: One-click copying for credentials and code snippets
- **Modern UI**: Clean, responsive design with mobile support
- **Resume Capability**: Users can pick up where they left off after closing the browser

## 📚 Lab Sections

1. **Lab Overview** - Introduction to WXCC widget integration
2. **Your Credentials** - Personal sandbox credentials
3. **Verify Node.js** - Environment setup verification
4. **Clone Repository** - Getting the lab code
5. **Install Dependencies** - Setting up the project
6. **Start Application** - Running the development server
7. **Get Access Token** - Authentication setup
8. **Implement Login Widget** - Adding login functionality
9. **Implement Widgets** - Step-by-step widget integration
10. **Prepare for Testing** - Setting up for call testing
11. **Make Test Call** - Testing the integration
12. **Verify Integration** - Complete integration verification
13. **Troubleshooting** - Common issues and solutions
14. **Resources & Cleanup** - Additional resources and cleanup steps

## 🚀 Quick Start

1. Open `index.html` in your web browser
2. Login with a username (user1 through user16)
3. Follow the step-by-step lab guide
4. Your progress is automatically saved!

## 📋 Prerequisites

- Modern web browser (Chrome, Firefox, Edge recommended)
- Node.js installed (for the actual WXCC integration lab)
- Git (for cloning the WXCC widgets repository)

## 👥 User Credentials

The lab supports 16 users (user1 - user16), each with unique credentials stored in `users-credentials.json`:
- Agent email and password
- Supervisor email and password
- Test phone number

## 💾 Progress Tracking

User progress is automatically saved in the browser's localStorage:
- Current page position
- Completed sections (shown with green checkmarks)
- Resume from last position on next login

## 🎨 Features Highlights

### Sidebar Navigation
- Numbered sections with visual indicators
- Active section highlighted in blue
- Completed sections marked with green checkmarks
- Click any section to jump directly to it

### Code Snippets
- Syntax-highlighted code blocks
- One-click copy buttons
- Visual feedback on copy

### Credentials Management
- Easy-to-copy credential buttons
- Per-user credential storage
- Visual copy confirmation

## 📱 Mobile Responsive

The lab guide automatically adapts to different screen sizes:
- Desktop: Full sidebar navigation
- Mobile: Streamlined navigation with bottom controls

## 🛠️ Technologies Used

- Pure HTML/CSS/JavaScript
- localStorage for progress tracking
- Modern ES6+ JavaScript
- Responsive CSS Grid/Flexbox

## 📄 Files

- `index.html` - Main lab guide application
- `users-credentials.json` - User credentials database
- `simple-lab.html` - Simplified test version

## 🔒 Security Note

This is a lab environment with dummy credentials. In production:
- Never hardcode credentials
- Use proper authentication mechanisms
- Implement server-side session management

## 📖 Usage

### For Students
1. Login with your assigned username
2. Follow the lab steps in order
3. Use the sidebar to navigate or review previous sections
4. Your progress is saved automatically

### For Instructors
- Update `users-credentials.json` with actual lab credentials
- Each user's progress is independent
- Progress persists across browser sessions

## 🤝 Contributing

This lab guide is part of the WXSD Sales demos. For contributions or issues, please contact the WXSD team.

## 📧 Support

For assistance during the lab:
- Refer to the built-in Troubleshooting section
- Contact your lab instructor
- Email: wxsd@external.cisco.com

## 📅 Version

- **Version:** 1.0
- **Last Updated:** February 2026
- **Estimated Lab Time:** 60 minutes

## 🎓 Learning Objectives

By completing this lab, you will:
- Understand how to integrate WXCC widgets into web applications
- Learn how to authenticate agents using access tokens
- Implement various WXCC widgets step-by-step
- Test the integration with live call scenarios
- Gain hands-on experience with RoomOS and Webex APIs

---

Built with ❤️ by Cisco WXSD Team

