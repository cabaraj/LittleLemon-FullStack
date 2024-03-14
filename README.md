# LittleLemon-FullStack

### Cloning the repository:
1. Clone the repository (via HTTPS)
```bash
git clone https://github.com/cabaraj/LittleLemon-FullStack.git
```
2. Create/activate a virtual environment
```python
pipenv shell
```
3. Install dependencies
```python
pipenv install
```
4. Change to the project's directory
```python
cd littlelemon
```
5. Apply migrations to create the models into your database
```python
python manage.py makemigrations
python manage.py migrate
```
NOTE: migrations will only take effect if an item has been modified, yet it is good practice to apply migrations at all times before running the server.
6. Run the server
```python
python manage.py runserver
```
7. Go to the local-host address in your browser with port 8000:
localhost:8000 OR
http://127.0.0.1:8000/
8. When done, exit the virtual environment
```python
exit
```

If want to create an admin user:
```python
python manage.py createsuperuser
```
use the '/admin' endpoint to access to the admin portal
