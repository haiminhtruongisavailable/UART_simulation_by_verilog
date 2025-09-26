# Project Structure Guide

## Team Branch System

This project uses a branch-based collaboration system where each team member has their own dedicated branch with a private workspace.

## Available Branches

### 1. HaiMinh-clean
- **Purpose**: Project leader's workspace
- **Contains**: `/leader/` folder only
- **Responsibilities**: 
  - Project coordination and planning
  - Code integration and quality control
  - Technical architecture decisions
  - Team communication

### 2. ThePhong-clean  
- **Purpose**: Team member 1's workspace
- **Contains**: `/friend1/` folder only
- **Focus**: Individual development and contributions

### 3. NgocBach-clean
- **Purpose**: Team member 2's workspace  
- **Contains**: `/friend2/` folder only
- **Focus**: Individual development and contributions

## Workspace Structure

Each private folder contains:
```
/[member-name]/
├── README.md          # Personal workspace overview
├── code/              # Verilog HDL files and source code
│   └── README.md
├── docs/              # Documentation and specifications
│   └── README.md
├── images/            # Diagrams, screenshots, waveforms
│   └── README.md
└── references/        # External links, YouTube videos, papers
    └── README.md
```

## How to Use

1. **Switch to your branch**:
   ```bash
   git checkout [your-branch-name]
   ```

2. **Navigate to your workspace**:
   ```bash
   cd [your-folder-name]/
   ```

3. **Organize your work**:
   - Put code in `code/` folder
   - Add documentation in `docs/` folder  
   - Save images/diagrams in `images/` folder
   - Link references in `references/` folder

4. **Document everything**:
   - Update README files as you work
   - Use descriptive commit messages
   - Keep references organized

## Benefits

- **Privacy**: Each member has their own branch and folder
- **Organization**: Structured folders for different types of content
- **Flexibility**: Support for code, docs, images, and external references
- **Collaboration**: Clear separation of responsibilities
- **Version Control**: Full git history for each workspace

## Tips for Success

- Regularly commit your changes
- Use descriptive file names
- Update documentation as you go
- Add useful resources to references folder
- Communicate with team leader for integration planning
