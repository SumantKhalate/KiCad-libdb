# KiCad-libdb
 This repo will walk you through setting up a KiCad V7 library database using SQLite.

1. Download the KiCad configuration file *libdb.kicad_dbl* and the database file *libdb.sqlite* and place it in a suitable folder. [KiCad-libdb](https://github.com/SumantKhalate/KiCad-libdb/archive/refs/heads/main.zip)
2. Verify if *SQLite3 ODBC Driver* is installed by running *ODBC Data Source Administrator (64-bit)*, if not then install *sqliteodbc.exe* from [Link](http://www.ch-werner.de/sqliteodbc/)

![Alt text](/README/ODBC_3.jpg)

3. Again run *ODBC Data Source Administrator (64-bit)* and under **User DNS** add a new entry called *KiCad_libdb* and select the recently downloaded database file

![Alt text](/README/ODBC_1.jpg) ![Alt text](/README/ODBC_2.jpg)

4. Now in KiCad, open the *Manage Symbol Library* and add the folder containing the KiCad configuration file

![Alt text](/README/KiCad_1.jpg) ![Alt text](/README/KiCad_2.jpg)

5. Once you open any schematic you will be able to see the library components in the *Choose Component* window

![Alt text](/README/KiCad_3.jpg)

6. You can edit the content of the database using your preferred SQL database manager or download one. I'm using **SQLiteStudio**

![Alt text](/README/SQLiteStudio_1.jpg)
![Alt text](/README/SQLiteStudio_2.jpg)
![Alt text](/README/SQLiteStudio_3.jpg)
