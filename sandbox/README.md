# Sandbox

> **Note**: This README was generated with GitHub Copilot. The content below outlines the intended purpose and guidelines for this experimental workspace.

Experimental workspace for rapid prototyping, testing new technologies, and exploring ideas without the constraints of formal project structure.

## 🎯 Purpose

The sandbox is your playground for:
- **Quick Experiments**: Test ideas rapidly without setup overhead
- **Learning New Tech**: Try out new frameworks, libraries, or tools
- **Proof of Concepts**: Build minimal viable examples
- **Breaking Things**: Learn by experimentation without fear of breaking production code
- **Iterative Learning**: Quick iteration cycles for hands-on learning

## 🧪 Current Experiments

### ⚛️ [learning-reducers/](learning-reducers/)
Exploring state management patterns with React reducers.

**Technologies**: React, TypeScript, Vite  
**Focus**: Understanding reducer patterns, context API, and state management  
**Status**: Active learning project

---

## 📋 Sandbox Guidelines

### Philosophy
- **Speed over Perfection**: Get ideas working quickly
- **Experimentation First**: Try things, break things, learn things
- **Minimal Documentation**: Document just enough to remember what you did
- **Disposable Code**: Code here may be temporary or evolve into full projects

### What Belongs Here
✅ Testing new frameworks or libraries  
✅ Following tutorials and learning exercises  
✅ Quick prototypes and MVPs  
✅ Algorithm implementations for learning  
✅ API experimentation  
✅ UI/UX experiments  

### What Doesn't Belong Here
❌ Production-ready code (use `projects/` instead)  
❌ Well-documented learning materials (use `notebooks/` instead)  
❌ Long-term maintained applications  
❌ Code requiring extensive documentation  

## 🚀 Quick Start

### Creating a New Experiment

```bash
# Navigate to sandbox
cd sandbox

# Create a new directory for your experiment
mkdir my-experiment
cd my-experiment

# Initialize based on your needs
npm init -y                    # For Node.js projects
npm create vite@latest .       # For Vite projects
# or just start coding!
```

### Typical Structure
```
experiment-name/
├── README.md (optional)    # Brief notes on what you're testing
├── package.json            # If needed
├── src/                    # Source files
└── notes.md (optional)     # Learning notes and insights
```

## 💡 Best Practices for Sandbox

### Do:
- **Commit Working States**: Save code that works, even if messy
- **Take Notes**: Jot down key learnings and gotchas
- **Time-box Experiments**: Set a time limit to avoid rabbit holes
- **Extract Learnings**: Move successful patterns to projects or notebooks

### Don't:
- Over-engineer: Keep it simple
- Worry about perfect code: Focus on learning
- Spend too long: If it's getting complex, promote to a project
- Forget to document insights: Future you will thank you

## 🔄 Experiment Lifecycle

### 1. Start
- Create directory
- Set up minimal tooling
- Start coding immediately

### 2. Explore
- Try different approaches
- Break things intentionally
- Learn from errors

### 3. Conclude
- Document key findings
- Decide on next steps:
  - **Archive**: Keep for reference
  - **Delete**: Wasn't useful, that's okay!
  - **Promote**: Move to projects/ with proper structure
  - **Document**: Create a notebook explaining the concept

## 📝 Common Experiment Types

### Framework Learning
```
learning-[framework-name]/
├── src/
│   ├── basic-example/
│   ├── advanced-example/
│   └── edge-cases/
└── notes.md
```

### API Testing
```
api-experiment/
├── test-endpoints.js
├── mock-data.json
└── findings.md
```

### Algorithm Practice
```
algorithm-exploration/
├── approach1.js
├── approach2.js
├── benchmark.js
└── notes.md
```

### UI Experiments
```
ui-prototype/
├── src/
│   ├── components/
│   └── styles/
└── screenshots/
```

## 🎓 Learning from Experiments

### Capture Insights
Keep a simple log of what you learned:
```markdown
## What I Tried
- Implemented feature X using approach Y

## What Worked
- Pattern Z was cleaner than expected

## What Didn't Work
- Library A had limitation B

## Next Steps
- Try alternative C
- Read documentation on D
```

### Graduation Path
When an experiment succeeds:
1. **Quick Reference** → Create a notebook with explanation
2. **Useful Tool** → Refactor into a proper project
3. **Reusable Pattern** → Extract and document in projects/
4. **Just Learning** → Keep notes and archive

## 🔗 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [Stack Overflow](https://stackoverflow.com/)
- [GitHub Explore](https://github.com/explore)
- Framework-specific documentation

## 💭 Remember

> "The sandbox is where you learn by doing. Make mistakes here, learn from them, and grow. Not every experiment needs to succeed – each one teaches you something valuable."

## 🧹 Maintenance

- **Review Periodically**: Every few months, review experiments
- **Archive Old Stuff**: Move outdated experiments to an `archive/` folder
- **Clean Up**: Delete experiments that served their purpose
- **Promote Winners**: Move successful experiments to appropriate locations

---

**Happy Experimenting! 🚀**