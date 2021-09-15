Backend implementation of secret voldemort game in RESTful API architecture. 
Built based on the FastAPI framework and pony orm for managing the database. 

#run with: python3 -m venv venv && source venv/bin/activate && pip install wheel && pip install -r requirements.txt && python3 app/main.py

#test with: source venv/bin/activate && pytest -v app/server/test.py ; rm app/server/database.sqlite