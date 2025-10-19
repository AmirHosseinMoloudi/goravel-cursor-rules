# 🚀 Goravel Cursor Rules

**The Ultimate Collection of Cursor AI Rules for Goravel Framework Development**

A comprehensive, production-ready collection of 50+ specialized Cursor AI rules for Goravel framework development, ensuring consistent, maintainable, and high-quality Go applications with seamless AI-LLM collaboration.

## ✨ What Makes This Special

- **🎯 Framework-Specific**: Tailored specifically for Goravel framework conventions
- **🤖 AI-Optimized**: Designed for seamless AI-LLM collaboration and human-developer friendly code
- **🚀 Production-Ready**: Battle-tested patterns, one-click deployment, and comprehensive testing
- **📚 Comprehensive Coverage**: From basic setup to advanced deployment and everything in between
- **🔒 Security-First**: Built-in security best practices, authentication, and authorization
- **📖 Self-Documenting**: Every rule includes comprehensive documentation with examples

## 🏗️ Complete Architecture Coverage

### 🎯 Core Framework Rules
- **Installation & Setup**: Complete project initialization and configuration
- **Directory Structure**: Organized, scalable project structure
- **Configuration Management**: Environment-specific configurations
- **Compilation & Deployment**: Production-ready build processes
- **Request Lifecycle**: Understanding Goravel's request processing
- **Service Container**: Dependency injection and service management
- **Service Providers**: Modular service registration
- **Facades**: Static access to framework services
- **Versioning & Releases**: Semantic versioning and release management

### 🌐 HTTP & API Development
- **Fiber HTTP Driver**: High-performance HTTP server (MANDATORY)
- **Routing**: RESTful API routing with middleware
- **Middleware**: Request/response processing pipeline
- **Controllers**: Clean, organized controller patterns
- **Requests**: Input validation and data binding
- **Responses**: Consistent response formatting
- **Views**: Template rendering and view management
- **gRPC**: Microservices communication
- **Session Management**: User session handling
- **Validation**: Comprehensive input validation
- **Logging**: Structured logging and monitoring

### 🔐 Security & Authentication
- **Authentication**: JWT tokens, session-based auth, multi-guard support
- **Authorization**: Gates, policies, role-based access control
- **Encryption**: Data encryption and secure storage
- **Hashing**: Password hashing and verification
- **Security Guidelines**: Comprehensive security best practices

### 🗄️ Database & Data Management
- **Database Setup**: Multi-database support (MySQL, PostgreSQL, SQLite)
- **Query Builder**: Fluent database query interface
- **Migrations**: Version-controlled database schema changes
- **Seeding**: Database seeding and test data
- **ORM Getting Started**: Object-relational mapping basics
- **ORM Relationships**: Model relationships and associations
- **ORM Factories**: Test data generation
- **ORM Enforcement**: Data integrity and constraints

### 🧪 Testing & Quality Assurance
- **Testing Getting Started**: Unit, integration, and feature testing
- **HTTP Tests**: API endpoint testing with assertions
- **Mock Testing**: Complete facade mocking for isolated testing
- **Database Testing**: Model factories, seeders, Docker testing
- **Test Organization**: Structured test suites and best practices

### 📚 API Documentation & Integration
- **Swagger/OpenAPI**: Complete API documentation with Swagger
- **Postman Collections**: Automated Postman collection generation
- **API Standards**: RESTful API design patterns
- **Request/Response Models**: Structured API models
- **Authentication Documentation**: Complete auth flow documentation

### ⚡ Advanced Features
- **Artisan Console**: Command-line interface and custom commands
- **Cache System**: Redis, memory, and custom cache drivers
- **Event System**: Event-driven architecture
- **File Storage**: Local and cloud storage management
- **Mail System**: Email sending and templates
- **Queue System**: Background job processing
- **Task Scheduling**: Cron-like task management
- **Localization**: Multi-language support
- **Package Development**: Custom package creation
- **Color Output**: Terminal color formatting
- **String Utilities**: String manipulation helpers
- **Helper Functions**: Utility functions and helpers
- **HTTP Client**: External API integration

