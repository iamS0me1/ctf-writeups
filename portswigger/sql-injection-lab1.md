# SQL Injection Lab 1 — PortSwigger
## By Some1 | iamS0me1

### Vulnerability
SQL injection in WHERE clause — hidden data retrieval

### Target
PortSwigger Web Security Academy — Lab 1

### Payload Used
' OR 1=1--

### Steps
1. Found category parameter in URL
2. Added ' OR 1=1-- to bypass WHERE clause
3. All hidden products revealed
4. Lab solved ✅

### Impact
Attacker can retrieve hidden/unreleased 
data from database without authentication

### Lessons Learned
- Always sanitize user input in SQL queries
- Use parameterized queries to prevent SQLi
