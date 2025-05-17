# 🎓 Online Result System (ORS)

A modernized **Online Result Management System** for colleges/universities, rebuilt using **Java**, **JSP**, **HTML**, **CSS (Bootstrap)**, **Hibernate**, and **MySQL** with a clean implementation of the **MVC (Model-View-Controller)** architecture.

This system allows **administrators** to manage student records and **students** to securely view their academic results online with a mobile-responsive and interactive interface.

---

## 🚀 Key Features

- 🔐 Admin and student login with authentication
- 🧾 CRUD operations for student records and exam results
- 📊 Result display with subject-wise marks and grades
- 📱 Fully responsive UI using **Bootstrap 5**
- 💾 Hibernate integration for ORM-based database interaction
- ⚙️ Follows **MVC** pattern for clean code separation

---

## 🛠️ Technologies Used

| Technology     | Purpose                          |
|----------------|----------------------------------|
| Java           | Backend logic                    |
| JSP            | View rendering                   |
| HTML/CSS       | Frontend structure               |
| Bootstrap      | Responsive design                |
| Hibernate ORM  | Database interaction layer       |
| MySQL          | Relational database              |
| MVC Pattern    | Clean architecture               |

---


## 📁 Project Structure

```plaintext
OnlineResultSystem/
│
├── src/
│   ├── controller/         # Servlets and controllers
│   ├── model/              # Hibernate entity classes, DAOs
│   ├── util/               # Hibernate configuration, helper classes
│   └── view/               # JSP pages (UI)
│
├── WebContent/
│   ├── css/                # Custom styles
│   ├── js/                 # JavaScript files
│   ├── images/             # Image assets
│   └── WEB-INF/            # web.xml, lib dependencies
│
├── hibernate.cfg.xml       # Hibernate configuration
├── database/schema.sql     # MySQL database schema
└── README.md
