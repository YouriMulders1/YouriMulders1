# Plannify Order Management System - Complete Documentation

## Overview
Plannify is a comprehensive order management system designed for manufacturing and production environments. It provides real-time order tracking, barcode scanning capabilities, user management, and custom reporting features. The system is built with PHP and MySQL, utilizing a Docker-based architecture for easy deployment and scalability.

## Main Pages and Functionality

### 1. Login Page (`login.php`)
**Purpose**: Secure authentication gateway for the Plannify system.

**Features**:
- Modern responsive design with animated elements and particles effect
- Parthos branding with SVG logo integration
- Session management and user authentication
- Secure password verification
- Automatic redirection for already logged-in users

**Buttons**:
- **Login Button**: Authenticates user credentials and creates session

**Access**: Public (unauthenticated users only)

---

### 2. Main Dashboard (`index.php`)
**Purpose**: Central navigation hub and entry point for authenticated users.

**Features**:
- Session validation and login requirement enforcement
- Dynamic page routing based on user permissions
- Header and footer inclusion for consistent UI
- Support for fullscreen modes for certain pages

**Navigation Options**:
- Orders Dashboard
- Fullscreen Orders View
- History
- Page Templates
- Settings
- Notifications

**Access**: All authenticated users

---

### 3. Orders Dashboard (`pages/orders-dashboard.php`)
**Purpose**: Primary interface for viewing and managing active production orders.

**Features**:
- Comprehensive order listing with customizable columns
- Advanced filtering and search capabilities
- Multi-column sorting with individual column sort controls
- Pagination with configurable items per page
- Real-time order status updates
- Lock/unlock functionality for order protection
- User-specific column preferences and visibility settings
- Export capabilities for order data
- Traffic light status indicators for order progress

**Key Buttons**:
- **Search Button**: Executes search across visible order columns
- **Filter Controls**: Apply column-specific filters (date ranges, text filters)
- **Sort Headers**: Click to sort by specific columns (ascending/descending)
- **Lock/Unlock Buttons**: Protect orders from modifications (Admin/Planner only)
- **Edit Buttons**: Modify order details inline
- **Export Button**: Download filtered order data
- **Pagination Controls**: Navigate between order pages
- **Per Page Selector**: Choose number of orders displayed per page
- **Column Visibility Toggle**: Show/hide specific columns
- **Fullscreen Toggle**: Switch to fullscreen view mode

**Access**: All authenticated users (features vary by role)

---

### 4. Fullscreen Orders (`pages/fullscreen-orders.php`)
**Purpose**: Distraction-free fullscreen view of orders for production floor displays.

**Features**:
- Clean, minimalist interface without headers/sidebars
- Same filtering and sorting capabilities as main dashboard
- Optimized for large displays and kiosk modes
- Real-time data refresh capabilities
- Touch-friendly interface elements

**Key Buttons**:
- **Search Controls**: Filter orders by various criteria
- **Sort Controls**: Multi-column sorting options
- **Refresh Button**: Manual data refresh
- **Exit Fullscreen**: Return to normal dashboard view

**Access**: All authenticated users

---

### 5. History Page (`pages/history.php`)
**Purpose**: Archive view for completed orders and historical data analysis.

**Features**:
- Displays all completed orders with full details
- Advanced search across all order fields
- Sortable columns with persistent preferences
- Export functionality for completed orders
- Date range filtering for historical analysis
- Performance metrics and completion statistics

**Key Buttons**:
- **Search Button**: Search through historical order data
- **Sort Headers**: Column-based sorting controls
- **Export Button**: Download historical data
- **Date Range Picker**: Filter by completion dates
- **Clear Filters**: Reset all applied filters

**Access**: All authenticated users

---

### 6. Notifications Page (`pages/notifications.php`)
**Purpose**: Central hub for system notifications and locked order change alerts.

**Features**:
- Real-time notification display
- Locked order change tracking
- Notification categorization and filtering
- Bulk notification management
- Auto-refresh capabilities
- Visual notification counters

**Key Buttons**:
- **Clear All Notifications**: Remove all current notifications
- **Mark as Read**: Individual notification management
- **View Details**: Expand notification information
- **Refresh**: Manual notification update
- **Filter Buttons**: Sort notifications by type/priority

**Access**: All authenticated users

---

### 7. Settings Page (`pages/settings.php`)
**Purpose**: User account management and system configuration center.

**Features**:
- User profile management with avatar upload
- Password change functionality
- Column permission management (Admin only)
- Account creation and user management (Admin only)
- Personal preferences configuration
- Security settings and access controls

**Key Buttons**:
- **Profile Picture Upload**: Change user avatar
- **Save Profile**: Update user information
- **Change Password**: Security credential updates
- **Create User Account**: Add new system users (Admin only)
- **Edit User**: Modify existing user accounts (Admin only)
- **Delete User**: Remove user accounts (Admin only)
- **Column Permissions**: Configure field-level access (Admin only)
- **Save Settings**: Apply configuration changes

**Access**: All authenticated users (Admin features restricted)

---

### 8. Page Templates (`pages/page-templates.php`)
**Purpose**: Custom page creation and management for specialized order views.

**Features**:
- Create custom dashboard layouts
- Define specific column sets for different use cases
- Template sharing between users
- Version control for page templates
- Archive and restore functionality
- Template categorization (Dashboard/Scan pages)

