<h1 align="center" id="title"></h1>

<h2 id="description">Description</h2>

<p>
 
</p>

## 🔧 Github Commands :-

`Step 1` : SSH Configuration.

```
ssh-keygen -t ed25519 -C "ex@gmail.com"
```

```
cat ~/.ssh/id_ed25519.pub
```

```
git config --global user.email "ex@gmail.com"
```

```
git config --global user.name "ex"
```

`Step 2` : Starting Git.

```
git init
```

```
git add .
```

```
git commit -m "first commit"
```

```
git branch -M main
```

```
git remote add origin
```

```
git push -u origin main
```

`Step 3` : Clone.

```
git clone
```

`Step 4` : Pull.

```
git pull -r origin main
```

```
Accept Both Changes
```

```
git rebase --continue
```

```
git config --global pull.rebase true
```

`Step 5` : Tag.

```
git checkout main
```

```
git tag
```

```
git tag -a v1.0 -m "Version 1.0"
```

```
git push origin v1.0
```

---

## 🛠️ Installation Steps :-

<h3 align="center"> Ubuntu </h3>

`Step 1` : Install and activate VirtualEnvironment.

```
pip install virtualenv
```

```
virtualenv venv
```

```
source venv/bin/activate
```

`Step 2` : Install Packages.

```
pip install django
```

```
python.exe -m pip install --upgrade pip
```

```
pip install djangorestframework
```

```
pip install django-cors-headers
```

```

```

`Step 3` : Install requiremental Packages.

```
pip freeze > requirements.txt
```

```
pip install -r requirements.txt
```

`Step 4` : Create Project.

```
django-admin startproject homeverse
```

```
cd homeverse
```

`Step 5` : Create Apps.

```
python3 manage.py startapp api
```

`Step 6` : Create Database.

```
su - postgres
```

```
psql
```

```
CREATE USER django_proj WITH PASSWORD 'django@@1';
```

```
create database homeverse;
```

```
\c homeverse;
```

```
GRANT ALL PRIVILEGES ON DATABASE homeverse TO django_proj;
```

```
GRANT ALL PRIVILEGES ON ALL TABLES IN SCHEMA public TO django_proj;
```

```
GRANT ALL PRIVILEGES ON SCHEMA public TO django_proj;
```

```
GRANT ALL PRIVILEGES ON ALL SEQUENCES IN SCHEMA public TO django_proj;
```

`Step 7` : Create Migrate.

```
python3 manage.py makemigrations
```

```
python3 manage.py migrate
```

`Step 8` : Create Superuser.

```
python manage.py createsuperuser
```

```
_proj@gmail.com
```

```
_proj
```

```
@@1
```

`Step 9` : Run Server.

```
python3 manage.py runserver
```

`Step 10` : Info Admin.

```
homeverse_proj@gmail.com
```

```
homeverse@@1
```

`Step 11` : Info Server.

```

```

<h3 align="center"> Windows </h3>

`Step 1` : Install and activate VirtualEnvironment.

```
pip install virtualenv
```

```
virtualenv wvenv
```

```
wvenv\Scripts\activate
```

`Step 2` : Install Packages.

```
pip install django
```

```
python.exe -m pip install --upgrade pip
```

```
pip install djangorestframework
```

```
pip install django-cors-headers
```

```

```

`Step 3` : Install requiremental Packages.

```
pip freeze > wrequirements.txt
```

```
pip install -r wrequirements.txt
```

`Step 4` : Create Project.

```
django-admin startproject homeverse
```

```
cd homeverse
```

`Step 5` : Create Apps.

```
python manage.py startapp api
```

`Step 6` : Create Database.

```
su - postgres
```

```
psql
```

```
CREATE USER django_proj WITH PASSWORD 'django@@1';
```

```
create database homeverse;
```

```
\c homeverse
```

```
GRANT ALL PRIVILEGES ON DATABASE homeverse TO django_proj;
```

```
GRANT ALL PRIVILEGES ON ALL TABLES IN SCHEMA public TO django_proj;
```

```
GRANT ALL PRIVILEGES ON SCHEMA public TO django_proj;
```

```
GRANT ALL PRIVILEGES ON ALL SEQUENCES IN SCHEMA public TO django_proj;
```

`Step 7` : Create Migrate.

```
python manage.py makemigrations
```

```
python manage.py migrate
```

`Step 7` : Create Superuser.

```
python manage.py createsuperuser
```

```
homeverse_proj@gmail.com
```

```
homeverse_proj
```

```
homeverse@@1
```

`Step 9` : Run Server.

```
python manage.py runserver
```

`Step 10` : Info Admin.

```
homeverse_proj@gmail.com
```

```
homeverse@@1
```

`Step 11` : Info Server.

```
m9ee9m+4@gmail.com
```

---

## 🧐 Features :

<ul>
<li>
    <b>User Authentication:</b> Secure registration, login, and password recovery.
</li>
<li>
    <b>Project Creation:</b>
</li>
<li>
    <b>Project Management:</b> Features for viewing, commenting, rating, and reporting projects.
</li>
<li>
    <b>Homepage:</b> Displays featured, latest, and categorized projects.
</li>
<li>
    <b>Search:</b> Allows users to find projects by title or tag.
</li>
<li>
    <b>Additional Features:</b> user profiles, and notifications.
</li>
</ul>

---

## 💻 Built with :-

Technologies used in the project:

-   Django Framework
-   Postgres Database

---

<p align="left"><img src="https://profile-counter.glitch.me/iti-final-project-babackend/count.svg" alt="desphixs" /></p>

---

<h1>Under The Supervision of:</h1>
<table>
    <tr>
        <td>
            <img src="https://avatars.githubusercontent.com/u/84921583?v=4"></img>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/Ma7moudHelmi">Mahmoud Elmahmoudy</a>
        </td>
    </tr>
</table>

---

## Contributors

<table>
    <tr>
        <td>
            <img src="https://avatars.githubusercontent.com/u/91129862?v=4"></img>
        </td>
        <td>
            <img src="https://avatars.githubusercontent.com/u/120313545?v=4"></img>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/Ma7en">Mazen Saad</a>
        </td>
        <td>
            <a href="https://github.com/rehabezzat">Rehab Ezzat</a>
        </td>
    </tr>
    <tr>
        <td>
            <img src="https://avatars.githubusercontent.com/u/93333314?v=4"></img>
        </td>
        <td>
            <img src="https://avatars.githubusercontent.com/u/174034623?v=4"></img>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/Shrouk2000">Shrouk Ahmed</a>
        </td>
        <td>
            <a href="https://github.com/nada-mohamed-ops">Nada Mohamed</a>
        </td>
    </tr>
</table>
```