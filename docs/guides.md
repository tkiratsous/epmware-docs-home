# Documentation Guides

EPMware provides comprehensive documentation across seven main guides, each tailored for specific user roles and use cases.

### :material-rocket-launch: Quick Start Guide

The Quick Start Guide provides high-level steps to rapidly deploy and configure your first EPMware application, perfect for getting started quickly.

**Key Topics Covered:**
- Adding target application servers
- Creating EPMware applications
- Changing default Admin user security
- Updating global settings (Email, Application, UDF)
- Starting essential services
- Creating workflows
- Creating deployments

**Target Audience:**
- New EPMware Users
- System Administrators (Initial Setup)
- POC/Trial Users
- Teams needing rapid deployment

[:octicons-link-external-16: Open Quick Start Guide](https://quick-start.epmware.com/){ .md-button .md-button--primary target="_blank" }

---

### :material-shield-account: Administrator's Guide

The Administrator's Guide is essential for system administrators responsible for EPMware configuration, management, and maintenance.

**Key Topics Covered:**
- System configuration
- Security setup and user management
- Application and dimension configuration
- Workflow administration
- System maintenance and troubleshooting
- Performance optimization
- Backup and recovery procedures

**Target Audience:**
- System Administrators
- IT Managers
- Database Administrators
- Security Administrators

[:octicons-link-external-16: Open Administrator's Guide](https://admin-guide.epmware.com/){ .md-button .md-button--primary target="_blank" }

---

### :material-account-circle: User Guide

The User Guide provides end users with detailed instructions on using EPMware for daily metadata management tasks.

**Key Topics Covered:**
- EPMware navigation and interface
- Working with hierarchies and members
- Managing properties and attributes
- Creating and submitting requests
- Running reports and analytics
- Import/Export operations
- Collaboration features

**Target Audience:**
- Business Users
- Data Stewards
- Business Analysts
- Department Managers

[:octicons-link-external-16: Open User Guide](https://user-guide.epmware.com/){ .md-button .md-button--primary target="_blank" }

---

### :material-code-tags: Logic Builder Guide

The Logic Builder Guide is designed for developers and technical users who need to extend EPMware functionality through custom scripts.

**Key Topics Covered:**
- Logic script development
- PL/SQL programming in EPMware
- Event-driven architecture
- API reference and usage
- Custom workflow development
- Integration patterns
- Debugging and troubleshooting

**Target Audience:**
- Developers
- Technical Consultants
- System Integrators
- Advanced Administrators

[:octicons-link-external-16: Open Logic Builder Guide](https://logic-builder-guide.epmware.com/){ .md-button .md-button--primary target="_blank" }

---

### :material-server-network: Agent Installation Guide

The Agent Installation Guide provides detailed instructions for installing and configuring EPMware On-Premise Agents to enable integration between EPMware Cloud and on-premise target applications.

**Key Topics Covered:**
- Agent architecture and requirements
- Cygwin installation for Windows servers
- Agent installation and configuration
- REST API token management
- Application-specific setup (HFM, Planning, PCMCS)
- EPM Automate configuration
- Scheduled task configuration
- Troubleshooting and log analysis

**Target Audience:**
- Infrastructure Engineers
- System Administrators
- Integration Specialists
- Cloud Architects

[:octicons-link-external-16: Open Agent Installation Guide](https://agent-install-guide.epmware.com/){ .md-button .md-button--primary target="_blank" }

---

### :material-api: REST API Guide

The REST API Guide provides comprehensive documentation for EPMware's RESTful API, enabling developers to programmatically interact with EPMware and build custom integrations.

**Key Topics Covered:**
- API authentication and token management
- Complete endpoint reference
- Request/Response formats and examples
- Data models and schemas
- Pagination and filtering
- Rate limiting and best practices
- Error handling and status codes
- Integration patterns and use cases

**Target Audience:**
- API Developers
- Integration Engineers
- DevOps Teams
- Automation Specialists

[:octicons-link-external-16: Open REST API Guide](https://rest-api-guide.epmware.com/){ .md-button .md-button--primary target="_blank" }

---

### :material-package-variant: On-Premise Installation Guide

The On-Premise Installation Guide provides detailed instructions for installing EPMware components in your own data center, including database setup, application server configuration, and integration with target applications.

**Key Topics Covered:**
- Hardware and software requirements
- Oracle database installation and configuration
- Tablespace and schema creation
- Database object installation
- Apache Tomcat installation and configuration
- EPMware application deployment
- JDBC properties configuration
- Application-specific tasks (HFM, Planning, PCMCS)
- Cygwin installation for Windows servers
- Environment variable configuration

**Target Audience:**
- Infrastructure Engineers
- Database Administrators
- System Administrators
- IT Operations Teams

[:octicons-link-external-16: Open On-Premise Installation Guide](https://install-guide.epmware.com/){ .md-button .md-button--primary target="_blank" }

## Quick Navigation Matrix

| Task | Quick Start | Administrator's Guide | User Guide | Logic Builder Guide | Agent Installation Guide | REST API Guide | On-Premise Install |
|------|------------|----------------------|------------|-------------------|-------------------------|----------------|-------------------|
| Initial Setup | ✅ Primary | ✅ Configuration | ✅ Reference | - | ✅ Agent Setup | ✅ API Setup | ✅ Detailed |
| Database Setup | ✅ Overview | ✅ Reference | - | - | - | - | ✅ Primary |
| Application Server | ✅ Overview | ✅ Configuration | - | - | - | - | ✅ Primary |
| User Management | ✅ Basic | ✅ Primary | - | - | - | ✅ API Calls | - |
| Hierarchy Operations | - | ✅ Setup | ✅ Primary | ✅ Automation | - | ✅ API Endpoints | - |
| Property Management | - | ✅ Configuration | ✅ Primary | ✅ Validation | - | ✅ API Operations | - |
| Workflow Configuration | ✅ Basic | ✅ Primary | ✅ Usage | ✅ Customization | - | ✅ Automation | - |
| Custom Logic | - | - | - | ✅ Primary | - | - | - |
| Reporting | - | ✅ Setup | ✅ Primary | - | - | ✅ Data Retrieval | - |
| Troubleshooting | - | ✅ System | ✅ User Issues | ✅ Scripts | ✅ Agent Issues | ✅ API Errors | ✅ Installation |
| API Integration | - | ✅ Configuration | - | ✅ Primary | ✅ REST API | ✅ Primary | - |
| Security | ✅ Basic | ✅ Primary | ✅ Understanding | ✅ API Access | ✅ Token Management | ✅ Authentication | ✅ DB Security |
| Cloud Integration | - | ✅ Configuration | - | - | ✅ Primary | ✅ Cloud APIs | - |
| On-Premise Setup | - | ✅ Reference | - | - | ✅ Agent Setup | - | ✅ Primary |
| Automation | - | ✅ Scheduling | - | ✅ Scripts | - | ✅ Primary | - |

## Learning Paths

### For Quick Start Users
1. Start with the **Quick Start Guide** - Overview
2. Add target application server
3. Create your first EPMware application
4. Configure basic security
5. Start essential services
6. Create your first workflow

### For Infrastructure Teams
1. Start with the **On-Premise Installation Guide** - Prerequisites
2. Install and configure Oracle database
3. Set up Apache Tomcat application server
4. Deploy EPMware application
5. Configure application-specific integrations

### For New Users
1. Optionally review the **Quick Start Guide** for rapid overview
2. Start with the **User Guide** - Getting Started section
3. Learn basic navigation and hierarchy management
4. Practice with property management
5. Understand the request and workflow process

### For Administrators
1. Complete **Quick Start Guide** for initial setup
2. Complete **On-Premise Installation** if applicable
3. Review **Administrator's Guide** - Configuration
4. Configure security and user access
5. Set up applications and dimensions
6. Learn maintenance procedures

### For Developers
1. Review **Logic Builder Guide** - Getting Started
2. Understand the script structure and events
3. Learn the API reference
4. Practice with example scripts

### For Integration Engineers
1. Install EPMware using **On-Premise Installation Guide**
2. Follow **Agent Installation Guide** - Prerequisites
3. Install and configure the agent on target servers
4. Set up application-specific configurations
5. Configure scheduled tasks for continuous operation
6. Test connectivity and monitor logs

### For API Developers
1. Begin with **REST API Guide** - Authentication
2. Understand the API architecture and endpoints
3. Learn request/response formats
4. Practice with API testing tools
5. Implement error handling and retry logic
6. Build automated integrations

## Documentation Standards

All EPMware documentation follows these standards:

- **Consistent Structure** - Each guide follows a logical progression from basic to advanced topics
- **Visual Examples** - Screenshots and diagrams illustrate key concepts
- **Code Examples** - Working examples with detailed explanations
- **Best Practices** - Industry-standard recommendations throughout
- **Cross-References** - Links between related topics across guides
- **Version Specific** - Documentation matches the current EPMware version

## Feedback and Updates

We continuously improve our documentation based on user feedback. If you have suggestions or find any issues:

- Email: support@epmware.com
- Include the guide name and page/section
- Describe the issue or suggestion clearly
- Screenshots are helpful for reporting issues

!!! tip "Documentation Search"
    Use the search feature (🔍) in each guide to quickly find specific topics. The search indexes all content including code examples and API references.
