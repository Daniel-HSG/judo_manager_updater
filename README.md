# Judo Tournament Admin - Installation Guide

## System Requirements

- **Operating System:** Windows 10/11 (64-bit)
- **Backend Server:** Judo Tournament Manager Server must be running on the same network
- **Network:** Connection to the backend server (default: localhost:8001 for HTTP, localhost:8000 for HTTPS)

## Installation

1. Download the latest `Judo Tournament Admin Setup x.x.x.exe` from the releases
2. Run the installer
3. Follow the installation wizard
4. Launch "Judo Tournament Admin" from the Start Menu or Desktop shortcut

## First-Time Setup

1. Start the Judo Tournament Manager backend server
2. Launch the Judo Tournament Admin application
3. Log in with your admin credentials
4. Go to **Application Settings** to configure:
   - Backend API URL (if not using default localhost)
   - License code (required for weight grouping features)

## License

A valid license is required to use the full functionality of this application.

**Free features (no license required):**
- Basic tournament management
- Participant registration
- Scoreboard operation
- Fight scheduling

**Licensed features:**
- Automatic weight grouping algorithm
- Advanced tournament brackets

To obtain a license, contact the application provider. Enter your license code in **Application Settings > License Code** and click "Validate".

## Backend Server Requirements

The application requires the Judo Tournament Manager backend server to be running. The backend provides:

- User authentication
- Tournament data management
- Real-time fight updates
- Update notifications

Contact your system administrator for backend server setup and credentials.

## Updates

The application automatically checks for updates:
- On first launch
- After each login
- Every 2 hours while running

When an update is available:
1. You will see a notification popup
2. Go to **Application Settings > Updates** to download
3. Run the new installer to update

**Note:** Some features (like weight grouping) require the latest version to be installed.

## Troubleshooting

### Cannot connect to server
- Verify the backend server is running
- Check the API URL in Application Settings
- Ensure your firewall allows the connection

### White screen after login
- Restart the application
- Clear browser cache (Ctrl+Shift+Delete in DevTools)
- Verify backend server is responding

### Login fails
- Verify your credentials with your administrator
- Check if the backend server is reachable
- Ensure you're using the correct API URL

## Support

For issues and feature requests, contact your system administrator.

---

**Version:** 1.0.0
**Platform:** Windows (x64)
