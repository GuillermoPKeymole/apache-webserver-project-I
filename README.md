# Apache Web Server Project – John Abbott College

This is a completed project for the **Network Installation and Administration I** course at John Abbott College.

The project involved setting up and securing an Apache web server using AlmaLinux. It includes subnet-based access control, user authentication, file-level restrictions, and departmental site separation.

---

## 📁 Project Tasks

- ✅ Apache setup with custom DocumentRoot: `/var/www/html_project1`
- ✅ Homepage with HTML links and tags
- ✅ 7 secure directories (user + subnet restrictions)
- ✅ 4 project directories with `.txt`, `.gif`, `.html`, and `test.html` access rules
- ✅ Departmental directories with Aliases and access rules (vendors, accountants, etc.)

---

## 📂 Project Structure

- [`httpd.conf`](./apache-webserver-files_project1/etc/httpd/conf/httpd.conf) – Apache server configuration
- [`html_project1/`](./apache-webserver-files_project1/var/www/html_project1) – Homepage and secure/project directories
- [`htdocs/`](./apache-webserver-files_project1/var/www/htdocs) – Departmental folders with access restrictions

---

## 📎 Quick Access – Key Files

🔧 **Apache Config**
- [`httpd.conf`](./apache-webserver-files_project1/etc/httpd/conf/httpd.conf)

🖥️ **Homepage**
- [`index.html`](./apache-webserver-files_project1/var/www/html_project1/index.html)

📄 **Documents**
- [`Project Report`](./Guillermo_PadillaKeymole_Report_P1.pdf)
- [`Project Instructions`](./Projet-Part I_Apache.pdf)
- [`Original .tar archive`](./guillermopk_project1.tar)

---

## 🔐 Features Demonstrated

- Apache directives: `<Directory>`, `.htaccess`, `RequireAll`, `RequireAny`
- Subnet-based and user-based access control
- File-level restrictions using `.txt`, `secret.*`, `*.gif`, etc.
- Virtual hosting and alias setup
- Bash scripting and firewall validation
- Tested across multiple subnets and browsers

---

## 👨‍💻 Author

**Guillermo Padilla Keymole**  
Network Administration AEC Student  
John Abbott College
