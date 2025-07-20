Purpose: Commands to create, manage, and delete users and groups.
# User & Group Management

## Add User
```bash
sudo useradd brian
sudo passwd brian


#Add Group and Assign User#

sudo groupadd devops
sudo usermod -aG devops brian

#View Users and Groups#
cat /etc/passwd
cat /etc/group

---

##file-permissions.md#

**Purpose**: File ownership, permissions, and `umask`.

```markdown
# File Permissions

## Change Permissions
```bash
chmod 755 file.sh
chmod +x script.sh


Change Ownership
sudo chown brian:brian file.txt

#Umask#
umask 0022

---

##`filesystem-navigation.md`

**Purpose**: Directory structure and navigation.

```markdown
# File System Navigation

## Navigation Commands
```bash
cd /etc
ls -al
pwd






