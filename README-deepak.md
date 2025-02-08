python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install Flask

pip freeze > requirements.txt
pip install -r requirements.txt

To Run: python app.py


/your-project-directory
    /config
        config.yaml
    /templates
        index.html
    app.py
    .gitignore

1. i want to understand airflow source code. I am new. From where i should start
### 5. **Start with the `airflow/__init__.py` File**
The `airflow/__init__.py` file will give you insight into the main entry points for the Airflow package. You'll see how Airflow is initialized and how different modules are imported and structured.