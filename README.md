# Backend

Backend for Blog App
using Node.js, Express.js, and MongoDB.

## Features are
- User Authentication
- Google Login
- Create Blog
- View Blogs
- Edit Blog
- Delete Blog
- Image Upload
- JWT Authentication
- REST API
- MongoDB Connection

## Packages Used

Install Express:
npm install express

Install Mongoose:
npm install mongoose

Install CORS:
npm install cors

Install Dotenv:
npm install dotenv

Install JWT:
npm install jsonwebtoken

Install Bcrypt:
npm install bcrypt

Install Cookie Parser:
npm install cookie-parser

Install Express Session:
npm install express-session

Install Passport:
npm install passport

Install Google OAuth:
npm install passport-google-oauth20

Install Multer:
npm install multer

Install Cloudinary:
npm install cloudinary

Install Nodemailer:
npm install nodemailer


### Backend Folder Structure

- APIs
  - AdminAPI.js
  - AuthorAPI.js
  - CommonAPI.js
  - userAPI.js

- config
  - cloudinary.js
  - cloudinaryUpload.js
  - multer.js
  - passport.js

- middlewares
  - checkoutuser.js
  - verifyTokens.js

- Models
  - AdminModel.js
  - ArticleModel.js
  - UserModel.js

- node_modules

- services

- utils
  - emailService.js

- .env
- .gitignore
- package-lock.json
- package.json
- README.md


- req.http
- server.js

## To Run Project

npm install
nodemon server.js


## Environment Variables

env
PORT=5000
DB_URL=your_mongodb_url
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
