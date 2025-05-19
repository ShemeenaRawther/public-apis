# 🧪 Public & Free Test Data APIs

A curated list of free and public APIs perfect for testing, prototyping, and mock data generation for web or mobile applications.

---

## 🔢 General Test Data APIs

### [JSONPlaceholder](https://jsonplaceholder.typicode.com)
- **Description**: Fake REST API for testing and prototyping. Supports `GET`, `POST`, `PUT`, and `DELETE` operations.
- **Sample Resources**:  
  `/posts`, `/comments`, `/users`, `/todos`, `/albums`, etc.

---

### [ReqRes](https://reqres.in)
- **Description**: Provides fake users and login/register flows. Supports various HTTP methods.
- **Sample Resources**:  
  `/api/users`, `/api/login`, `/api/register`

---

### [RandomUser.me](https://randomuser.me)
- **Description**: Random user profile generator. Great for testing UI components like user cards or avatars.
- **Sample Endpoint**:  
  `https://randomuser.me/api/`

---

## 📚 Fake Data APIs for Specific Domains

### [FakerAPI](https://fakerapi.it/en)
- **Description**: Generate fake data for blog posts, users, products, companies, and more.
- **Sample Resources**:  
  `/api/v1/persons`, `/api/v1/companies`, `/api/v1/texts`, `/api/v1/products`

---

### [Mockaroo](https://www.mockaroo.com)
- **Description**: UI-based fake data generator. Export to CSV, JSON, SQL, Excel, etc.  
- **Docs**: [Mockaroo API Docs](https://mockaroo.com/api/docs)  
  *Note: Free plan supports up to 200 rows per request.*

---

## 🧪 Mock & Testing Services

### [API Ninjas](https://api-ninjas.com)
- **Description**: Offers a wide variety of public APIs such as jokes, quotes, weather, cryptocurrency, and finance.
- **Auth**: Requires a free API key *(limited usage per day)*

---

### [DummyJSON](https://dummyjson.com)
- **Description**: Fake REST API for products, carts, users, todos, posts, and quotes.
- **Sample Resources**:  
  `/products`, `/carts`, `/users`, `/posts`, `/quotes`
- **Auth**: Includes a login API for testing token-based authentication.  
  - Example:  
    ```json
    {
      "username": "kminchelle",
      "password": "0lelplR"
    }
    ```

---

## 📌 Notes
- Most of these APIs support **CORS** and **HTTPS**.
- These APIs are perfect for front-end/backend testing and demo projects.
- Always check each service’s rate limits and terms of use.