### 🎨 Code Quality & Standards
- **Human-AI Friendly Code**: Optimized for both human and AI collaboration
- **Backward Compatibility**: Maintain API and code compatibility
- **Structure Monitoring**: Continuous monitoring of existing patterns
- **File Separation**: Maximum modularity with single-responsibility files
- **Go Coding Standards**: Go best practices and conventions
- **Laravel Conventions**: Laravel-style patterns in Go
- **Performance Optimization**: Speed and resource optimization
- **Project Structure**: Scalable project organization
- **Security Guidelines**: Comprehensive security practices
- **Testing Guidelines**: Testing best practices and patterns

### 🚀 DevOps & Deployment
- **Production-Ready Deployment**: One-click deployment with Docker
- **Docker Configuration**: Multi-stage builds and optimization
- **Environment Management**: Development, staging, production configs
- **CI/CD Pipeline**: Automated testing and deployment
- **Database Migrations**: Production database management
- **Monitoring & Observability**: Application monitoring and logging
- **Backup & Recovery**: Data protection and disaster recovery
- **Security in Deployment**: Secure deployment practices
- **Scaling Strategies**: Horizontal and vertical scaling
- **Infrastructure as Code**: Terraform and automation

## 🎯 Key Features

### 🤖 AI-LLM Optimized
- **Human-Developer Friendly**: Clear, readable code with comprehensive comments
- **AI-Friendly Structure**: Predictable patterns and consistent naming
- **Self-Documenting**: Every function, struct, and interface is well-documented
- **Type Safety**: Explicit types and interfaces for better AI understanding
- **Consistent Patterns**: Standardized approaches across all components

### 🚀 Production-Ready
- **One-Click Deployment**: Complete Docker setup with health checks
- **Performance Optimized**: Fiber HTTP driver, caching, and optimization
- **Security Hardened**: Authentication, authorization, encryption, and security
- **Monitoring Ready**: Logging, metrics, and observability built-in
- **Scalable Architecture**: Microservices-ready with gRPC support

### 🧪 Testing Excellence
- **Comprehensive Testing**: Unit, integration, HTTP, database, and mock testing
- **Test Automation**: Automated test generation and execution
- **Docker Testing**: Isolated test environments
- **Mock Testing**: Complete facade mocking for isolated testing
- **Test Coverage**: High test coverage with realistic scenarios

### 📚 Documentation Excellence
- **Swagger/OpenAPI**: Complete API documentation
- **Postman Collections**: Ready-to-import API collections
- **Code Documentation**: Comprehensive inline documentation
- **Best Practices**: Detailed guidelines and examples
- **Examples**: Real-world usage examples

## 🛠️ Quick Start

### 1. Installation
```bash
# Clone or download the rules
git clone https://github.com/AmirHosseinMoloudi/goravel-cursor-rules
cd goravel-cursor-rules

# Copy rules to your Goravel project
cp -r .cursor/rules/ /path/to/your/goravel/project/.cursor/
```

### 2. Configuration
```bash
# Generate application key
go run . artisan key:generate

# Generate JWT secret
go run . artisan jwt:secret

# Run database migrations
go run . artisan migrate

# Seed database
go run . artisan db:seed
```

### 3. Development
```bash
# Start development server
go run . artisan serve

# Run tests
go test ./...

# Generate API documentation
go run . artisan api:generate-postman
```

### 4. Production Deployment
```bash
# One-click deployment
./deploy.sh

# Or using Docker
docker-compose up -d
```

## 📁 Rule Structure

