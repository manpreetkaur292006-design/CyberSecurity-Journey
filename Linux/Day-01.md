# 🐧 Linux Day - 01 

## 📝 Commands Learned

### 1. echo
**Purpose :** This command is just like print command in pyhton.

**Example :** echo "Hello World !"

**Key points to remember :**
 - Linux is case-sensitive : echo, Echo and ECHO are all different.
 - Spaces matter : Make sure there's space between echo and the quotation mark (").
 - The quotes tell echo precisely what string of text to repeat.

### 2. whoami
**Purpose :** Displaying the Current User - This command is asking the computer, "Who am I?" It'll respond with your username.

**Example :** whoami

**Usage :** This command is useful when you're working on different machines or using different accounts.

### id
**Purpose :** Displaying user and group information.
**Example :** id , id root
**Key Points :** In Linux, users are organized into groups. These groups determine the permissions and access rights a user has.
 - **uid:** Your User ID (a unique numerical identifier).
 - **gid:** Your primary Group ID.
 - **groups:** All the groups you are a member of.

### id -un
**Purpose :** Extracting Your Username - This command prints only your username (the name for your current UID).


### man whoami or man id
**Purpose :** used to review the manual pades.
**Synatax :** man <Command_name>
**Example :** man whoami, man id


**Note* : Each user typically has a "home directory" represented by ~.**


### pwd
Full form : Print working directory
Purpose : Show current directory 

echo ~ : this command will display the path to your home directory.

### ls
Purpose : List files and folders - show the contents of your current directory.

ls ~ : this command lists the contents of your home directory, which may be different form your current working directory.

### mkdir 
Purpose : Create directory

### touch 
Purpose : Create file

### cp
Purpose : Copy file 

### mv
Purpose : Move or remove file

### rm
Purpose : Remove file

