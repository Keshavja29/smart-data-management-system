# Smart Data Management System 🗄️

Enterprise-grade data management platform with AI-powered duplicate detection, intelligent data cleaning, and advanced search capabilities.

## 🌟 Features

- **CRUD Operations** - Complete Create, Read, Update, Delete functionality
- **AI Duplicate Detection** - Machine learning-based duplicate record identification
- **Smart Data Cleaning** - Automated data validation and cleaning
- **Advanced Search** - Multi-field search with filters and sorting
- **Bulk Operations** - Import/Export CSV, Excel, JSON
- **Data Validation** - Real-time validation with custom rules
- **Audit Trail** - Track all data changes with timestamps
- **Role-Based Access** - User permissions and access control

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Material-UI
- Axios
- React Table
- React Hook Form

**Backend:**
- Java Spring Boot
- Spring Data JPA
- Spring Security
- Hibernate

**Database:**
- PostgreSQL

**AI/ML:**
- Python scikit-learn
- Fuzzy matching algorithms
- Data deduplication models

## 📋 Prerequisites

- Java 17+
- Node.js 14+
- PostgreSQL 13+
- Maven
- npm/yarn

## 🚀 Installation

### Backend Setup

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

### Database Setup

```sql
CREATE DATABASE smart_data_db;
```

## 📁 Project Structure

```
smart-data-management-system/
├── backend/
│   ├── src/main/java/com/smartdata/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── model/
│   │   ├── config/
│   │   └── util/
│   └── pom.xml
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
└── README.md
```

## 🎯 Key Features Explained

### 1. AI Duplicate Detection
Uses Levenshtein distance and fuzzy matching to identify potential duplicates with confidence scores.

### 2. Smart Data Cleaning
- Remove null/empty values
- Standardize formats
- Validate data types
- Fix inconsistencies

### 3. Advanced Search
- Full-text search
- Multi-field filtering
- Date range queries
- Custom sorting

## 📊 API Endpoints

### Data Management
- `GET /api/data` - Get all records
- `GET /api/data/{id}` - Get single record
- `POST /api/data` - Create new record
- `PUT /api/data/{id}` - Update record
- `DELETE /api/data/{id}` - Delete record

### AI Features
- `POST /api/ai/detect-duplicates` - Find duplicates
- `POST /api/ai/clean-data` - Clean dataset
- `POST /api/ai/validate` - Validate data

### Bulk Operations
- `POST /api/bulk/import` - Import data
- `GET /api/bulk/export` - Export data

## 🔧 Configuration

`application.properties`:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/smart_data_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

## 📸 Screenshots

(Add screenshots here)

## 🤝 Contributing

Contributions welcome! Please submit a Pull Request.

## 📝 License

MIT License

## 👨‍💻 Author

**Keshav Jadam**
- GitHub: [@Keshavja29](https://github.com/Keshavja29)
- LinkedIn: [Keshav Jadam](https://linkedin.com/in/keshav-jadam)
