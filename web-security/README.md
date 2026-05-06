# 🌐 Web Application Security Testing

## 🎯 Objective
Assess web application security by identifying common vulnerabilities, testing authentication mechanisms, and analyzing insecure functionality.

---

## 🛠 Tools Used
- Burp Suite
- Gobuster
- Browser Developer Tools
- SQL Injection Testing
- XSS Testing

---

## 🔍 Activities Performed

### 🔐 Authentication & Access Testing
- Tested login functionality and authentication workflows.
- Investigated access control weaknesses and hidden application endpoints.
- Analyzed HTTP requests and responses using Burp Suite.

### 💉 SQL Injection Testing
- Performed SQL Injection testing on vulnerable input fields.
- Tested payloads to identify database query manipulation vulnerabilities.
- Investigated insecure user input handling.

### ⚠️ Cross-Site Scripting (XSS)
- Tested input validation mechanisms for XSS vulnerabilities.
- Used Burp Suite to bypass client-side validation.
- Injected test payloads to identify insecure script handling.

### 📂 Directory Enumeration
- Performed directory and endpoint enumeration using Gobuster.
- Identified hidden directories, restricted endpoints, and HTTP status responses.
- Investigated 403 Forbidden responses and exposed resources.

### 🌍 Web Traffic Analysis
- Intercepted and modified HTTP requests and responses.
- Reviewed headers, cookies, and session-related information.
- Investigated client-server communication behavior.

---

## 🔎 Example Commands & Payloads Used

```bash
gobuster dir -u http://target-ip -w common.txt

' OR '1'='1
<script>alert('XSS')</script>
```

---

## 🧭 Investigation Methodology
1. Performed reconnaissance and directory enumeration.
2. Intercepted requests using Burp Suite.
3. Tested input fields for SQL Injection and XSS vulnerabilities.
4. Analyzed server responses and authentication behavior.
5. Identified insecure endpoints and improper validation mechanisms.

---

## 🚩 Key Findings
- Identified vulnerable input validation mechanisms.
- Detected SQL Injection and XSS vulnerabilities.
- Discovered hidden directories and restricted endpoints.
- Observed insecure handling of client-side validation.

---

## 🛡 Security Recommendations
- Implement server-side input validation and sanitization.
- Use parameterized queries to prevent SQL Injection.
- Apply secure authentication and session management practices.
- Restrict access to sensitive endpoints and directories.

---

## 💡 Skills Demonstrated
- Web Application Security Testing
- SQL Injection Testing
- Cross-Site Scripting (XSS)
- Directory Enumeration
- HTTP Request Analysis
- Burp Suite Usage

---

## 📚 Learning Outcome
This project improved my understanding of web application vulnerabilities, HTTP request analysis, authentication testing, and secure input validation practices.
