release: flask db upgrade
web: gunicorn test_project.app:create_app\(\) -b 0.0.0.0:$PORT -w 3