```
.cursor/rules/
├── 🎯 Core Framework
│   ├── goravel-installation-setup.mdc
│   ├── goravel-configuration.mdc
│   ├── goravel-directory-structure.mdc
│   ├── goravel-compilation-deployment.mdc
│   ├── goravel-architecture-lifecycle.mdc
│   ├── goravel-service-container.mdc
│   ├── goravel-service-providers.mdc
│   ├── goravel-facades.mdc
│   └── goravel-versioning-releases.mdc
├── 🌐 HTTP & API
│   ├── goravel-fiber-http-driver.mdc
│   ├── goravel-routing.mdc
│   ├── goravel-middleware.mdc
│   ├── goravel-controllers.mdc
│   ├── goravel-requests.mdc
│   ├── goravel-responses.mdc
│   ├── goravel-views.mdc
│   ├── goravel-grpc.mdc
│   ├── goravel-session.mdc
│   ├── goravel-validation.mdc
│   ├── goravel-logging.mdc
│   └── goravel-api-documentation.mdc
├── 🔐 Security
│   ├── goravel-authentication.mdc
│   ├── goravel-authorization.mdc
│   ├── goravel-encryption.mdc
│   └── goravel-hashing.mdc
├── 🗄️ Database
│   ├── goravel-database-getting-started.mdc
│   ├── goravel-query-builder.mdc
│   ├── goravel-migrations.mdc
│   ├── goravel-seeding.mdc
│   ├── goravel-orm-getting-started.mdc
│   ├── goravel-orm-relationships.mdc
│   ├── goravel-orm-factories.mdc
│   └── goravel-orm-enforcement.mdc
├── 🧪 Testing
│   ├── goravel-testing-getting-started.mdc
│   ├── goravel-http-tests.mdc
│   └── goravel-mock.mdc
├── ⚡ Advanced Features
│   ├── goravel-artisan-console.mdc
│   ├── goravel-cache.mdc
│   ├── goravel-event.mdc
│   ├── goravel-file-storage.mdc
│   ├── goravel-mail.mdc
│   ├── goravel-queues.mdc
│   ├── goravel-task-scheduling.mdc
│   ├── goravel-localization.mdc
│   ├── goravel-color-output.mdc
│   ├── goravel-strings.mdc
│   ├── goravel-helpers.mdc
│   └── goravel-http-client.mdc
├── 🎨 Code Quality
│   ├── goravel-human-ai-friendly.mdc
│   ├── goravel-backward-compatibility.mdc
│   ├── goravel-structure-monitoring.mdc
│   ├── goravel-file-separation.mdc
│   ├── go-coding-standards.mdc
│   ├── laravel-conventions.mdc
│   ├── performance-optimization.mdc
│   ├── project-structure.mdc
│   ├── security-guidelines.mdc
│   └── testing-guidelines.mdc
└── 🚀 DevOps
    ├── goravel-production-ready-deployment.mdc
    ├── goravel-comprehensive-best-practices.mdc
    └── deployment-devops.mdc
```

## 🎯 Rule Categories

### 🎯 Core Framework (9 rules)
- **Installation & Setup**: Complete project initialization
- **Configuration**: Environment and application settings
- **Directory Structure**: Organized project layout
- **Compilation**: Build and deployment processes
- **Architecture**: Request lifecycle and framework concepts
- **Service Container**: Dependency injection
- **Service Providers**: Modular service registration
- **Facades**: Static service access
- **Versioning**: Release management

### 🌐 HTTP & API (12 rules)
- **Fiber HTTP Driver**: High-performance server (MANDATORY)
- **Routing**: RESTful API routing
- **Middleware**: Request/response processing
- **Controllers**: Clean controller patterns
- **Requests**: Input validation
- **Responses**: Response formatting
- **Views**: Template rendering
- **gRPC**: Microservices communication
- **Session**: User session management
- **Validation**: Input validation
- **Logging**: Structured logging
- **API Documentation**: Swagger/OpenAPI + Postman

### 🔐 Security (4 rules)
- **Authentication**: JWT, session-based auth
- **Authorization**: Gates, policies, RBAC
- **Encryption**: Data encryption
- **Hashing**: Password security

### 🗄️ Database (8 rules)
- **Database Setup**: Multi-database support
- **Query Builder**: Fluent queries
- **Migrations**: Schema versioning
- **Seeding**: Test data
- **ORM Basics**: Object-relational mapping
- **ORM Relationships**: Model associations
- **ORM Factories**: Test data generation
- **ORM Enforcement**: Data integrity

### 🧪 Testing (3 rules)
- **Testing Basics**: Unit, integration, feature tests
- **HTTP Tests**: API endpoint testing
- **Mock Testing**: Complete facade mocking

### ⚡ Advanced Features (12 rules)
- **Artisan Console**: CLI commands
- **Cache**: Redis, memory caching
- **Events**: Event-driven architecture
- **File Storage**: Local/cloud storage
- **Mail**: Email system
- **Queues**: Background jobs
- **Task Scheduling**: Cron-like tasks
- **Localization**: Multi-language
- **Package Development**: Custom packages
- **Color Output**: Terminal formatting
- **Strings**: String utilities
- **Helpers**: Utility functions
- **HTTP Client**: External API integration

