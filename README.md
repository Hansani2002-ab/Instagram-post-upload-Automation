# 📸 Instagram Post Automation Suite
> **A robust automation framework built with Selenium Java to streamline Instagram content workflows and validation.**

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Automation](https://img.shields.io/badge/Test_Automation-blue?style=for-the-badge)

## 📋 Project Overview
This project is a comprehensive automation suite designed to test the end-to-end functionality of the Instagram web application. It focuses specifically on the **Post Upload** workflow, ensuring that the platform handles valid inputs correctly while gracefully managing errors and edge cases.

---

## 🛠️ Tech Stack
* **Language:** Java
* **Automation Engine:** Selenium WebDriver
* **Architecture:** Modular Scripting (Page Object Model principles)
* **Testing Coverage:** Functional, Boundary, and Negative Testing

---

## 🧪 Test Coverage
The suite includes the following automated test scenarios:

### 🔑 Authentication & Access
* **Login Flow:** Automates the secure login process from the landing page to the homepage.
* **Security Validation:** Verifies system behavior when login attempts are made with invalid passwords.

### 🖼️ Content Uploading
* **Standard Post:** End-to-end flow of selecting an image and publishing.
* **UI Elements:** Validation of the "New Post" button and navigation icons.

### ⚠️ Edge Cases & Negative Testing

| Test Class | Objective |
| :--- | :--- |
| `InvalidImagePathTest` | Validates error handling for broken or missing file paths. |
| `unsupportedFileUpload` | Ensures only allowed file types (JPEG, PNG) are uploaded. |
| `longCaptionPostTest` | Tests the platform's behavior with character-heavy captions. |
| `withoutcaptionTest` | Verifies the ability to post without text descriptions. |
| `postWithoutImage` | Ensures the system prevents posting empty content. |

---

## 🚀 Getting Started

### Prerequisites
* **Java JDK:** 11 or higher.
* **Web Driver:** ChromeDriver or GeckoDriver (ensure version matches your browser).
* **IDE:** IntelliJ IDEA, Eclipse, or VS Code.

### Installation & Execution
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Hansani2002-ab/Instagram-post-upload-Automation.git](https://github.com/Hansani2002-ab/Instagram-post-upload-Automation.git)
