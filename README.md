# 🏗️ EXPRESS-TS-STARTER | Express TypeScript Boilerplate

[![npm version](https://badge.fury.io/js/express-ts-starter.svg)](https://badge.fury.io/js/express-ts-starter)
[![npm downloads](https://img.shields.io/npm/dm/express-ts-starter.svg)](https://www.npmjs.com/package/express-ts-starter)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue.svg)](https://www.typescriptlang.org/)
[![Express.js](https://img.shields.io/badge/Express-5.1-green.svg)](https://expressjs.com/)
[![Node.js](https://img.shields.io/badge/Node.js-20+-brightgreen.svg)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Ready-green.svg)](https://www.mongodb.com/)

**The fastest way to build production-grade REST APIs, web servers, and backend services with Node.js, Express.js, and TypeScript.**

A modern, enterprise-ready boilerplate featuring MVC architecture, JWT authentication, MongoDB integration, comprehensive security, input validation, testing setup, and developer-friendly tooling. Perfect for Node.js developers building scalable REST APIs, microservices, and web servers.

---

## 📌 What's Included? (Everything for Node.js API Development)

This production-ready Express.js + TypeScript boilerplate includes everything Node.js developers need to build scalable REST APIs:

| Feature               | Details                                               |
| --------------------- | ----------------------------------------------------- |
| **Architecture**      | MVC pattern with functional service layer             |
| **Type Safety**       | 100% TypeScript with strict type checking             |
| **Database**          | MongoDB/Mongoose pre-configured and ready to use      |
| **Authentication**    | JWT-based auth with bcryptjs password hashing         |
| **Validation**        | Built-in input validation using express-validator     |
| **Security**          | Helmet, CORS, rate limiting, and request ID tracking  |
| **Middleware Stack**  | Error handling, logging, authentication, file uploads |
| **Testing Framework** | Jest with unit test examples                          |
| **Code Quality**      | ESLint + Prettier configured for consistency          |
| **API Responses**     | Standardized response format across endpoints         |
| **Request Tracking**  | Unique request IDs for debugging and logging          |
| **Graceful Shutdown** | Proper signal handling for production deployments     |
| **Modular Structure** | Feature-based folder organization for scalability     |

---

## 🎯 Why Developers Choose This Express Boilerplate?

✅ **Zero Configuration** - Ready to code in seconds  
✅ **Production-Ready** - Enterprise-grade security & performance  
✅ **Fully Typed** - Complete TypeScript support with perfect type inference  
✅ **Industry Standards** - Follows Node.js, Express.js best practices  
✅ **Scalable Architecture** - Grow from startup to enterprise  
✅ **Well-Tested** - Jest testing suite with examples  
✅ **Amazing DX** - Hot reload, linting, formatting, debugging tools included  
✅ **MongoDB Ready** - Mongoose integration pre-configured  
✅ **Secure by Default** - Authentication, validation, rate limiting built-in  
✅ **Active Community** - Regular updates and support

---

## 🔍 Perfect For Node.js Developers Building...

- **REST APIs** - Full-featured API servers with authentication and validation
- **Microservices** - Scalable service architecture ready for production
- **Web Servers** - Fast, secure HTTP servers for web applications
- **Backend Services** - Complex business logic with clean separation of concerns
- **Startups** - Quick MVP development with enterprise-grade foundation
- **Enterprise Apps** - Scalable architecture for large teams
- **Real-time Backends** - Socket.io integration ready
- **Data APIs** - MongoDB integration for data management
- **Learning** - Best practices and patterns for Node.js/Express.js

---

## 🚀 Quick Start - Get Coding in Seconds

### Option 1: Install as npm Package (Recommended)

```bash
npm install express-ts-starter
```

### Option 2: Clone & Customize

```bash
git clone https://github.com/nikhilpktcr/express-ts-starter.git my-api
cd my-api
npm install
npm run dev
```

---

## 📦 Available Commands

```bash
# Install dependencies
npm install

# Start development server (hot reload)
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run test suite
npm test

# Lint and fix code
npm run lint
npm run lint:fix
```

---

## 📁 Project Structure

```
src/
├── modules/
│   └── users/
│       ├── userController.ts     # Handles HTTP requests
│       ├── userService.ts        # Singleton service - business logic
│       ├── userMessage.ts        # Constants/messages
│       └── tests/
│           └── userController.test.ts
├── routes/
│   ├── index.ts                  # Main API router
│   └── usersRoute.ts             # /users routes
├── middleware/                   # Express middleware
│   ├── auth.ts                   # Authentication
│   ├── errorMiddleware.ts        # Error handling
│   ├── logMiddleware.ts          # Request logging (Morgan)
│   ├── validatorMiddleware.ts    # Input validation
│   ├── uploadMiddleware.ts       # File uploads (Multer)
│   └── requestIdMiddleware.ts    # Request tracking
├── config/                       # Configuration files
│   ├── envConfig.ts              # Environment variables
│   ├── dbConfig.ts               # MongoDB/Mongoose connection
│   ├── emailConfig.ts            # Email service config
│   ├── rateLimitConfig.ts        # Rate limiting rules
│   └── throttleConfig.cjs        # Throttle configuration
├── models/
│   └── UserModel.ts              # Mongoose User schema
├── validators/                   # Input validators
│   └── userValidators.ts         # User validation rules
├── types/
│   ├── index.ts                  # Exported types
│   ├── userTypes.ts              # User type definitions
│   └── roleType.ts               # Role type definitions
├── interfaces/
│   └── userInterface.ts          # User interfaces
├── utils/                        # Utility functions
│   ├── responseUtil.ts           # Standardized API responses
│   └── authFunction.ts           # Authentication helpers
├── constants/                    # Application constants
│   └── index.ts
├── messages/                     # Success/error messages
│   └── index.ts
├── app.ts                        # Express app initialization
└── server.ts                     # Server entry point
```

---

## ✨ Features

- ✅ **Express + TypeScript** - Full type safety
- ✅ **MVC Architecture** - Clean separation of concerns
- ✅ **Functional Service Pattern** - Lightweight, testable business logic
- ✅ **Modular Routing** - Feature-based structure
- ✅ **Security** - Helmet, CORS, JWT, bcryptjs
- ✅ **Database** - MongoDB with Mongoose integration
- ✅ **Validation** - Express-validator middleware
- ✅ **Error Handling** - Global error middleware + graceful shutdown
- ✅ **Logging** - Morgan with request IDs
- ✅ **File Uploads** - Multer configured
- ✅ **Rate Limiting** - Express rate-limit ready
- ✅ **Code Quality** - ESLint + Prettier
- ✅ **Testing** - Jest configured
- ✅ **Standardized Responses** - Consistent API responses

---

## 🧠 Architectural Patterns

### Pattern Overview

| Pattern/Concept            | Implementation                                      |
| -------------------------- | --------------------------------------------------- |
| **MVC**                    | Controllers, Services, Models - clean separation    |
| **Functional Services**    | Exported functions for business logic (not classes) |
| **Modular Design**         | Each feature is self-contained and independent      |
| **Separation of Concerns** | `app.ts` initializes app, `server.ts` starts server |
| **Global Error Handling**  | Centralized error middleware                        |
| **Request Tracking**       | Unique request IDs for debugging                    |
| **Graceful Shutdown**      | Proper signal handling (SIGTERM, SIGINT)            |

### Why Functional Services Instead of Class-Based Singletons?

This boilerplate uses **Functional Service Pattern** (exported async functions) instead of traditional Singleton classes. Here's why this approach is optimal:

#### ✅ **Benefits for Developers**

**1. Simplicity & Readability**

```typescript
// ✨ Our approach - simple and direct
export const registerUser = async (data) => { ... }
export const loginUser = async (data) => { ... }

// vs. Class-based singleton (boilerplate heavy)
class UserService {
  private static instance: UserService;
  static getInstance() { ... }
  async registerUser() { ... }
}
```

**2. Easier Testing & Mocking**

```typescript
// Functional - trivial to mock
jest.mock("./userService", () => ({
  registerUser: jest.fn(),
}));

// Class singleton - requires getInstance() mocking
```

**3. Tree-Shaking & Bundle Size**

- Only imported functions are included in production builds
- Class instantiation adds unnecessary overhead
- Faster startup time

**4. No State Management Issues**

- Functional services are stateless → no singleton state pollution
- Each request is isolated and independent
- No threading/concurrency concerns

**5. Better for Async Operations**

```typescript
// Naturally async
export const registerUser = async (data) => {
  // Direct async/await
};

// vs. Class requiring async getInstance()
```

#### 🎯 **Robustness**

✅ **Testable** - Functions are pure and easy to mock  
✅ **Scalable** - Add new services without complexity  
✅ **Maintainable** - No hidden state or initialization logic  
✅ **Production-Ready** - Used by companies like Airbnb, Stripe  
✅ **TypeScript-Friendly** - Full type inference for functions

#### 📊 **Comparison**

| Aspect             | Functional              | Class Singleton   |
| ------------------ | ----------------------- | ----------------- |
| **Complexity**     | Low                     | Medium-High       |
| **Testing**        | Easy                    | Complex           |
| **Bundle Size**    | Smaller                 | Larger            |
| **Learning Curve** | Minimal                 | Moderate          |
| **Scalability**    | Linear                  | Logarithmic       |
| **Production Use** | Airbnb, Stripe, Netflix | Legacy enterprise |

---

## 🔧 Tech Stack

- **Runtime**: [Node.js](https://nodejs.org/) (v20+)
- **Framework**: [Express](https://expressjs.com/) v5
- **Language**: [TypeScript](https://www.typescriptlang.org/) v5
- **Database**: [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/)
- **Security**: [Helmet](https://helmetjs.github.io/), [CORS](https://github.com/expressjs/cors)
- **Authentication**: [JWT](https://jwt.io/), [bcryptjs](https://github.com/dcodeIO/bcrypt.js)
- **Validation**: [express-validator](https://express-validator.github.io/docs/)
- **Logging**: [Morgan](https://github.com/expressjs/morgan)
- **File Upload**: [Multer](https://github.com/expressjs/multer)
- **Testing**: [Jest](https://jestjs.io/)
- **Linting**: [ESLint](https://eslint.org/) + [Prettier](https://prettier.io/)

---

## 📝 Configuration

### Environment Variables

Create a `.env` file in the root by copying from `.env.example`:

```bash
cp .env.example .env
```

Then update the values:

```env
# Server
NODE_ENV=development
PORT=5000
BASIC_API_URL=/api/v1

# Database
DB_CONNECTION=mongodb://localhost:27017/
DB_NAME=testDB

# Authentication
JWT_SECRET=your-super-secret-jwt-key-change-in-production

# Email (Optional)
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your-email@gmail.com
SMTP_PASSWORD=your-app-password
```

**Key Variables:**

- `PORT` - Server port (default: 5000)
- `DB_CONNECTION` - MongoDB connection string
- `DB_NAME` - Database name
- `JWT_SECRET` - Secret key for JWT tokens (⚠️ Change in production!)
- `BASIC_API_URL` - API base path (default: /api/v1)

See [`.env.example`](.env.example) for complete list of options.

---

## 🔐 Security Features

- **Helmet** - HTTP headers security
- **CORS** - Cross-Origin Resource Sharing
- **JWT** - Secure authentication
- **bcryptjs** - Password hashing
- **Rate Limiting** - DDoS protection
- **Input Validation** - Prevent injection attacks
- **Request ID Tracking** - Audit trail

---

## 🧪 Testing

```bash
# Run all tests
npm test

# Run tests in watch mode
npm test -- --watch

# Run with coverage
npm test -- --coverage
```

---

## 🔢 API Versioning

Supports URL-based API versioning for backward compatibility.

```typescript
// In app.ts
app.use("/api/v1", routes); // Change version as needed
```

**Example Endpoints:**

- `POST /api/v1/users` - Create user
- `GET /api/v1/users` - Get all users
- `GET /api/v1/users/:id` - Get user by ID
- `PUT /api/v1/users/:id` - Update user
- `DELETE /api/v1/users/:id` - Delete user

---

## 📋 Standardized Responses

All API responses follow a consistent format:

### Success Response

```json
{
  "success": true,
  "requestId": "550e8400-e29b-41d4-a716-446655440000",
  "message": "Operation successful",
  "response": { "data": "..." }
}
```

### Error Response

```json
{
  "success": false,
  "requestId": "550e8400-e29b-41d4-a716-446655440000",
  "error": "Error message"
}
```

---

## 🚦 Graceful Shutdown

The server handles graceful shutdown on:

- `SIGTERM` (Docker stop)
- `SIGINT` (Ctrl+C)

Existing connections are completed before exit (30-second timeout).

---

---

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see `LICENSE` file for details.

Free for personal and commercial use! ✨

---

## 🎯 Roadmap

- [ ] API Documentation (Swagger/OpenAPI)
- [ ] Health check endpoint
- [ ] Pagination utility
- [ ] Redis caching layer
- [ ] Database migrations
- [ ] Docker & Docker Compose
- [ ] CI/CD pipeline examples
- [ ] More comprehensive test suite

---

## 💬 Questions & Support

- **Email**: nikhil.pk.connect@gmail.com
- **GitHub Issues**: [Report bugs](https://github.com/nikhilpktcr/express-ts-starter/issues)
- **GitHub**: [@nikhilpktcr](https://github.com/nikhilpktcr)

---

## 🌟 Show Your Support

If this boilerplate helps your project:

- ⭐ **Star the repository** on GitHub
- 📦 **Use the npm package** in your projects
- 🐛 **Report issues** you encounter
- 💡 **Suggest features** and improvements
- 🔄 **Share** with other developers

Your support helps improve this project for everyone!

---

## 📊 Trending Keywords

This boilerplate is perfect for developers searching for:

- Express TypeScript starter
- Node.js REST API boilerplate
- Production-ready backend template
- MVC Node.js project
- TypeScript Express API
- MongoDB Express starter
- Secure Node.js backend
- Express authentication template

---

## 🚀 Ready to Build?

Start building your next API with this production-ready boilerplate. Clone, customize, and deploy in minutes!

```bash
npm install express-ts-starter
```

**Happy coding!** 🎉
