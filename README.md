# Test_1 Repo
```bash
# Install WSL and Ubuntu
wsl --install  # Installs WSL and Ubuntu Linux distro

# Open Ubuntu and create a UNIX user (manual step shown during setup)

# Update package list and install Git
sudo apt update                     # Updates package index
sudo apt install git -y            # Installs Git

# Configure Git with your GitHub info
git config --global user.name "Harshita"                          # Sets your Git username
git config --global user.email "harshita.bachoo@bdo.mu"          # Sets your Git email

# Create a test project folder
mkdir git-test && cd git-test     # Creates and moves into a test Git project folder

# Create a file
echo "Hello Git!" > hello.txt     # Creates a test file with content

# Initialize Git repository
git init                          # Initializes a new Git repo

# Stage and commit changes
git add hello.txt                 # Stages the file
git commit -m "Initial commit"   # Commits with a message

# Connect to GitHub repository
git remote add origin https://github.com/Harshita10B/Test_1.git  # Links local repo to GitHub
git branch -M main               # Renames the current branch to 'main'
git push -u origin main          # Pushes code to GitHub

# Create and switch to a new branch
git checkout -b feature-1        # Creates and switches to 'feature-1' branch

# Create and edit a second file
echo "File_2" > file2.txt        # Creates a second test file
nano file2.txt                   # Opens file2.txt in the nano editor

# Stage and commit the new file
git add file2.txt                # Stages second file
git commit -m "Add file2.txt"    # Commits the file

# Push new branch to GitHub
git push -u origin feature-1     # Pushes feature-1 branch to GitHub

# Edit file2.txt in VS Code (manual step), then:
git add file2.txt                # Stages updated file
git commit -m "Edit file2.txt in feature-1"  # Commits changes
git push                         # Pushes to GitHub

# Create a README
echo "# Test_1 Repo" > README.md # Creates a README.md with a title
nano README.md                   # Opens README for editing
git add README.md                # Stages the README file
git commit -m "Add README.md"    # Commits the README
git push                         # Pushes it to GitHub
```