### 🎨 Code Quality (10 rules)
- **Human-AI Friendly**: Optimized collaboration
- **Backward Compatibility**: API compatibility
- **Structure Monitoring**: Pattern monitoring
- **File Separation**: Maximum modularity
- **Go Standards**: Go best practices
- **Laravel Conventions**: Laravel-style patterns
- **Performance**: Optimization
- **Project Structure**: Organization
- **Security**: Security practices
- **Testing**: Testing guidelines

### 🚀 DevOps (3 rules)
- **Production Deployment**: One-click deployment
- **Best Practices**: Comprehensive guidelines
- **DevOps**: CI/CD and infrastructure

## 🚀 Production Features

### 🎯 One-Click Deployment
- **Docker Configuration**: Multi-stage builds, health checks
- **Environment Management**: Dev, staging, production configs
- **Database Setup**: Automated migrations and seeding
- **Security Configuration**: HTTPS, authentication, authorization
- **Monitoring**: Health checks, metrics, logging
- **Scaling**: Horizontal and vertical scaling support

### 🧪 Comprehensive Testing
- **Unit Testing**: Individual component testing
- **Integration Testing**: Component interaction testing
- **HTTP Testing**: API endpoint testing with assertions
- **Database Testing**: Model testing with factories
- **Mock Testing**: Complete facade mocking
- **Docker Testing**: Isolated test environments
- **Test Automation**: Automated test generation

### 📚 Complete Documentation
- **Swagger/OpenAPI**: Interactive API documentation
- **Postman Collections**: Ready-to-import API collections
- **Code Documentation**: Comprehensive inline docs
- **Best Practices**: Detailed guidelines
- **Examples**: Real-world usage examples

### 🔒 Security First
- **Authentication**: JWT tokens, multi-guard support
- **Authorization**: Gates, policies, role-based access
- **Encryption**: Data encryption and secure storage
- **Input Validation**: Comprehensive validation
- **Security Headers**: Security best practices
- **Rate Limiting**: API protection

### ⚡ Performance Optimized
- **Fiber HTTP Driver**: High-performance server
- **Caching**: Redis, memory, custom drivers
- **Database Optimization**: Query optimization
- **Connection Pooling**: Efficient resource usage
- **Async Processing**: Background jobs and queues
- **Monitoring**: Performance metrics

## 🎯 Use Cases

### 🚀 New Project Setup
1. **Copy Rules**: Copy `.cursor/rules/` to your project
2. **Initialize**: Run `go run . artisan key:generate`
3. **Configure**: Set up environment variables
4. **Database**: Run migrations and seeders
5. **Start**: Begin development with full rule coverage

### 🔄 Existing Project Enhancement
1. **Add Rules**: Copy relevant rules to your project
2. **Gradual Adoption**: Implement rules incrementally
3. **Customize**: Adapt rules to your specific needs
4. **Test**: Ensure compatibility with existing code
5. **Deploy**: Use production-ready deployment

### 🧪 Testing & Quality
1. **Test Setup**: Configure testing environment
2. **Mock Testing**: Set up facade mocking
3. **HTTP Testing**: Test API endpoints
4. **Database Testing**: Test models and relationships
5. **Quality Assurance**: Ensure code quality

### 📚 API Development
1. **API Design**: Design RESTful APIs
2. **Documentation**: Generate Swagger/OpenAPI docs
3. **Postman**: Create Postman collections
4. **Testing**: Test all endpoints
5. **Deployment**: Deploy with monitoring

## 🎯 Best Practices

### 🎯 Development Workflow
1. **Design First**: Plan your architecture
2. **Document Early**: Document as you code
3. **Test Continuously**: Write tests alongside code
4. **Review Regularly**: Review code and documentation
5. **Deploy Safely**: Use production-ready deployment

### 🧪 Testing Strategy
1. **Unit Tests**: Test individual components
2. **Integration Tests**: Test component interactions
3. **HTTP Tests**: Test API endpoints
4. **Mock Tests**: Test with mocked dependencies
5. **End-to-End**: Test complete workflows

### 📚 Documentation Strategy
1. **API Documentation**: Document all endpoints
2. **Code Documentation**: Document all functions
3. **Examples**: Provide realistic examples
4. **Best Practices**: Document patterns and practices
5. **Maintenance**: Keep documentation current

