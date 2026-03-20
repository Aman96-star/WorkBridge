# WorkBridge
Employee Management System is a web-based application developed using Java and Spring Boot It improves data management, reduces manual work, and ensures organized employee record handling.

FLOW DIAGRAM & FILE STRUCTURE
WorkBridge/
│
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/workbridge/
│   │   │   │   ├── controller/
│   │   │   │   ├── service/
│   │   │   │   ├── repository/
│   │   │   │   ├── entity/
│   │   │   │   ├── dto/
│   │   │   │   ├── config/
│   │   │   │   ├── exception/
│   │   │   │   └── WorkBridgeApplication.java
│   │   │   │
│   │   │   └── resources/
│   │   │       ├── application.yml
│   │   │       ├── static/
│   │   │       └── templates/
│   │   │
│   │   └── test/
│   │
│   ├── pom.xml
│   └── Dockerfile
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── context/
│   │   ├── utils/
│   │   ├── styles/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── Dockerfile
│
├── docs/
│   ├── architecture.md
│   ├── api-docs.md
│   ├── database-schema.md
│   ├── setup-guide.md
│   └── screenshots/
│
├── scripts/
│   ├── setup.sh
│   ├── run.sh
│   └── db-init.sql
│
├── .github/
│   └── workflows/
│       ├── backend-ci.yml
│       └── frontend-ci.yml
│
├── docker-compose.yml
├── .gitignore
├── README.md
└── LICENSE
