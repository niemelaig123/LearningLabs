# Projects

> **Note**: This README was generated with GitHub Copilot. The guidelines below represent goals and standards to aspire to for projects in this directory.

Full-featured applications and projects that demonstrate practical implementation of learned concepts. The goal is for these to be runnable at minimum, with hopefully some tests.

## Overview

This directory is for complete, working applications that integrate multiple technologies and concepts. Unlike the experimental sandbox, these projects aim to be functional, well-documented, and closer to production quality.

## Current Projects

TBD, mainly reorganizing things right now

## Project Standards

This is a sort of how to guide/checklist for me when starting up one of these projects:

### Documentation
- **README.md**: Project overview, setup instructions, and usage guide
- **Code Comments**: Clear explanations for complex logic
- **API Documentation**: Document interfaces and function signatures

### Code Quality
- **Type Safety**: Use TypeScript or similar type systems where applicable
- **Testing**: Include unit tests and integration tests
- **Linting**: Follow consistent code style with ESLint/Prettier
- **Error Handling**: Robust error handling and validation

### Project Structure
```
project-name/
├── README.md           # Project documentation
├── package.json        # Dependencies and scripts
├── tsconfig.json       # TypeScript configuration
├── src/                # Source code
│   ├── components/     # UI components
│   ├── hooks/          # Custom hooks
│   ├── types/          # Type definitions
│   └── utils/          # Utility functions
├── tests/              # Test files
└── public/             # Static assets
```

### Common Commands
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Run tests
npm test

# Build for production
npm run build

# Run linter
npm run lint
```

## Adding New Projects

When creating a new project:
1. Create a dedicated directory with a descriptive name
2. Initialize with appropriate build tools and configuration
3. Create a comprehensive README.md
4. Set up testing infrastructure
5. Document learning goals and key concepts
6. Update this README with project information
