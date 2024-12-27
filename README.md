# **Expense Tracker**

This project is a multi-platform application to help users track their expenses and incomes. It includes a **Telegram bot**, **Mobile App**, and **Web Client**, allowing users to easily manage their financial activities across different devices.

## **Features**

- **Track Expenses and Incomes**: Users can record their expenses and incomes through Telegram, mobile app, or web interface.
- **Telegram Bot**: Use the Telegram bot to quickly add, view, and manage financial transactions.
- **Mobile App**: A mobile application (iOS/Android) that provides users with an intuitive interface to track their finances.
- **Web Client**: A web-based client for users who prefer using a browser to manage their finances.
- **User Authentication**: Secure login/signup functionality for tracking personal financial data.
- **Statistics and Reports**: Visual representations (charts, tables) of user expenses and incomes over different periods.

## **Technologies Used**

- **Frontend**: React (Web) / React Native (Mobile)
- **Backend**: Node.js / Express.js
- **Database**: MongoDB
- **Telegram Bot**: node-telegram-bot-api
- **Testing**: Jest, Cypress, Supertest
- **Authentication**: JWT (JSON Web Tokens)
- **Styling**: CSS/SCSS (for web), Native styling (for mobile)

## **Project Structure**

```
my_project/
├── client/               # Frontend (Web client)
├── mobile/               # Mobile app (React Native)
├── server/               # Backend (Node.js/Express)
├── bot/                  # Telegram bot
├── tests/                # Testing for the app
├── README.md
└── .gitignore            # Git ignore file
```

## **Installation**

### **Clone the repository**

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker
```

### **Set up the server**

1. Navigate to the `server/` directory:
   ```bash
   cd server
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables (e.g., database credentials, JWT secret) in a `.env` file.

4. Run the server:
   ```bash
   npm start
   ```

### **Set up the client (Web)**

1. Navigate to the `client/` directory:
   ```bash
   cd client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the React web client:
   ```bash
   npm start
   ```

### **Set up the mobile app**

1. Navigate to the `mobile/` directory:
   ```bash
   cd mobile
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the React Native app:
   ```bash
   npx react-native run-android    # For Android
   npx react-native run-ios        # For iOS (macOS only)
   ```

### **Set up the Telegram Bot**

1. Navigate to the `bot/` directory:
   ```bash
   cd bot
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the Telegram bot:
   ```bash
   node index.js
   ```

### **Testing**

To run tests for the server, client, and mobile apps, use the following commands:

#### **For server**:
```bash
cd server
npm test
```

#### **For client**:
```bash
cd client
npm test
```

#### **For mobile**:
```bash
cd mobile
npm test
```

## **Contributing**

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make changes and commit them (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.