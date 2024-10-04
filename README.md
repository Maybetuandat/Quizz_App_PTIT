markdown
Copy code
# Quiz App - PTIT

This is a web-based Quiz App project built for the Web Programming course at PTIT using **Express.js** for the backend and **Pug** as the templating engine for the frontend.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (login/register)
- Quiz creation and management
- Quiz participation and scoring
- Real-time updates and ranking
- Mobile-friendly design

## Tech Stack

- **Backend:** Express.js (Node.js)
- **Frontend Templating:** Pug
- **Database:** MongoDB
- **Styling:** Bootstrap / Custom CSS

## Installation

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
  
### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
Install the dependencies:

bash
Copy code
npm install
Set up the environment variables. Create a .env file in the root directory and add the following:

bash
Copy code
MONGODB_URI=<your-mongodb-uri>
SECRET_KEY=<your-secret-key>
Start the server:

bash
Copy code
npm start
Navigate to http://localhost:3000 in your browser.

Usage
Register a new account or log in with an existing account.
Create or participate in a quiz.
View your results and real-time rankings.
Screenshots
Login Page


Quiz Page

Deployment
The app is deployed at: Quiz App

To deploy the app yourself:

Set up your server environment (e.g., DigitalOcean, Heroku).
Push your code to the server.
Install the required packages and set up your environment variables.
Start the application on the server.
Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Fork the project
Create your feature branch (git checkout -b feature/new-feature)
Commit your changes (git commit -m 'Add some new feature')
Push to the branch (git push origin feature/new-feature)
Open a pull request
License
This project is licensed under the MIT License - see the LICENSE file for details.

less
Copy code

### Hướng dẫn chi tiết:

1. **Clone dự án**: Dùng lệnh `git clone` với đường dẫn của repo.
2. **Cài đặt dependencies**: Chạy `npm install` để cài đặt tất cả các gói cần thiết.
3. **Cấu hình môi trường**: Tạo file `.env` và cấu hình các biến môi trường như kết nối MongoDB và key bảo mật.
4. **Chạy server**: Sử dụng lệnh `npm start` để khởi động server cục bộ.

Bạn có thể thay đổi chi tiết đường dẫn và hình ảnh trong phần **Screenshots**.
