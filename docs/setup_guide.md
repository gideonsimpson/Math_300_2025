# Setup Guide for Math 300

This guide will help you set up your environment for the course.

## Installing Julia

1. Visit [julialang.org](https://julialang.org/downloads/)
2. Download Julia for your operating system
3. Follow the installation instructions for your platform

## Setting up the Course Environment

1. Clone or download this repository
2. Navigate to the repository directory in your terminal
3. Start Julia in the repository directory
4. In the Julia REPL, press `]` to enter package mode
5. Run `activate .` to activate the course environment
6. Run `instantiate` to install dependencies (when they are added)

## Recommended Tools

- **IDE/Editor**: VS Code with the Julia extension, or any text editor you prefer
- **Jupyter**: For interactive notebooks (install with `using Pkg; Pkg.add("IJulia")`)
- **Git**: For keeping up with repository updates

## Getting Updates

This repository will be updated throughout the term. To get the latest materials:

```bash
git pull origin main
```

If you've made local changes, you may need to stash them first:

```bash
git stash
git pull origin main
git stash pop
```

## Troubleshooting

If you encounter issues:
1. Make sure you have the latest version of Julia
2. Check that you're in the correct directory
3. Try restarting Julia and re-activating the environment
4. Ask for help during office hours or class