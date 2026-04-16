# Level 1: advanced Operations

 _ I evolved my workflow to handle profissional environments more efficiently:
 * Bulk creation - Mastered: `mkdir -p project/{backend,frontend,database,cybersecurity,financial,RH}`
 * Recursive Power - Mastered: `rm -rf`
 * Copy directories - Mastered: `cp -r`
 * Move files and rename - Mastered: `mv`
 * And also: `ln -s`, `find "where to look" - name "what to look for"`
 * System visualization: comand `tree`


### Security & Permissions - The DevOps Mindset ( Understanding "WHO" can do "What" is core of cloud security.)
 - I've moved beyond just creating files to security.

 * I learned and understood the command: `chmod` and `chmod -r`, i learned the meaning of numbers `7`,`6`,`5`,`4` and `0`.

 * `chmod +x` and  `chmod -x`.

 *  Ownership management: `chown`.

  - Security logic: Learning how to lock down sensitive directories - Like `cybersecurity` and `database` to prevent unauthorized access.

### system Infrastructure & Security
 - In this stage, I evolved from basic file manipulation to professional system administration.
 
 * User and group Management: Learned to create and manage users and groups (`adduser`,`addgroup`) to simulate a real-world enterprise environment.
 
 * Path-based permissions: Mastered how to structure permissions across specific directory paths, ensuring department (finance,HR, backend) has the correct
   access level.

 * Security validation: I didin't just set permissions; I tested them. I used `su - [user]` to switch between accounts and verify that unauthorized users
   were successfully blocked from sensitive data.

 * The "execution" insight: Understood that the +x permission is mandatory not just for scripts, but for a user to enter and navigate through a directory
   using `cd`
 

### Visualizing the enterprise Architecture I created:

```text
  
* sistema_gestao_cloud
.
├── backend
│   ├── C#.c#
│   ├── java.jv
│   └── python3.py
├── cybersecurity
│   ├── analista_SOC
│   ├── devsecops
│   ├── red_Team
│   └── security_engineer
├── database
│   ├── oracle.sql
│   └── PostgreeSQL.sql
├── financeiro
│   ├── accounting
│   ├── financialPlanning_and_Analysis
│   └── treasury
├── frontend
│   ├── css_html
│   ├── javascript.js
│   ├── react.js
│   └── ux_design
├── readme.md
└── RH
    ├── compensation
    ├── learning
    ├── performance_management
    └── recruitment

7 directories, 21 files
