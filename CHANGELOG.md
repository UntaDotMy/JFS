# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.7.1] - 2025-03-25

### Changed
- Enhanced mobile navigation with improved layout and accessibility
- Optimized mobile menu positioning and scroll behavior
- Streamlined mobile navigation UI by removing redundant theme switcher
- Improved mobile menu portal implementation for better performance
- Updated branding from "Student Feedback" to "Jazro Feedback System" across the application
- Enhanced mobile responsiveness with "JFS" abbreviation for smaller screens

### Fixed
- Fixed mobile menu cutoff issues when scrolling
- Improved mobile menu visibility and interaction on all screen sizes
- Enhanced mobile navigation accessibility and usability
- Resolved z-index conflicts in mobile navigation

## [1.7.0] - 2025-03-25

### Added
- Advanced filtering, pagination, and search functionality for completed classes in Classes page
- Advanced filtering, pagination, and search functionality for completed classes in Reports page
- Enhanced Live Preview interface with better visualization of student responses
- Improved awaiting responses UI with student avatars and status indicators
- Student information cards with clear visual hierarchy and status indicators
- Modals with better information architecture and visual organization
- Page size selection for completed class lists (5, 10, 15, or 20 per page)
- Multiple sorting options (date, name, student count) for completed classes
- Visual pagination controls with numbered page navigation
- Sort direction toggle with clear visual indicators

### Changed
- Completely redesigned Live Preview interface with modern UI elements
- Enhanced modal interfaces for Awaiting and Revoke actions
- Improved dark mode visibility for user interface elements
- Refined QR code display with better visual instructions
- Streamlined user interface for class management
- Better visual hierarchy for completed and in-progress classes
- More intuitive layout for student submission tracking
- Optimized student lists for better readability and information density

### Fixed
- Visual contrast issues in dark mode for certain UI elements
- Duplicate student ID generation for students with the same name
- Emoji randomization for student submissions in live preview
- Removed redundant UI elements to improve clarity and focus
- Fixed unnecessary counters that duplicated information
- Improved name handling for students with identical names

## [1.6.0] - 2025-03-25

### Added
- Enhanced profile management with visual password strength indicators
- Dynamic user avatars with personalized color schemes based on user initials
- Interactive profile dropdown with user context and quick actions
- Success animations and visual feedback for form submissions
- Improved form validation with real-time feedback
- Modern profile page with tabbed interface for better organization
- Password strength meter with visual feedback during password creation/update
- Admin badge indicators across the interface for better role visibility

### Changed
- Completely redesigned profile page with modern UI elements
- Enhanced header with decorative patterns and user information
- Streamlined navigation with intuitive tab indicators
- Improved form layouts with better visual hierarchy
- More intuitive input fields with contextual icons
- Better visual feedback for error states and validation
- Refined color scheme with subtle gradients and transitions
- Improved mobile experience with responsive adjustments

### Fixed
- Inconsistent form styles across the application
- Profile information update flow and validation
- Dropdown menu positioning and interaction issues
- Visual feedback during form submission
- Layout issues on smaller screens
- Improved error state handling in password fields

## [1.5.0] - 2025-03-23

### Added
- Parent interaction analytics dashboard for tracking registration and WhatsApp contacts
- Analytics data visualization for user engagement metrics
- Registration option clicks tracking with detailed information
- WhatsApp contact button interaction tracking
- Class completion status enforcement to prevent feedback on completed classes

### Changed
- Improved mobile tooltip behavior for better user experience
- Enhanced table UI with text truncation and tooltips for long content
- Better contrast for registration type badges in dark mode
- Optimized data structure for analytics storage in Firebase
- Removed debugging delays in feedback form navigation for smoother user experience

### Fixed
- Mobile layout issues with tooltip positioning and behavior
- Fixed data persistence issues in Firebase analytics tracking
- Improved error handling for invalid timestamps
- Enhanced table hover behavior in dark mode for better readability

## [1.4.1] - 2025-03-03

### Added
- Vercel Analytics integration for visitor and page view tracking

## [1.4.0] - 2025-03-03

### Added
- Support for multi-child voting in the same session
- Enhanced dashboard animations with hardware acceleration
- Better animation timing and easing functions for smoother transitions

### Changed
- Improved profile menu behavior with click-outside detection
- Enhanced Reports page design to match dashboard principles
- Optimized card animations for better performance on all devices
- Better visual hierarchy in dashboard components
- Updated card designs with consistent styles and improved responsiveness
- Fixed teacher name retrieval for live feedback sessions

### Fixed
- Profile dropdown now closes when clicking anywhere outside the menu
- Inconsistent animation smoothness across the dashboard
- Improved loading states with better indicators
- Fixed teacher name not showing correctly in feedback form
- Multiple children from same family can now vote in one session without redirection

## [1.3.0] - 2025-01-08

### Added
- System status page with real-time service monitoring
- Service uptime tracking and history visualization
- Incident reporting and management for administrators
- Enhanced QR code generation with downloadable styled images
- Service health checks with response time monitoring
- Status history bar showing 90-day service status
- System metrics visualization with customizable time ranges

### Changed
- Improved QR code download functionality with better visibility
- Enhanced status monitoring with detailed service information
- Updated admin controls for service testing and incident management
- Optimized code base by removing unused declarations
- Improved error handling and user feedback

### Security
- Added role-based access control for system status management
- Implemented secure service health checks
- Enhanced error handling for API endpoints

## [1.2.0] - 2024-11-20

### Added
- Real-time user presence tracking with online/offline status
- Enhanced Excel export with improved formatting and styling
- Staff registration with magic code authentication
- Theme toggle with dark mode persistence
- QR code generation for class access
- Comprehensive admin dashboard with user management
- Student vote reset functionality
- Class status tracking (active/completed)

### Changed
- Improved user interface with responsive design
- Enhanced authentication flow with better error handling
- Updated class management system with edit restrictions
- Modernized dashboard with real-time statistics
- Streamlined feedback submission process

### Security
- Added magic code verification for staff registration
- Implemented user session management
- Enhanced role-based access control
- Added input validation and sanitization

## [1.1.0] - 2023-11-19

### Changed
- Updated report format from CSV to XLSX for better formatting and readability
- Added company logo to improve branding
- Enhanced mobile theme support for better responsive design
- Improved UI/UX with multiple version updates (v11-v13)
- Updated application title for better clarity

### Added
- Excel export functionality with custom styling and formatting
- Enhanced report generation with conditional formatting
- Mobile-responsive design improvements
- Dark mode support across all components

## [1.0.0] - 2023-11-12

### Added
- Initial release of Jazro Student Vote
- Real-time voting and feedback collection system
- QR code generation functionality
- Interactive charts and data visualization
- Excel export capability
- Firebase integration for data persistence
- Authentication and authorization system
- Responsive design with Tailwind CSS
- Documentation and contribution guidelines

### Security
- Environment variables for sensitive data
- Firebase Authentication implementation
- Input validation and sanitization
- Role-based access control
