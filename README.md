## Sample Flask Project Using Postgres DB | ![Visitor Count](https://visitor-badge.glitch.me/badge?page_id=0xStryK3R.Sample-Flask-Postgres-Project)

1. Rename _`sample_config.py`_ to _`config.py`_, and update with your own _`SQLALCHEMY_DATABASE_URI`_ and desired _`SECRET_KEY`_.

2. Run below command inside project directory to setup environment
      ```console
      python -m venv venv
      ```

3. Activate enviroment with below command (for Windows):
      ```console
      venv\Scripts\activate
      ```

4. Run below command next to install required modules plus dependencies defined in `requirements.txt`
      ```console
      pip install -r requirements.txt
      ```

5. Run below command to start the app:
      ```python
      python app.py
      ```

6. All Done!! [Click Here](http://localhost:5000/) to interact with your app:

> _**Assumptions**: Python and Postgres DB have been setup and is running prior to starting with this project._

> _**References**: For Complete details, please refer [`Sending data from a Flask app to PostgreSQL database`](https://towardsdatascience.com/sending-data-from-a-flask-app-to-postgresql-database-889304964bf2) for source article for this Repo._
