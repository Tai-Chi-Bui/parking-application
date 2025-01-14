Autospace is a comprehensive car parking and valet service platform built using modern web technologies. This monorepo contains multiple applications and shared libraries managed with Nx build system.

## Project Structure

autospace/
├── apps/ # Applications
│ ├── api/ # Backend API (NestJS)
│ ├── web/ # Main customer app (Next.js)
│ ├── web-manager/ # Garage management interface
│ ├── web-valet/ # Valet service interface
│ └── web-admin/ # Administrative interface
└── libs/ # Shared libraries
├── ui/ # UI components
├── network/ # API integration
├── forms/ # Form handling
├── 3d/ # 3D components
└── util/ # Utilities


## Applications

### 1. API (NestJS Backend)
- GraphQL and REST API endpoints
- Authentication and authorization
- Swagger documentation
- Prisma for database management
- Running on default port 3000

### 2. Web Applications (Next.js)
- **Web** (`@autospace/web`): Main customer-facing application (Port 3001)
- **Web Manager** (`@autospace/web-manager`): Garage management interface (Port 3002)
- **Web Valet** (`@autospace/web-valet`): Valet service interface (Port 3003)
- **Web Admin** (`@autospace/web-admin`): Administrative interface (Port 3004)

## Shared Libraries

### 1. UI Library (`@autospace/ui`)
- Reusable React components
- Tailwind configuration
- Common styling
- Layout components

### 2. Network Library (`@autospace/network`)
- GraphQL code generation
- Apollo client configuration
- Authentication utilities
- API types and interfaces

### 3. Forms Library (`@autospace/forms`)
- React Hook Form configurations
- Zod validations
- Form components

### 4. 3D Library (`@autospace/3d`)
- Three.js integration
- React Three Fiber components
- 3D models and scenes

### 5. Utilities Library (`@autospace/util`)
- Common utilities
- Date handling
- Type definitions
- Constants

## Technology Stack

### Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS
- Apollo Client
- NextAuth.js
- Three.js

### Backend
- NestJS
- GraphQL
- REST
- PostgreSQL
- Prisma
- JWT Authentication

### Development Tools
- Nx Build System
- ESLint
- Prettier
- Husky
- TypeScript
- Docker


