# Product Inventory Management

> Product Inventory Management is a backend API project designed to teach the fundamentals of authentication and CRUD operations using Node.js, Express, and MongoDB. The system allows users to securely register and log in to receive a JSON Web Token (JWT). Authenticated users can then manage an inventory by adding new products, viewing the entire catalog or specific product IDs, updating product details, and deleting entries, ensuring that sensitive data modification is protected by secure token verification.

## 🚀 About the Project

### Key Features

- **Feature 1:** User registration, secure login, and authentication.
- **Feature 2:** Real-time product add, get, update, and delete operations.

---

## 🛠️ Built With

- Node.js and Express, JWT for authentication, and bcrypt
- MongoDB

---

## 💻 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js v14+
- npm or yarn

### Installation

1.  **Clone the repository**

    ```bash
    git clone [https://github.com/kanagasakthivel26/product-inventory-management.git](https://github.com/kanagasakthivel26/product-inventory-management.git)
    cd product-inventory-management
    ```

2.  **Install dependencies**

    ```bash
    npm install
    ```

3.  **Configure Environment Variables**
    - Create a `.env` file in the root directory.
    - Add the following variables:
      ```env
      MONGO_URI=your_database_url
      PORT=Your server port
      SECRET_KEY=For JWT
      ```

4.  **Run the application**

    ```bash
    node server.js
    ```