**Key Buttons**:
- **Create Page**: New template creation wizard
- **Edit Template**: Modify existing page layouts
- **Duplicate Page**: Copy template for customization
- **Archive Page**: Remove from active use
- **Restore Page**: Reactivate archived templates
- **View Page**: Preview template layout
- **Delete Page**: Permanently remove template

**Access**: All authenticated users (creation may be restricted)

---

### 9. View Template (`pages/view-template.php`)
**Purpose**: Display orders using custom template configurations.

**Features**:
- Render orders with custom column layouts
- Apply template-specific filters and sorting
- Export data in template format
- Template-based access controls
- Responsive template rendering

**Key Buttons**:
- **Edit Template**: Modify current template
- **Export Data**: Download in template format
- **Back to Templates**: Return to template list
- **Save View**: Store current view state

**Access**: Users with template access permissions

---

## Administrative and Utility Pages

### 10. Barcode Scanner (`barcode-standalone.php`)
**Purpose**: Standalone barcode scanning interface for production floor use.

**Features**:
- Real-time barcode scanning capabilities
- Order lookup by barcode
- Production status updates
- Mobile-optimized interface
- Camera integration for barcode reading
- Manual barcode entry fallback

**Key Buttons**:
- **Start Scanner**: Activate camera for scanning
- **Manual Entry**: Input barcode manually
- **Lookup Order**: Find order by scanned code
- **Update Status**: Modify order progress
- **Clear Scanner**: Reset scanning interface

**Access**: Production users and above

---

### 11. Import Logs Viewer (`view-import-logs.php`)
**Purpose**: Monitor data import processes and troubleshoot import issues.

**Features**:
- Real-time import log display
- Error tracking and reporting
- Import performance metrics
- File processing status
- Historical import data

**Key Buttons**:
- **Refresh Logs**: Update log display
- **Clear Logs**: Remove old log entries
- **Export Logs**: Download log data
- **Filter by Date**: Show specific time periods

**Access**: Admin and Planner roles only

---

### 12. Admin Notification Creator (`admin-create-notification.php`)
**Purpose**: Administrative tool for creating test notifications and system alerts.

**Features**:
- Create test locked order notifications
- Simulate system alerts
- Test notification delivery
- Configure notification parameters

**Key Buttons**:
- **Create Test Notification**: Generate sample notification
- **Clear All**: Remove test notifications
- **Send Alert**: Dispatch system-wide notification

**Access**: Admin and Planner roles only

---

### 13. Database Setup Pages

#### Setup Notifications (`setup-notifications.php`)
**Purpose**: Initialize notification system database tables.

**Key Buttons**:
- **Setup Notifications**: Create required database tables

#### Apply Migrations (`apply-notifications-migration.php`)
**Purpose**: Update database schema for notifications.

#### Build Assets (`build-assets.php`)
**Purpose**: Compile and optimize system assets.

**Key Buttons**:
- **Rebuild Now**: Regenerate all system assets

---

## API Endpoints and Services

### Order Management APIs
- **`api/find-order.php`**: Order search and retrieval
- **`api/scan-order.php`**: Barcode scanning integration
- **`api/scan-order-by-id.php`**: Direct order lookup
- **`api/slotje-api.php`**: Order lock/unlock functionality

### User and Permission APIs
- **`api/users.php`**: User account management
- **`api/column-api.php`**: Column permission management
- **`api/initialize-all-permissions.php`**: Setup default permissions

### Configuration APIs
- **`api/custom-page-api.php`**: Template management
- **`api/sidebar-config-api.php`**: UI configuration
- **`api/machine-status-api.php`**: Production equipment status

### Notification APIs
- **`api/notifications.php`**: Notification management
- **`api/clear-notifications.php`**: Notification cleanup

---

## User Roles and Permissions

### BEHEERDER (Administrator)
- Full system access
- User management capabilities
- Column permission configuration
- System administration tools
- All page access and modification rights

### PLANNER
- Order management and modification
- Lock/unlock order functionality
- Access to planning tools
- Import log viewing
- Limited administrative features

### PRODUCTIE (Production)
- View orders and basic information
- Barcode scanning capabilities
- Status updates for assigned orders
- Limited modification rights

### BEPERKT (Limited)
- Read-only access to orders
- Basic filtering and search
- No modification capabilities
- Restricted column visibility

---

## System Features Summary

### Core Functionality
- **Real-time Order Tracking**: Live updates of production orders
- **Barcode Integration**: Seamless scanning for order lookup
- **Custom Dashboards**: User-defined views and layouts
- **Advanced Filtering**: Multi-column search and filter options
- **Role-based Security**: Granular permission system
- **Notification System**: Real-time alerts and updates
- **Data Export**: Multiple format export capabilities
- **Mobile Responsive**: Touch-friendly interface design

### Technical Features
- **Docker Architecture**: Containerized deployment
- **MySQL Database**: Robust data storage
- **PHP Backend**: Server-side processing
- **RESTful APIs**: Modern service architecture
- **Session Management**: Secure user authentication
- **Asset Pipeline**: Optimized resource delivery

### Integration Capabilities
- **Import Services**: Automated data import from external systems
- **Machine Status**: Production equipment monitoring
- **Scan History**: Tracking of all scanning activities
- **Process Times**: Production timing analysis

This comprehensive documentation covers all major pages, functionality, and features of the Plannify Order Management System, providing users and administrators with a complete understanding of the system's capabilities and operation procedures.
