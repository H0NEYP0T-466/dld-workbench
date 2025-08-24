# 🤝 Contributing to DLD Workbench

Thank you for your interest in contributing to the DLD Workbench! This document provides guidelines for contributing to this educational digital logic design repository.

## 📋 Table of Contents

- [🤝 Contributing to DLD Workbench](#-contributing-to-dld-workbench)
  - [📋 Table of Contents](#-table-of-contents)
  - [🚀 Getting Started](#-getting-started)
  - [🍴 How to Contribute](#-how-to-contribute)
  - [📝 Code Style Guidelines](#-code-style-guidelines)
  - [🐛 Bug Reports](#-bug-reports)
  - [✨ Feature Requests](#-feature-requests)
  - [🧪 Testing Guidelines](#-testing-guidelines)
  - [📚 Documentation Guidelines](#-documentation-guidelines)
  - [📞 Support](#-support)

## 🚀 Getting Started

### Prerequisites
- **Proteus Design Suite** (8.0 or higher)
- **Git** for version control
- Basic knowledge of digital electronics
- Understanding of circuit design principles

### Setting Up Development Environment

1. **Fork the Repository**
   ```bash
   # Click the "Fork" button on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/dld-workbench.git
   cd dld-workbench
   ```

2. **Set Up Upstream Remote**
   ```bash
   git remote add upstream https://github.com/H0NEYP0T-466/dld-workbench.git
   git remote -v
   ```

3. **Install Proteus Design Suite**
   - Download from [Labcenter Electronics](https://www.labcenter.com/)
   - Ensure ISIS Professional is properly configured
   - Test by opening an existing `.pdsprj` file

## 🍴 How to Contribute

### Step 1: Create a Branch
```bash
# Create and switch to a new branch
git checkout -b feature/your-feature-name
# or
git checkout -b bugfix/issue-description
```

### Step 2: Make Your Changes
- Add new circuits or improve existing ones
- Update documentation as needed
- Follow the project structure and naming conventions

### Step 3: Test Your Changes
- Open all modified `.pdsprj` files in Proteus
- Ensure circuits simulate correctly
- Verify documentation is accurate

### Step 4: Commit Your Changes
```bash
# Stage your changes
git add .

# Commit with descriptive message
git commit -m "Add: New half-adder circuit with improved layout"
# or
git commit -m "Fix: Corrected logic gate connections in Assignment#3"
```

### Step 5: Push and Create Pull Request
```bash
# Push to your fork
git push origin feature/your-feature-name

# Create a Pull Request on GitHub
# Include detailed description of changes
```

## 📝 Code Style Guidelines

### Circuit Design Standards

#### 🔌 Component Placement
- **Logical Flow**: Place components left-to-right following signal flow
- **Spacing**: Maintain consistent spacing between components
- **Alignment**: Align similar components vertically or horizontally
- **Clarity**: Ensure circuit is easily readable and understandable

#### 🏷️ Naming Conventions
- **Files**: Use descriptive names with proper capitalization
  ```
  ✅ Good: "4BitFullAdder.pdsprj"
  ❌ Bad: "circuit1.pdsprj"
  ```
- **Component Labels**: Use clear, concise labels
  ```
  ✅ Good: "InputA", "SumOutput", "CarryOut"
  ❌ Bad: "U1", "D1", "X"
  ```

#### 📁 Project Organization
```
New-Circuit/
├── CircuitName.pdsprj              # Main Proteus project
├── CircuitName.pdsprj.workspace    # Workspace file (auto-generated)
├── README.md                       # Circuit documentation
├── Simulation/                     # Test cases and results
└── Documentation/                  # Additional docs, images
```

### Documentation Standards

#### 📖 Circuit Documentation
Each new circuit should include:
- **Purpose**: What the circuit does
- **Inputs/Outputs**: Clear signal descriptions
- **Operation**: How the circuit works
- **Testing**: Simulation results and verification

#### 📝 README Format
```markdown
# Circuit Name

## Description
Brief description of the circuit's purpose and functionality.

## Components Used
- List of main components
- IC specifications
- Part numbers (if applicable)

## Simulation Instructions
1. Step-by-step simulation guide
2. Expected outputs
3. Test cases

## Educational Objectives
- Learning goals
- Concepts demonstrated
```

## 🐛 Bug Reports

### Before Submitting a Bug Report
1. **Search existing issues** to avoid duplicates
2. **Update Proteus** to the latest version
3. **Test with minimal example** to isolate the issue

### Bug Report Template
```markdown
## Bug Description
A clear and concise description of the bug.

## Steps to Reproduce
1. Open file 'X.pdsprj'
2. Run simulation
3. Click on component Y
4. See error

## Expected Behavior
What you expected to happen.

## Actual Behavior
What actually happened.

## Environment
- Proteus Version: [e.g., 8.12]
- Operating System: [e.g., Windows 10]
- Project File: [e.g., LogicGates.pdsprj]

## Screenshots
Add screenshots to help explain the problem.
```

## ✨ Feature Requests

### Suggesting New Features
We welcome suggestions for:
- **New Circuits**: Additional digital logic designs
- **Educational Content**: Tutorials, assignments, projects
- **Documentation**: Improved guides and examples
- **Tools**: Scripts or utilities for circuit development

### Feature Request Template
```markdown
## Feature Description
A clear description of the feature you'd like to see.

## Educational Value
How this feature would benefit students and educators.

## Implementation Ideas
Any thoughts on how this could be implemented.

## Additional Context
Screenshots, diagrams, or references that help explain the feature.
```

## 🧪 Testing Guidelines

### Circuit Testing Checklist
- [ ] **Functional Testing**: Circuit performs intended operation
- [ ] **Edge Cases**: Test with boundary conditions
- [ ] **Documentation**: All inputs/outputs documented
- [ ] **Simulation**: Runs without errors in Proteus
- [ ] **Components**: All components properly connected
- [ ] **Labels**: Clear and consistent labeling

### Testing Process
1. **Open Circuit**: Load `.pdsprj` file in Proteus ISIS
2. **Visual Inspection**: Check component placement and connections
3. **Simulation Test**: Run simulation with various inputs
4. **Documentation Review**: Verify README and comments
5. **Performance Check**: Ensure reasonable simulation speed

## 📚 Documentation Guidelines

### Writing Style
- **Clear and Concise**: Use simple, direct language
- **Educational Focus**: Remember the target audience is students
- **Step-by-Step**: Break complex procedures into steps
- **Examples**: Include practical examples and use cases

### Required Documentation
For each contribution, update:
- **Main README.md**: If adding new sections or features
- **Local README.md**: For individual circuits or projects
- **Comments**: In Proteus project files where helpful
- **CHANGELOG.md**: Document significant changes

### Documentation Tools
- **Markdown**: For all documentation files
- **Screenshots**: Use high-quality images from Proteus
- **Diagrams**: Include circuit diagrams when helpful
- **Videos**: Consider screen recordings for complex procedures

## 📞 Support

### Getting Help
- **GitHub Issues**: For bugs and feature requests
- **Discussions**: For general questions and ideas
- **Documentation**: Check existing docs first
- **Community**: Connect with other contributors

### Contact Information
- **Maintainer**: [H0NEYP0T-466](https://github.com/H0NEYP0T-466)
- **Project Issues**: [GitHub Issues](https://github.com/H0NEYP0T-466/dld-workbench/issues)
- **Discussions**: [GitHub Discussions](https://github.com/H0NEYP0T-466/dld-workbench/discussions)

---

### 🙏 Thank You!

Thank you for contributing to the DLD Workbench! Your contributions help make digital electronics education more accessible and engaging for students worldwide.

**Happy Circuit Building! 🔌⚡**