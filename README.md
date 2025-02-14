# StockStack

StockStack is a comprehensive **inventory management system** designed for E Mart grocery store. It helps businesses efficiently manage their products, orders, vendors, and sales tracking with user authentication and access control.

## 📂 Project Structure

```
StockStack/
│── frontend/               # React.js frontend
│── stockstackbackend/      # Spring Boot backend
│── README.md               # Project documentation
```

## 🚀 Features

- **Product Management**: Add, update, delete, and view products.
- **Order Management**: Create, view, and track orders with multiple products.
- **Vendor Management**: Add, update, and delete vendors for inventory supplies.
- **Sales Tracking**: Monitor product sales over time.
- **User Authentication**: Each user manages their own inventory.
- **Pro Access Feature**: Graphical representation of product sales and price trends.

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS (for styling)
- Axios (for API requests)

### Backend
- Spring Boot (Java)
- MySQL (Database)
- Spring Security (for authentication & authorization)
- JPA/Hibernate (for ORM)

## 🔧 Setup & Installation

### 1️⃣ Clone the Repository
```bash
 git clone https://github.com/Bhuvan0123/StockStack.git
 cd StockStack
```

### 2️⃣ Backend Setup (Spring Boot)
```bash
 cd stockstackbackend
 mvn clean install
 mvn spring-boot:run
```
- Ensure MySQL is running, and update `application.properties` with your database credentials.

### 3️⃣ Frontend Setup (React.js)
```bash
 cd frontend
 npm install
 npm start
```
- This will start the frontend on `http://localhost:3000/`.

## 📌 API Endpoints
| Endpoint          | Method | Description |
|------------------|--------|-------------|
| `/api/products`  | GET    | Fetch all products |
| `/api/orders`    | POST   | Create a new order |
| `/api/vendors`   | DELETE | Remove a vendor |

More details are available in the backend documentation.

## 🤝 Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## 📜 License
This project is licensed under the MIT License.

---

🚀 **StockStack** - Simplifying Inventory Management! 🛒

