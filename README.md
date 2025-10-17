# Git and GitHub Assignment
This assignment has 2 python programs
 - CalculatorPlus python program
 - GeometryCalculator python program

Following document discusses about the two python programs in detailed with **screenshots**

## 1. CalculatorPlus Application

A simple Python calculator app that provides basic arithmetic operations and square root calculation.

### Features
- Addition: `add(a, b)`
- Subtraction: `subtract(a, b)`
- Multiplication: `multiply(a, b)`
- Division with safe handling of division-by-zero: `divide(a, b)`
- Square root calculation with input check: `square_root(x)`

### Repository Structure
git_assignment_HeroVired/
<br>├── CalculatorPlus.py    # Main calculator application
<br>├── README.md           # Project documentation
<br>└── .git/              # Git version control

### Installation
Clone the repository:
```bash
git clone https://github.com/vikramhemchandar/git_assignment_HeroVired.git
cd git_assignment_HeroVired
```

### Running the application
```
python calculator.py
```

### Example Output
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
- `feature/sqrt` — short-lived branches for feature development

Releases are created as Git tags (semver): v1.0.0, v2.0.0, etc.

### Release Information
- **Version**: 1.0.0
- **Release Date**: October 10, 2025
- **Tag**: `v1.0.0`
- **Commit Hash**: `7cf6d1f `
- **Release Notes**: Initial release with basic arithmetic operations

## 2. GeormetryCalculator Application

A simple Python app that provides basic area calculator for Rectangle and Circle.

### Features
- Calculate Circle Area
- Calculate Rectangle Area

### Repository Structure
git_assignment_HeroVired/
<br>├── GeometryCalculator.py    # Main application
<br>├── README.md                # Project documentation
<br>└── .git/                    # Git version control

### Installation
Clone the repository:
```bash
git clone https://github.com/vikramhemchandar/git_assignment_HeroVired.git
cd git_assignment_HeroVired
```

### Running the application
```
python GeometryCalculator.py
```

### Example Output
```
The area of the circle with radius 5 = 78.53981633974483
The area of the rectangle with length 10 and width 6 = 60
```

### Branching & Release Strategy (used in this assignment)
- `main` — production-ready code and releases.
- `dev` — integration/testing branch where features are merged before release.
- `feature/circle-area` — short-lived branches for feature development
- `feature/rectangle-area` — short-lived branches for feature development

### Screenshots of the program

a. Create a new branch **feature/circle-area**
<img width="940" height="174" alt="image" src="https://github.com/user-attachments/assets/c0118604-fa29-4c5a-b082-7df8ac53fb0e" />

b. Stash changes in feature/circle-area
<img width="745" height="606" alt="image" src="https://github.com/user-attachments/assets/b9543964-485c-472d-8956-e8ce29013ce1" /><br>
After stashing the feature, the code has saved but not committed
<img width="940" height="979" alt="image" src="https://github.com/user-attachments/assets/231bc959-bd4d-440b-9de6-08e8b450d115" />

c. Create a new branch **feature/rectangle-area**
<img width="940" height="654" alt="image" src="https://github.com/user-attachments/assets/c388efc6-469b-4fdf-b70b-7fd7966b552e" />

d. Stash changes in feature/rectangle-area
<img width="940" height="786" alt="image" src="https://github.com/user-attachments/assets/2ff93e2a-e967-42fc-a5ad-a6fd3266871f" />
After stashing the featre, the code has saved but not committed
<img width="940" height="967" alt="image" src="https://github.com/user-attachments/assets/388041f3-e3bc-4a19-87e3-416dca3bb33e" />

e. Switch back to feature/circle-area
<img width="940" height="985" alt="image" src="https://github.com/user-attachments/assets/6d44c640-4307-48e7-82c9-2fe1c328653d" />
After stash apply on feature/circle-area
<img width="940" height="1044" alt="image" src="https://github.com/user-attachments/assets/648a3f44-07ff-473a-ab6f-6ae51dbbc1d3" />

f. Commit and push feature/circle-area branch
<img width="940" height="1044" alt="image" src="https://github.com/user-attachments/assets/12fd4c2e-cdff-47c3-b820-1f03bc639919" />


g. Switch back to feature/rectangle-area
<img width="940" height="750" alt="image" src="https://github.com/user-attachments/assets/40c911f9-152c-47cb-8cbc-0bf430c5698a" />
After stash changes applied on feature/rectangle-area
<img width="940" height="953" alt="image" src="https://github.com/user-attachments/assets/ffb52f09-d7ec-4a93-9664-55fd2fcae945" />

h. Commmit and push feature/rectangle-area
<img width="940" height="953" alt="image" src="https://github.com/user-attachments/assets/5ba588d3-fd7d-4a9a-8801-42a286a4ffdb" />

i. Create two Pull Requests to merge both feature/circle-area and feature/rectangle-area branches to dev branch<br>
Raised Pull Request and code review the feature/circle-area branch to dev branch
<img width="940" height="952" alt="image" src="https://github.com/user-attachments/assets/c4353eab-b362-4a2e-af7d-3fbffd95c599" />

Pull Request to merge the code from feature/rectangle-area to dev branch
<img width="940" height="716" alt="image" src="https://github.com/user-attachments/assets/fe5ce1c3-a477-43f5-aee0-855429173731" />

j. Create Pull Request to merge from dev branch to main branch and review the code
<img width="940" height="818" alt="image" src="https://github.com/user-attachments/assets/9396af32-1fe2-4414-99ae-e2b073e26a5e" />

### Collaborators
Invite collaborators via GitHub: Settings → Manage access → Invite collaborators and add their GitHub usernames.

### Contributing
1. Create a feature branch from dev: git checkout -b feature/sqrt dev
2. Make changes, write tests, and commit.
3. Push your branch and create a Pull Request (target main for review, then merge into dev).
4. After review and verification, merge into dev, test, and finally merge dev into main for the release.

## License
This assignment project has no formal license, however, it is part of Hero Vired Git and GitHub Assignment
