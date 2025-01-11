# Java React Full Stack E-Commerce Project

## 🚀 Project Overview
A comprehensive full-stack e-commerce web application developed using Java Spring Boot for the backend and React for the frontend. This project demonstrates modern web development practices and provides a robust, scalable online shopping platform.

## 🛠 Technologies Used
- **Backend**: 
  - Java 21
  - Spring Boot 3.2.3
  - Spring Data JPA
  - Spring Security
- **Frontend**:
  - React.js
  - React Hooks
  - Axios for API calls
- **Database**:
  - MySQL
  - Redis (Optional)
- **Build Tools**:
  - Maven
  - npm/yarn

## 📋 Prerequisites
- Java Development Kit (JDK) 21
- Node.js 16+
- MySQL Database
- Maven
- npm or yarn

## 🔧 Setup and Installation

### Backend Setup
1. Clone the repository
   ```bash
   git clone https://github.com/LohiyaH/e-commerce-springboot-react.git
   cd e-commerce-springboot-react
   ```

2. Configure Database
   - Open `src/main/resources/application.properties`
   - Update database connection details
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

3. Build and Run Backend
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend Setup
1. Navigate to frontend directory
   ```bash
   cd frontend
   ```

2. Install Dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Run Frontend
   ```bash
   npm start
   # or
   yarn start
   ```

## 🧪 Running Tests
- Backend Tests: `mvn test`
- Frontend Tests: `npm test` or `yarn test`

## 🚢 Deployment
- Backend: Deploy to cloud platforms like AWS, Azure, or Google Cloud
- Frontend: Deploy static files to Netlify, Vercel, or similar platforms
- Database: Configure production database connection

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact
Email - harshrlohiya@gmail.com

Project Link: [https://github.com/LohiyaH/e-commerce-springboot-react](https://github.com/LohiyaH/e-commerce-springboot-react)
