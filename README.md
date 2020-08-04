# Deepminer

## A Deep Web Datamining and Search Tool

The automation of the process of crawling through the deep web and searching for key terms or domain names would be a valuable tool for any tester, researcher, or IT security team. This framework would need to be simple to use and able to continuously run. Additionally, results would need to meaningful and easy for the user to understand.

To solve this issue, I’ve developed a deep web crawling tool called Deepminer, that allows easy searching to help users identify any results. Deepminer pulls Onion sites from well-known resources and searches using any extracted HTML. Deepminer runs continuously and indefinitely to ensure that the database is updated. Site names, directories, HTML, and connected sites are saved to a SQLite database file where users can analyze the results.

### Implementation

Deepminer is written using Python 3 and tested in Ubuntu 20.04. Searches are conducted using [SQLite FTS5 Extension](https://www.sqlite.org/fts5.html), for both full text and regex searches. For ease of searching, users can use [SQLite DB Browser](https://github.com/sqlitebrowser/sqlitebrowser) for a graphical interface.

### Requirements

git

[Python 3](https://www.python.org/downloads/release/python-383/)

[Pip3](https://pip.pypa.io/en/stable/installing/)

[Tor](https://packages.ubuntu.com/focal/tor)

Screen

[Pysocks](https://pypi.org/project/PySocks/)

### Installation

On a fresh install of Ubuntu 20.04 run the following commands

1. ```
   sudo apt install git
   ```

2. ```
   sudo apt install python3-pip
   ```

3. ```
   pip3 install pysocks
   ```

4. ```
   sudo apt install tor
   ```

5. ```
   sudo apt install screen
   ```

6. ```
   git clone https://github.com/Conso1eCowb0y/Deepminer
   ```

7. ```
   cd Deepminer
   ```

8. ```
   sudo python3 deepminer.py
   ```

9. To install SQLite DB Browser, run the following command:

   ```
   sudo apt install sqlitebrowser
   ```

### TODO

- Multi-threading
- [Kivy](https://kivy.org/) based search GUI