### 🚀 Deployment Strategy
1. **Environment Setup**: Configure all environments
2. **Database Management**: Handle migrations safely
3. **Security**: Implement security measures
4. **Monitoring**: Set up monitoring and logging
5. **Scaling**: Plan for growth

## 🎯 Advanced Features

### 🤖 AI-LLM Collaboration
- **Human-Friendly Code**: Clear, readable code
- **AI-Friendly Structure**: Predictable patterns
- **Self-Documenting**: Comprehensive documentation
- **Type Safety**: Explicit types and interfaces
- **Consistent Patterns**: Standardized approaches

### 🔒 Security Hardening
- **Authentication**: Multi-guard authentication
- **Authorization**: Role-based access control
- **Encryption**: Data encryption at rest and in transit
- **Input Validation**: Comprehensive validation
- **Security Headers**: Security best practices
- **Rate Limiting**: API protection

### ⚡ Performance Optimization
- **Fiber HTTP Driver**: High-performance server
- **Caching Strategy**: Multi-level caching
- **Database Optimization**: Query optimization
- **Connection Pooling**: Efficient resource usage
- **Async Processing**: Background jobs
- **Monitoring**: Performance metrics

### 🧪 Testing Excellence
- **Comprehensive Coverage**: All aspects tested
- **Mock Testing**: Isolated unit testing
- **Integration Testing**: Component interaction
- **HTTP Testing**: API endpoint testing
- **Database Testing**: Model and relationship testing
- **Test Automation**: Automated test generation

## 🎯 Getting Started

### 1. Quick Setup
```bash
# Clone the repository
git clone https://github.com/AmirHosseinMoloudi/goravel-cursor-rules
cd goravel-cursor-rules

# Copy rules to your project
cp -r .cursor/rules/ /path/to/your/goravel/project/.cursor/

# Initialize your project
cd /path/to/your/goravel/project
go run . artisan key:generate
go run . artisan jwt:secret
go run . artisan migrate
go run . artisan db:seed
```

### 2. Development
```bash
# Start development server
go run . artisan serve

# Run tests
go test ./...

# Generate API documentation
go run . artisan api:generate-postman
```

### 3. Production
```bash
# One-click deployment
./deploy.sh

# Or using Docker
docker-compose up -d
```

## 🎯 Rule Customization

### 🎯 Rule Configuration
Each rule can be configured using frontmatter:
```yaml
---
alwaysApply: true          # Apply to every request
description: "Rule description"  # Manual application
globs: "*.go,*.md"         # File-specific application
---
```

### 🎯 Custom Rules
Create your own rules following the same pattern:

```markdown
---
alwaysApply: true
---
# Your Custom Rule

## Requirements
- Your requirements here
- More requirements

## Examples
// Your Go code examples here
```

## 🎯 Contributing

### 🎯 How to Contribute
1. **Fork** the repository
2. **Create** a feature branch
3. **Add** your improvements
4. **Test** thoroughly
5. **Submit** a pull request

### 🎯 Contribution Guidelines
- **Follow** existing patterns
- **Document** all changes
- **Test** thoroughly
- **Maintain** backward compatibility
- **Update** documentation

### 🎯 Areas for Contribution
- **New Rules**: Additional specialized rules
- **Improvements**: Enhance existing rules
- **Documentation**: Better documentation
- **Examples**: More examples
- **Testing**: Test coverage improvements

## 🎯 Support

### 🎯 Getting Help
- **Documentation**: Comprehensive rule documentation
- **Examples**: Real-world usage examples
- **Issues**: GitHub issues for bug reports
- **Discussions**: GitHub discussions for questions
- **Community**: Join the community

### 🎯 Reporting Issues
- **Bug Reports**: Use GitHub issues
- **Feature Requests**: Use GitHub discussions
- **Security Issues**: Contact maintainers directly
- **Documentation**: Use GitHub issues

## 🎯 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🎯 Acknowledgments

- **Goravel Framework**: The amazing Go framework
- **Cursor AI**: The AI-powered code editor
- **Community**: All contributors and users
- **Open Source**: The open source community

---

**🚀 Ready to build amazing Goravel applications with AI-powered development?**

Start with these rules and watch your development productivity soar! 🚀