# BookReview

A Flutter-based mobile application for book reviews.

## Getting Started

Follow the steps below to set up and run the project.

### 1. Set up the Flutter project and Git repository

Run the following commands in your terminal:

```bash
# Create a new Flutter project
flutter create --platforms ios,android --org com.indextrown.bookreview bookreview

# Navigate to the project directory
cd bookreview

# Initialize Git repository
git init

# Add remote repository
git remote add origin https://github.com/indextrown/bookreview.git

# Set main branch
git branch -M main

# Stage all files
git add .

# Initial commit
git commit -m "초기 프로젝트 세팅"

# Push to remote repository
git push -u origin main
```

### 2. Install necessary libraries

Add the required Flutter packages using the following command:

```bash
flutter pub add bloc flutter_bloc go_router equatable

```
