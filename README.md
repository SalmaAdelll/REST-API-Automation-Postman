# 🚀 REST API Automation Project | Postman & JavaScript

## 📌 Project Overview
This project is a **Professional API Testing Framework** designed to validate CRUD operations for the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) API. It showcases a robust testing approach, including **Automated Assertions**, **Schema Validation**, and **Performance Benchmarking**.

---

## 🛠️ Tech Stack & Methods
| Category | Tools / Methods |
| :--- | :--- |
| **Tool** | 🟠 Postman |
| **Scripting** | 📜 JavaScript (Chai Assertion Library) |
| **Methods** | `GET`, `POST`, `PUT`, `PATCH`, `DELETE`, `HEAD`, `OPTIONS` |
| **Testing Types** | ✅ Functional, ⚡ Performance, 🛡️ Negative, 🔍 Schema |

---

## 🧪 Key Testing Features
* **✅ Full CRUD Coverage:** Professional validation for creating, reading, updating, and deleting resources.
* **⚡ Performance Benchmarking:** Monitoring response times to ensure high API availability.
* **🛡️ Data Integrity:** Verifying that fields like **ID**, **Name**, and **Email** match expected values.
* **🔍 Schema Validation:** Ensuring JSON objects contain all mandatory keys.
* **🚫 Negative Testing:** Validating system stability with `404 Not Found` scenarios.
* **⚙️ Smart Automation:** Utilizing **Pre-request Scripts** and **Collection Variables** for dynamic testing.

---

## 📊 Test Execution Reports
### 🟢 Overall Run Summary
The entire collection was executed with **25 Passed Assertions** and **0 Failures**.

![Run Summary](https://ibb.co/VpzQ2RGG)

### 🔍 Detailed Request Results
| Request Name | Method | Key Validations | Screenshot Link |
| :--- | :--- | :--- | :--- |
| **Get Single User** | `GET` | ID Accuracy, Object Keys | [View Result](https://ibb.co/5WjWNh1z) |
| **Get All Users** | `GET` | Status 200, Array Check | [View Result](https://ibb.co/YFCKhK3D) |
| **Get Invalid User** | `GET` | Negative Test (404) | [View Result](https://ibb.co/YFCKhK3D) |
| **Create New User** | `POST` | Status 201, Unique ID | [View Result](https://ibb.co/Nq8L6dd) |
| **Update User (Full)** | `PUT` | Status 200, Data Sync | [View Result](https://ibb.co/RTXbcz01) |
| **Update User (Partial)** | `PATCH` | Email Patch Success | [View Result](https://ibb.co/wFzFYrxH) |
| **Delete User** | `DELETE` | Empty Body Verification | [View Result](https://ibb.co/pBDwnhML) |
| **Check User Headers** | `HEAD` | Metadata Validation | [View Result](https://ibb.co/21xFQ58z) |
| **Check API Permissions** | `OPTIONS` | Permitted Methods | [View Result](https://ibb.co/mCzrndM4) |

---

## 🚀 How to Run
1. **Download** the `REST_API_Automation_Project.json` file from this repository.
2. **Open Postman** and click **Import**.
3. **Set Environment Variable** `{{baseUrl}}` to `https://jsonplaceholder.typicode.com`.
4. **Open Collection Runner** and hit **Run**.

---

## 📬 Contact Me
If you have any questions or would like to discuss this project, feel free to reach out:

* **LinkedIn:** [Salma Adel](https://www.linkedin.com/in/salma-adel-891ab0180)
* **Email:** [salma.adelmo123@gmail.com](mailto:salma.adelmo123@gmail.com)
* **Role:** **QA Automation Engineer** 💻

---
**Developed by: Salma**
