## Sample Flask Project Using Postgres DB

1. Rename `sample_config.py` to `config.py`, and update with your own `SQLALCHEMY_DATABASE_URI` and desired `SECRET_KEY`.

2. Run below command inside project directory to setup environment
```console
python -m venv venv
```

3. Activate enviroment with below command (for Windows):
```console
venv\Scripts\activate
```

3. Run below command next to install required modules plus dependencies defined in `requirements.txt`
```console
pip install -r requirements.txt
```

4. Run below command to start the app:
```python
python app.py
```

5. All Done!! [Click Here](http://localhost:5000/) to interact with your app:
