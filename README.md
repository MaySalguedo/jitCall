# JitCall - Modern Contact Management Platform

[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io)
[![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white)](https://ionicframework.com)
[![Licence: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://mit-license.org/)

A modern contact management solution with real-time synchronization and secure cloud storage.

## Features ✨

- **Contact Management**
  - Create, Read, Update, Delete (CRUD) contacts
  - Rich contact profiles

- **Security & Authentication**
  - Firebase Authentication (Email/Password, Google)
  - End-to-end data encryption
  - Session management

- **Cloud Integration**
  - Real-time sync with Firebase Firestore
  - Cloud Storage for contact media
  - Firebase Cloud Functions integration
  - Automated backups

- **UI/UX**
  - Responsive design
  - Dark/Light mode support
  - Cross-platform compatibility
  - Accessibility optimized

## Tech Stack 🛠️

**Core Technologies**
- **Frontend:** Angular 15+, Ionic 6+
- **Backend:** Firebase (Firestore, Auth, Storage, Functions)
- **State Management:** RxJS
- **UI Components:** Ionic Framework
- **Image Handling:** Cloudinary Integration

**Key Packages**
- `@angular/fire` - Firebase integration
- `@ionic/storage` - Local data persistence
- `rxjs` - Reactive programming

## Screenshots

<div align="center"> <img src="src/assets/img/login.png" alt="Login Screen" width="200" style="margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/> <img src="src/assets/img/contacts.png" alt="Contact List" width="200" style="margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/> <img src="src/assets/img/chats.png" alt="Chats" width="200" style="margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/> </div> <div align="center"> <img src="src/assets/img/chat.png" alt="Chat Screen" width="200" style="margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/> <img src="src/assets/img/group.png" alt="Group Chat" width="200" style="margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/> <img src="src/assets/img/update_user.png" alt="User Update" width="200" style="margin: 10px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/> </div>

## Getting Started 🚀

### Prerequisites
- Node.js v16+
- Firebase account
- Ionic CLI (`npm install -g @ionic/cli`)

### Installation

1. Clone repository:
```bash
git clone https://github.com/Dandelionield/jitCall.git
cd jitcall
npm install