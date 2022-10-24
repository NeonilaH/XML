# XML

1. Create an external repository called XML.
- `Create a new repository`
2. Clone the XML repository to the local machine.
- `git clone https://github.com/NeonilaH/XML.git`
3. Inside the local XML create the “new.xml” file.
- `touch new.xml`
4. Add file under git.
- `git add new.xml`
5. Commit the file.
- `git commit -m "add xml file"`
6. Submit the file to an external GitHub repository.
- `git push`
7. Edit the content of the “new.xml” file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in XML format.
- `nano new.xml`
```xml
<?xml version="1.0" encoding="utf-8"?>
<general>
<name>
<first>Neonila</first>
<last>Hlovatska</last>
</name>
<age>34</age>
<number_of_pets>1</number_of_pets>
<salary>1000</salary>
</general>
```
8. Push changes to an external repository.
- `git commit -m "add changes to xml file"` ---> `git push`
9. Create preferences.xml file.
- `touch preferences.xml`
10. In the preferences.xml file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in XML format.
- `nano preferences.xml`
```xml
<?xml version="1.0" encoding="utf-8"?>
<general>
<favourite_film>None</favourite_film>
<favourite_tv_series>None</favourite_tv_series>
<favourite_food>Shrimps</favourite_food>
<country_I_wanna_see>Japan</country_I_wanna_see>
<favorite_season>summer</favorite_season>
</general>
```
11. Create a file sklls.xml add information about the skills that will be studied on the course in XML format.
- `nano skills.xml`
```xml
<?xml version="1.0" encoding="UTF-8"?>
<skills>
        <skill id="1" type="Basic theory. SDLC, STLC."></skill>
        <skill id="2" type="What is a client-server architecture."></skill>
        <skill id="3" type="HTTP request methods to the server and response codes."></skill>
        <skill id="4" type="Structures of HTTP requests and responses."></skill>
        <skill id="5" type="What is JSON, XML. Their structure."></skill>
        <skill id="6" type="API testing via Postman (JS, API autotests)."></skill>
        <skill id="7" type="Removing and reading logs from an external server."></skill>
        <skill id="8" type="Dev Tools of web browsers (Google Chrome)."></skill>
        <skill id="9" type="VPN (How it works, why you need it, how to use it, tool options)"></skill>
        <skill id="10" type="Mobile testing."></skill>
        <skill id="11" type="Feature iOS, Android, guidelines."></skill>
        <skill id="12" type="Building Android applications on Android Studio."></skill>
        <skill id="13" type="ADB (android device management)."></skill>
        <skill id="14" type="Command line (terminal) Linux (copying, creating, viewing, moving files on servers without a graphical interface)"></skill>
        <skill id="15" type="Basics of bash scripting, automation of routine tasks on the server."></skill>
        <skill id="16" type="Access to remote servers."></skill>
        <skill id="17" type="SQL basics (Create, Delete, Drop, Insert Into, Select, Where, Join)."></skill>
        <skill id="18" type="Database Postgres (installation, configuration and use)."></skill>
        <skill id="19" type="Scrum development methodology."></skill>
    </skills>
 ```
12. Make a commit in one line.
- `git add skills.xml preferences.xml | git commit -am "add and commit 2 files at once"`
13. Send 2 files at once to an external repository.
- `git push`
14. On the web interface, create the bug_report.xml file.
- `nano bug_report.xml`
```xml
<?xml version="1.0" encoding="UTF-8"?>
<bug_report>
<Bug_id>111</Bug_id>
<Title>Missing white lines on widgets</Title>
<Severity><type>Major</type></Severity>
<Priority><type>Medium</type></Priority>
<Environment>Xiaomi Redmi 8A, MIUI Global 12.5.2, 10 QKQ1.191014.001</Environment>
<Precondition>Desktop grid 5x5, font size Medium, zoom Medium</Precondition>
<STR>
<step id="1" type="Add 6 widgets"></step>
<step id="2" type="Arrange widgets as in the attachment"></step>
</STR>
<AR>The widget in the center has a missing white bottom line</AR>
<ER>All widgets should have four white lines</ER>
<Attachments>https://bit.ly/3NOFgrJ</Attachments>
</bug_report>
```
15. Make Commit changes (save) changes on the web interface.
- `Add file`
---> `Create new file`
---> `Commit new file`
16. Modify the bug_report.xml file on the web interface, add a bug report in XML format.
- `Open file`
---> Go to the pencil button `Edit this file`
17. Make Commit changes (save changes) on the web interface.
- `Commit changes`
18. Synchronize external and local XML repository.
- `git fetch`
---> `git pull`
