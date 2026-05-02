# PHP-DB-Security-Demo 🔓➜🔐

**Database demo: Login VULNERABILE vs SICURO. SQLi hands-on + prepared statements.**

[![PHP](https://img.shields.io/badge/PHP-8.2+-pink)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-8.0+-orange)](https://mysql.com)

<br>

## 📖 Descrizione
**Lab pratico SQL Injection** – Confronta codice vulnerabile vs sicuro.
- **VULNERABILE:** `mysql_query("SELECT * FROM users WHERE id=$_GET[id]")`
- **SICURO:** PDO prepared statements + `password_verify()`
- **Hands-on:** Testa SQLi live → Vedi dump password!
- **XAMPP ready** – 3 minuti setup

  <br>

**Obiettivo CV:** Web application security + secure coding PHP.

<br>

## 🛠 Tech Stack
Database: MySQL demo_users table <br>
Vulnerable: mysql_query(), $_GET raw <br>
Secure: PDO prepared, password_hash ()<br>
Demo: 2 versioni fianco a fianco <br>

<br>

## 🚀 Setup XAMPP (3 min)
```bash
1. XAMPP Apache + MySQL START
2. Importa demo_users.sql
3. http://localhost/db-security/
```

<br>

## 🧪 Test SQL Injection
✅ VULNERABILE <br>
✅ SICURO: 
→ "Invalid query" – BLOCCATO! 

<br>

## 🛡️ Security Lessons
✅ Prepared statements = NO SQLi <br>
✅ PDO > mysql_query (deprecato) <br>
✅ password_hash() / password_verify() <br>
✅ Input validation + sanitization <br>
✅ Error handling (no SQL errors visibili) 

<br>

## 🎓 OWASP Top 10
Injection (SQLi) <br>
Hands-on demo + fix implementati

<br>

## 📄 Licenza
MIT

<br>
---

**© 2026 Suzuka90** | Private Access
