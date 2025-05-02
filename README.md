# Apache Web Server Project – John Abbott College

This is a completed project for the **Network Installation and Administration I** course at John Abbott College.

The project involved setting up and securing an Apache web server using AlmaLinux. It includes subnet-based access control, user authentication, file-level restrictions, and departmental site separation.

## 📁 Project Tasks

- ✅ Apache setup with custom DocumentRoot: `/var/www/html_project1`
- ✅ Homepage with HTML links and tags
- ✅ 7 secure directories (user + subnet restrictions)
- ✅ 4 project directories with `.txt`, `.gif`, `.html`, and `test.html` access rules
- ✅ Departmental directories with Aliases and access rules (vendors, accountants, etc.)

## 📄 Files Included

- `Guillermo_PadillaKeymole_Report_P1.pdf` – Final documented report with screenshots
- `Projet-Part I_Apache.pdf` – Project instructions
- `guillermopk_project1.tar` – Archive with:
  - `/etc/httpd/conf/httpd.conf`
  - `/var/www/html_project1/`
  - `/var/www/htdocs/`

## 🔐 Features Demonstrated

- Apache directives: `<Directory>`, `.htaccess`, `RequireAll`, `RequireAny`
- Subnet and user authentication
- File-based access restrictions (`.txt`, `secret.*`, `*.gif`, etc.)
- Virtual hosting and alias configuration
- Bash scripting and firewall configuration
- Testing via browser + IP-based simulations

## 📍 Author

**Guillermo Padilla Keymole**  
Network Administration AEC Student  
John Abbott College
