# 🎬 Movie Management API  

A **Spring Boot-based Movie Management API** that allows users to **perform CRUD operations on movies**.  
Users can **add, update, delete, search, and filter movies** based on name, director, cast, genre, and release year.  

---

## 🚀 Features  

- ✅ **CRUD Operations** (Create, Read, Update, Delete)  
- 🔍 **Search & Filters** (Find movies by name, director, cast, genre, or year)  
- 📊 **Pagination & Sorting** for optimized data retrieval  
- 🛠️ **Spring Boot, Spring Data JPA, and MySQL** integration  
- 📝 **Postman API Testing** for validating endpoints  

---

## 🛠️ Technologies Used  

- **Spring Boot** – Backend Framework  
- **Spring Data JPA** – Database Interaction  
- **MySQL** – Database Management  
- **Lombok** – Reducing Boilerplate Code  
- **Postman** – API Testing  
- **Maven** – Dependency Management  

---

## 📌 API Endpoints  

### 🔹 **CRUD Operations**  

- **POST** `/api/movies` → Add a new movie  
- **GET** `/api/movies/{id}` → Get movie by ID  
- **PUT** `/api/movies/{id}` → Update movie details  
- **DELETE** `/api/movies/{id}` → Remove a movie  

### 🔹 **Search & Filters**  

- **GET** `/api/movies/search?name=Inception` → Search movies by name  
- **GET** `/api/movies/filter/director?director=Nolan` → Filter movies by director  
- **GET** `/api/movies/filter/cast?cast=DiCaprio` → Filter movies by cast  
- **GET** `/api/movies/filter/genre?genre=Action` → Filter movies by genre  
- **GET** `/api/movies/filter/year?year=2010` → Filter movies by release year  

### 🔹 **Pagination & Sorting**  

- **GET** `/api/movies?page=0&size=5&sortBy=releaseDate`  
  - **Pagination:** Default `page=0`, `size=10`  
  - **Sorting:** Default sorting by `name`  

---

## 🎯 How to Use  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/movie-management-api.git
cd movie-management-api
