# Apache Web Server Project – John Abbott College

This is a completed project for the **Network Installation and Administration I** course at John Abbott College.

The project involved setting up and securing an Apache web server using AlmaLinux. It includes subnet-based access control, user authentication, file-level restrictions, and departmental site separation.

## 📁 Project Tasks

- ✅ Apache setup with custom DocumentRoot: `/var/www/html_project1`
- ✅ Homepage with HTML links and tags
- ✅ 7 secure directories (user + subnet restrictions)
- ✅ 4 project directories with `.txt`, `.gif`, `.html`, and `test.html` access rules
- ✅ Departmental directories with Aliases and access rules (vendors, accountants, etc.)

## 📂 Project Structure

- [`httpd.conf`](./httpd.conf) – Apache server configuration
- [`html_project1/`](./html_project1) – Homepage and public site content
- [`htdocs/`](./htdocs) – Project and department directories (Project1–4, vendors, etc.)

## 📎 Quick Access – Key Files

🔧 **Apache Config**
- [`httpd.conf`](./apache-webserver-files_project1/etc/httpd/conf/httpd.conf)

🖥️ **Homepage & HTML**
- [`index.html`](./apache-webserver-files_project1/var/www/html_project1/index.html)

## 📄 Additional Files

- `Guillermo_PadillaKeymole_Report_P1.pdf` – Final documented report with screenshots
- `Projet-Part I_Apache.pdf` – Official project instructions
- `guillermopk_project1.tar` – Archived backup of the full config and project directories

📄 **Documents**
- [`Report PDF`](./Guillermo_PadillaKeymole_Report_P1.pdf)
- [`Instructions PDF`](./Projet-Part I_Apache.pdf)
- [`Original .tar archive`](./guillermopk_project1.tar)

## 🔐 Features Demonstrated

- Apache directives: `<Directory>`, `.htaccess`, `RequireAll`, `RequireAny`
- Subnet-based and user-based access control
- File-level restrictions using `.txt`, `secret.*`, `*.gif`, etc.
- Virtual hosting and alias setup
- Bash scripting and firewall validation
- Tested from multiple subnets and browsers

## 👨‍💻 Author

**Guillermo Padilla Keymole**  
Network Administration AEC Student  
John Abbott College
