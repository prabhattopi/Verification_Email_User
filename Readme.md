
# Email Verification App

A Dashboard with an email support feature with sso

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/prabhattopi/Verification_Email_User.git
```

### Navigate to the Project Directory For Backend

```bash
cd backend
```

### Add variables in .env file 

You can get this variables in google console and mogodb uri either use local or atlas and for refresh token got oauth playground

```bash
PORT=5000
MONGO_URI=
JWT_SECRET=your_jwt_secret_key
GOOGLE_CLIENT_SECRET=
GOOGLE_CLIENT_ID=
MAIL_CLIENT_ID=
MAIL_CLIENT_SECRET=
MAIL_REFRESH_TOKEN=
SENDER_EMAIL_ADDRESS=
```

### Run the Application

To start the application in development mode:

```bash
npm run dev
```

### Navigate to the Project Directory For Fronted

```bash
cd frontend
```
### Add variables in .env file 

You can get this variables in google console

```bash
VITE_APP_GOOGLE_CLIENT_ID=
VITE_APP_BASE_URL=http://localhost:5000/api
```

### Run the Application

To start the application in development mode:

```bash
npm run dev
```