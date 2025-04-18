# restaurantMap

# 🗺️ Busan Restaurant & Parking Map Web Application

A web application that helps users discover popular restaurants in Busan, view nearby public parking spots, and manage their favorite places. The project is built using Spring MVC, MyBatis, Oracle DB, and Kakao Maps API.

---

## 📌 Features

- 🔍 **District-based restaurant search** (filter by 16 districts in Busan)
- 🗺️ **Kakao Map integration** for real-time location display
- 🅿️ **Public parking API integration** (within 500m of selected restaurant)
- ⭐ **Favorites management** (add/remove favorite restaurants)
- 🗨️ **Comment system** (write/delete replies per post)
- 📝 **Bulletin board** with CRUD support (write, edit, delete, view)

---

## ⚙️ Tech Stack

| Layer           | Technology                        |
|----------------|------------------------------------|
| Frontend        | JSP, HTML, CSS, Bootstrap, jQuery |
| Backend         | Java, Spring MVC, MyBatis         |
| Database        | Oracle DB                         |
| External APIs   | Kakao Maps API, Busan Public Data |
| Build Tool      | Maven                             |

---

## 📷 Screenshots

| Home (District Selection) | Restaurant Map View |
|---------------------------|---------------------|
|![스크린샷 2025-04-15 172247](https://github.com/user-attachments/assets/9760881a-356d-4b44-aa05-0ceade064f72)
 | ![스크린샷 2025-04-15 172309](https://github.com/user-attachments/assets/97d5caef-ede1-4d7e-a762-ba9f3fcbafc5) |


---

## 🗃️ Folder Structure (Simplified)
src/ ├── main/ │ ├── java/ │ │ └── com.myproject.mymap/ │ │ ├── controller/ │ │ ├── service/ │ │ ├── dao/ │ │ └── vo/ │ └── resources/ │ └── mybatis/ │ └── mapper/ └── webapp/ ├── WEB-INF/ │ ├── views/ │ └── jsp/ └── resources/

## 💡 How to Run

1. Clone the repository
2. Configure your `Oracle DB` and import the schema (SQL script included)
3. Set your `application.properties` (DB connection, Kakao API key)
4. Run the project via Spring-compatible IDE (e.g., IntelliJ, Eclipse)
5. Access the app at: `http://localhost:8080/`

---

## 📁 External APIs Used

- **Kakao Maps JavaScript SDK**: For displaying maps, markers, polylines, and roadview
- **Busan Public Parking Open API**: Real-time parking info (filtered by proximity)

---
