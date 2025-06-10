# Changelog

All notable changes to the Jazro Student Vote project will be documented in this file.

## [1.8.7] - 2025-06-10

### Changed
- **Updated Online Class Coupon Code**: Changed coupon code for Wednesday online classes from "REGSEL" to "REGRAB"
  - Affects both class creation and feedback form coupon display
  - Updated coupon logic in `Classes.tsx` and `FeedbackForm.tsx`
- **Dependency Cleanup**: Removed unused Three.js dependencies to optimize bundle size
  - Removed `@react-three/fiber`, `@react-three/drei`, and `three` packages

### Fixed
- Improved package.json structure by removing unnecessary 3D graphics dependencies

## [1.8.6] - 2025-04-16

### Changed
- **Redesigned Feedback Form (`FeedbackForm.tsx`)**:
  - Modernized layout with improved spacing, cards, and visual hierarchy.
  - Enhanced header section for class details.
  - Updated accordion style for "Important Question" and "How to Vote" sections.
  - Improved mobile responsiveness, especially for student voting buttons.
  - Relocated theme and language toggles to the top-right corner for better usability.
  - Adjusted feedback option card layout (icon top, title, text) and added theme-aware borders.
- Updated `README.md` to reflect UI changes.

### Fixed
- Corrected registration analytics tracking: `registrationType` is now set to "Online Class (jazarian)" for classes with location "ONLINE".


## [1.8.5] - 2025-04-10

### Changed
- Redesigned User Profile page (`Profile.tsx`) for a modern look and improved mobile responsiveness.
- Adjusted header layout, avatar positioning, and spacing.
- Refined form input styles, labels, and password strength indicator.
- Updated tab navigation styling for desktop and mobile (using a grid for mobile tabs).
- Fixed avatar cutoff issue on mobile view.


## [1.8.4] - 2025-04-10

### Added
- Site-wide maintenance mode, toggleable by admin via Firebase (`/config/maintenanceMode`).
- `MaintenanceWrapper` component to restrict access during maintenance (excludes `/login`).
- Dedicated maintenance page (`MaintenancePage.tsx`) with bilingual text (Malay/English), animated SVG, and contact information.
- Dedicated error page (`ErrorPage.tsx`) for routing errors (404 etc.) with contact info.
- Automatic cleanup of leading numbers/whitespace from pasted student lists in "Create Class".

### Changed
- Refactored maintenance check logic from `PrivateRoute` to `MaintenanceWrapper`.
- Updated `App.tsx` routing structure to use `MaintenanceWrapper` and `ErrorPage`.
- Improved coupon modal UI and SVG ticket design (`CouponTicketSVG`).
- Improved copy-to-clipboard mechanism for coupon code with fallback (`document.execCommand`).
- Made coupon modal non-dismissible via backdrop click.
- Adjusted text sizes and layout on maintenance page for compactness and hierarchy.

### Fixed
- Potential inability for non-admins to access `/login` during maintenance mode.
- Fixed typing issue with `Layout` component receiving `children` in `App.tsx`.

## [1.8.3] - 2025-04-09

### Added
- Three-step class creation process for improved mobile UX
- Animated UI transitions for location and program selection
- Interactive selection UI with fade and slide animations
- Custom CSS animations in index.css
- VSCode settings for ignoring CSS linting errors

### Changed
- Enhanced coupon display with larger, more readable code
- Improved discount coupon modal layout and text sizing
- Streamlined discount claiming with instant navigation
- Removed unnecessary fullscreen mode from class creation
- Reorganized form steps for better mobile experience

### Fixed
- Resolved TypeScript error with unused ChevronDown import
- Fixed CSS linting issues with @variant rule
- Improved mobile form layout on smaller screens
- Enhanced coupon code visibility and copying UX

## [1.8.2] - 2025-04-08

### Fixed
- Fixed Firebase update error when submitting feedback with undefined referrals
- Improved error handling for form submissions
- Enhanced validation for parent referrals
- Fixed language switching persistence
- Resolved dark mode toggle state synchronization

### Added
- Improved error messages for form validation
- Enhanced logging for debugging form submissions
- Better type checking for form data

## [1.8.1] - 2025-04-02

### Added
- Language switching functionality (English/Bahasa Melayu)
- Instant language updates for all UI elements
- Language toggle button in header
- Translations for all form text and messages
- Language state persistence

### Changed
- Updated WhatsApp link to https://wsap.to/hotline
- Improved form validation messages
- Enhanced error handling for form submissions
- Updated UI text and instructions

## [1.8.0] - 2025-04-01

### Added
- Parent referral system for Option 3
- Required text input for three parent referrals
- Database storage for referral information
- Analytics tracking for referrals
- Parent Interaction Analytics dashboard
- Referral data table in dashboard
- Malaysian phone number validation
- Duplicate phone number detection

### Changed
- Updated form validation for referrals
- Enhanced error messages
- Improved database structure for referrals
- Updated analytics tracking

## [1.7.0] - 2025-03-31

### Added
- Dark mode support
- System preference detection
- Theme toggle button
- Persistent theme preference
- Dark mode styles for all components

### Changed
- Updated color scheme
- Improved contrast ratios
- Enhanced accessibility
- Updated component styles

## [1.6.0] - 2025-03-30

### Added
- Real-time analytics dashboard
- Feedback tracking
- Student participation metrics
- Class performance indicators
- Data visualization components

### Changed
- Updated dashboard layout
- Improved data presentation
- Enhanced user interface
- Optimized performance

## [1.5.0] - 2025-03-29

### Added
- Firebase integration
- Real-time database updates
- Authentication system
- User management
- Security rules

### Changed
- Updated project structure
- Improved error handling
- Enhanced security
- Optimized performance

## [1.4.0] - 2025-03-28

### Added
- Responsive design
- Mobile optimization
- Tablet support
- Cross-browser compatibility
- Touch interactions

### Changed
- Updated layout system
- Improved navigation
- Enhanced accessibility
- Optimized performance

## [1.3.0] - 2025-03-27

### Added
- Student feedback form
- Parent information collection
- Form validation
- Error handling
- Success messages

### Changed
- Updated form design
- Improved user experience
- Enhanced validation
- Optimized performance

## [1.2.0] - 2025-03-26

### Added
- Class management
- Student tracking
- Attendance system
- Status updates
- Progress monitoring

### Changed
- Updated class structure
- Improved organization
- Enhanced tracking
- Optimized performance

## [1.1.0] - 2025-03-25

### Added
- Basic project structure
- Component framework
- Routing system
- State management
- Utility functions

### Changed
- Initial setup
- Project configuration
- Development environment
- Build system

## [1.0.0] - 2025-03-24

### Added
- Initial release
- Core functionality
- Basic features
- Project setup
- Documentation

### Changed
- First version
- Base implementation
- Initial structure
- Basic configuration
