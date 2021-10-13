<img 
     src="https://img.shields.io/badge/Made%20by%20Mohammed%20Zeeshan-4a10fb?style=for-the-badge&logo=zeeshan&logoColor=white"/> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/> <img src="https://img.shields.io/badge/Odoo-6b4762?style=for-the-badge&logo=odoo&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Pycharm-239120?style=for-the-badge&logo=pycharm&logoColor=white"/>

# Usefull_Commands 
All the commands, tips and tricks that will be usefull for developers, designers, non developers on linux, pycharm, windows etc

# Ubuntu Tips, Tricks and Commands
1. `sudo dpkg -i package.deb` (install deb file)
2. `cd -` (last working directory)
3. `pkill filename` (kill specific file with filename)
4. `ps ax` (find the process number for specific file to kill)
5. `pwd` (print full path of current working directory)
6. `cp filename directorypath` (to copy file to specific location)
7. `mv filename directorypath` (to move file to specific location)
8. `rmdir fielname` (remove empty directory)
9. `rm -r fielname` (remove directory with its content)
10. `mkdir` (create directory)
11. `history` (will display all the previously used directory)
12. `df` (display disk space usage)
13. `du` (directory usage)
14. `free` (display amount of free space)
15. `man command_name` (to get detail information about the command)
16. `passwd user` (to change password of the user)
17. `ctrl + u` (to delete whole line from terminal)
18. `ctrl + a` or `ctrl + e` (to move start and end of command in terminal)
19. `ll` (to show content of directory with access writes)


# SQL Commands general, for odoo specific also.
Note: Prefer SQL whene dealing with large data since sql is faster than ORM, dont use SQL everywhere since sql ignore access rights and more
1. `self.env.cr.execute(“””SELECT * FROM res_partner”””)` (This command will select all the records from partner, we can execute any sql query using cr.execute)
2. `self.env.cr.fetchall()` (Fetchall will give you matching records in the form of a list of tuples.)
3. `self.env.cr.fetchone()` (same as fetchall but show only one record)
4. `self.env.cr.dictfetchone()` (same as fetchone but It will return only a single record in the form of dictionary)
5. `self.env.cr.execute(“INSERT INTO res_partner(name) VALUES(‘ABC’)”)` (to Create a Record)
6. `self.env.cr.execute("""UPDATE res_partner SET mobile='123' WHERE id=5""")` (to Modify a Record)
7. `self.env.cr.execute("""DELETE FROM res_partner WHERE id=5""")` (to Delete a Record)
8. `update res_users set password='123' where login='admin';` (Change password if password forgot)


<!-- Add Any Tricks you know -->

