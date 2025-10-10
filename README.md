# CalculatorPlus

A simple Python calculator app that provides basic arithmetic operations and square root calculation.

## Features
- Addition: `add(a, b)`
- Subtraction: `subtract(a, b)`
- Multiplication: `multiply(a, b)`
- Division with safe handling of division-by-zero: `divide(a, b)`
- Square root calculation with negative input check: `square_root(x)`

## Repository Structure
git_assignment_HeroVired/
<br>├── CalculatorPlus.py    # Main calculator application
<br>├── README.md           # Project documentation
<br>└── .git/              # Git version control

## Installation
Clone the repository:
```bash
git clone https://github.com/vikramhemchandar/git_assignment_HeroVired.git
cd git_assignment_HeroVired
```

## Running the application
```
python calculator.py
```

## Example Output
```
16 + 4 = 20
16 - 4 = 12
16 * 4 = 64
16 / 4 = 4.0
```

### Development Commands

```bash
# Clone the repository
git clone https://github.com/vikramhemchandar/git_assignment_HeroVired.git
cd git_assignment_HeroVired

# Create a new feature branch
git checkout -b feature/your-feature-name

# Make changes and commit
git add .
git commit -m "Your commit message"

# Push feature branch
git push origin feature/your-feature-name
```

### Branching & Release Strategy (used in this assignment)
- `main` — production-ready code and releases.
- `dev` — integration/testing branch where features are merged before release.
- `feature/sqrt` — short-lived branches for feature development (e.g. feature/sqrt).

Releases are created as Git tags (semver): v1.0.0, v2.0.0, etc.

### Release Information
- **Version**: 1.0.0
- **Release Date**: October 10, 2025
- **Tag**: `v1.0.0`
- **Commit Hash**: `7cf6d1f `
- **Release Notes**: Initial release with basic arithmetic operations

### Collaborators
Invite collaborators via GitHub: Settings → Manage access → Invite collaborators and add their GitHub usernames.

### Contributing
1. Create a feature branch from dev: git checkout -b feature/sqrt dev
2. Make changes, write tests, and commit.
3. Push your branch and create a Pull Request (target main for review, then merge into dev).
4. After review and verification, merge into dev, test, and finally merge dev into main for the release.

## License
This assignment project has no formal license, however, it is part of Hero Vired Git and GitHub Assignment
