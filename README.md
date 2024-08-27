# Micro Frontend Angular Application

This repository is a Micro Frontend (MFE) application built using Angular 17 and Node.js 18+. The project demonstrates the use of Webpack Module Federation for integrating multiple Angular micro frontends into a single application.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Angular**: Version 17
- **Node.js**: Version 18 or above
- **npm**: Installed with Node.js (version 9.x or above)

## Getting Started

### Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/Jazaa-Jr/micro-frontend-Angular17.git
cd micro-frontend-Angular17

####Install Dependencies
# For MFE1
cd mfe1
npm install

# For MFE2
cd ../mfe2
npm install

# For Main App
cd ../main-app
npm install

#####Start the Micro Frontends
# Start MFE1
cd mfe1
ng serve --port 3001

# Start MFE2
cd ../mfe2
ng serve --port 3002

######Start the Main Application
cd ../main-app
ng serve

