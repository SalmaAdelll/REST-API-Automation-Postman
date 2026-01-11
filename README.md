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

![Run Summary](https://i.ibb.co/vz8N4pB/Rest-API-Automation-Project-Run-Result.png)

### 🔍 Detailed Request Results
| Request Name | Method | Key Validations | Screenshot Link |
| :--- | :--- | :--- | :--- |
| **Get Single User** | `GET` | ID Accuracy, Object Keys | [View Result](https://i.ibb.co/VgnfQvB/GET-Request-1.png) |
| **Get All Users** | `GET` | Status 200, Array Check | [View Result](https://i.ibb.co/YyYf8C8/GET-2-Negative.png) |
| **Get Invalid User** | `GET` | Negative Test (404) | [View Result](https://i.ibb.co/YyYf8C8/GET-2-Negative.png) |
| **Create New User** | `POST` | Status 201, Unique ID | [View Result](https://i.ibb.co/L8yX7M2/POST.png) |
| **Update User (Full)** | `PUT` | Status 200, Data Sync | [View Result](https://i.ibb.co/XWfC2fM/PUT.png) |
| **Update User (Partial)** | `PATCH` | Email Patch Success | [View Result](https://i.ibb.co/fDbH3C0/PATCH.png) |
| **Delete User** | `DELETE` | Empty Body Verification | [View Result](https://i.ibb.co/F8qf9vB/DELETE.png) |
| **Check User Headers** | `HEAD` | Metadata Validation | [View Result](https://i.ibb.co/r7C8zMv/HEAD.png) |
| **Check API Permissions** | `OPTIONS` | Permitted Methods | [View Result](https://i.ibb.co/r7C8zMv/OPTION.png) |

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
