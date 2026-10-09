# Module 2: Cloud Linux Server Deployment & Management

Successfully deployed and configured an Ubuntu cloud virtual machine on AWS EC2, managed file permissions, and hosted a custom web server.

## 🚀 Tasks Completed
1. **Cloud VM Provisioning:** Launched an AWS EC2 instance running Ubuntu 24.04 LTS (`t2.micro` free-tier eligible).
2. **Secure Access:** Connected via AWS EC2 Instance Connect / SSH over Port 22.
3. **User & Group Administration:**
   - Created a new user: `intern_user`
   - Created a group: `cloud_devs` and assigned the user to it.
4. **File Permissions & Ownership (`chmod` / `chown`):**
   - Configured custom directory ownership (`chown intern_user:cloud_devs`).
   - Applied octal permissions (`chmod 750`) ensuring strict role-based access.
5. **Web Service Deployment (Nginx):**
   - Installed and started the Nginx web server via `systemctl`.
   - Configured custom HTML landing page.
   - Tested local connectivity using `curl http://localhost` and public browser access via EC2 Public IPv4.

---
*Completed by Omar Maher Alkhamaiseh*
