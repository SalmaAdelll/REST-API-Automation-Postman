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

<img width="925" height="509" alt="Rest API Automation Project Run Result " src="https://github.com/user-attachments/assets/7572ab50-c1d8-4aeb-bac3-bb8029552115" />


### 🔍 Detailed Request Results
| Request Name | Method | Key Validations | Screenshot Link |
| :--- | :--- | :--- | :--- |
| **Get Single User** | `GET` | ID Accuracy, Object Keys | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQCINeqdHxqvSZl2OhzF45jWAUJdh3BS1HrvB0PAKLccdqo?e=sSWRhr) |
| **Get All Users** | `GET` | Status 200, Array Check | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQAjePCLKIBVSYCzmaGsKgx1AZzXEH2sDE2HuzHPdYW38AM?e=bKnCmU) |
| **Get Invalid User** | `GET` | Negative Test (404) | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQAjePCLKIBVSYCzmaGsKgx1AZzXEH2sDE2HuzHPdYW38AM?e=bKnCmU) |
| **Create New User** | `POST` | Status 201, Unique ID | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQCoLFC0rgP9RZYaXNYkO8JrARCAKnDZpAM5AM-MIt6OrH4?e=Zzyxla) |
| **Update User (Full)** | `PUT` | Status 200, Data Sync | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQDwvfIqD0thSIAXBXc3-ZjmAZ_xgUX7Nm0lOYR7f2TiPFk?e=CoQ0c6) |
| **Update User (Partial)** | `PATCH` | Email Patch Success | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQCXA7q4zrykRLQAjUYmHmGvAaaYWTJquv4pH9PA_H5_hK8?e=a4aVyl) |
| **Delete User** | `DELETE` | Empty Body Verification | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQBnQQKv7Vi_TaYX3QElT425AXbDMLMjxxAjhobqol05qwo?e=Yeil3U) |
| **Check User Headers** | `HEAD` | Metadata Validation | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQAKm8dCIW7mSYnwflTQTmn0AZe8R3_5Gq2OA1Ka7Srxdn8?e=2tgYgo) |
| **Check API Permissions** | `OPTIONS` | Permitted Methods | [View Result](https://1drv.ms/i/c/f047d8e8f96d3a34/IQAoVDApqZbFR4mVjNdopvrPAbBwwT8JpK_w1kqThtkuy0U?e=9IJHWN) |

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
