# Live Docs Project

Welcome to the **Live Docs Project**! 🚀

## Overview
This project provides a live document editing experience where users can collaborate and update content in real time.

## Features
- ✅ Live document editing
- ✅ User authentication with Clerk
- ✅ Real-time updates with Liveblocks

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/live-docs-project.git
cd live-docs-project
```
### 2. Install Dependencies
If using Node.js, install the required packages:
```bash
npm install
```
### 3. Set Up Environment Variables
Create a .env.local file in the root directory and add the following:
```bash
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=your_liveblocks_public_key
LIVEBLOCKS_SECRET_KEY=your_liveblocks_secret_key
```
### 4. Run the Project
```bash
npm run dev
```
The project will be available at http://localhost:3000.

## Contributing
Feel free to submit issues or pull requests to improve the project.

## License
This project is licensed under the MIT License.
