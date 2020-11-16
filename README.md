Software versions for startup:
josh at starter_react_and_fastapi 🌲 node --version
v14.15.0
josh at starter_react_and_fastapi 🌲 python3 --version
Python 3.8.4
josh at starter_react_and_fastapi 🌲 pip3 --version
pip 20.1.1
josh at starter_react_and_fastapi 🌲 npm --version
6.14.8

Create directory to hold backend and frontend
mkdir starter_react_and_fastapi
cd starter_react_and_fastapi

Frontend - https://create-react-app.dev/docs/adding-typescript/

# Create frontend with create-react-app
Choose one of the following
# React with javascript
	npx create-react-app frontend
# React with TypeScript
	npx create-react-app frontend —template typescript
cd frontend;

Open directory with Code editor.
# In editor run 
npm install
npm run start
# open localhost: 3000

Backend - https://fastapi.tiangolo.com/
mkdir backend
cd backend
python3 -m venv env
source env/bin/activate
pip install fastapi uvicorn newsapi-python
touch main.py
charm .
paste fastapi with cors into main.py - https://fastapi.tiangolo.com/tutorial/cors/?h=+cors
uvicorn main:app —-reload


/Users/joshjohansen/senofjohan/kata/react_and_fastapi_with_cors/
