<h1 align='center'>pnRent</a></h1>
<p align='center'><b><a href='https://documentation.esx-framework.org/legacy/installation'>Documentation</a></b></p>

<p align='center'><b>Simple rent menu with UI inspired by Nopixel 4.0</b></p>

<hr>

<h3 align='center'>Dependency</h3>
<p align='center'><a href="https://github.com/overextended/ox_lib/releases"> ox_lib </a></p>

<hr>

<h3 align='center'>Installation Process</h3>

1. Download the pnRent.zip file from <a href="https://github.com/PandaRomania/pnRent/releases/latest">here</a>
2. Unzip the file
3. Add the pnRent file in rou `resources` folder
4. Go to server.cfg and add the piece of code below
```cfg
setr ox:locale en
ensure ox_lib
ensure pnRent
```
5. Go into your database
6. Add the SQL part of code that is for your Framework ( found in db.sql )
7. Configure the script to your linking in the config.lua

<h1 align='center'>Problems & Errors</h1>

In case of any problems, you are open to create a post here