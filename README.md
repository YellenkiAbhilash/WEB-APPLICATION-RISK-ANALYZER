# Web Application Risk Analyzer

This is a Node.js-based web application that allows users to log in and access a risk analysis dashboard for assessing the security posture of a web application.

## Features

- User Registration and Login 
- Risk Analysis Dashboard with visual representation 
- Authentication-protected routes
- Responsive UI with Bootstrap styling
- Likelihood and impact scoring for threat and vulnerability assessment

## Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start MongoDB**

   Make sure MongoDB is running on your machine. Default connection is set to:

   ```
   mongodb://localhost:27017/myapp
   ```

4. **Run the app**

   ```bash
   node app.js
   ```

5. **Open in browser**

   Visit: [http://localhost:3000](http://localhost:3000)

## Folder Structure

```
project-root/
│
├── model/
│   └── User.js          # Mongoose schema for users
│
├── views/
│   ├── home.ejs         # Login page
│   ├── secret.ejs       # Risk analysis dashboard (authenticated)
│
├── app.js               # Express application setup and routing
├── package.json         # Node.js dependencies
```
