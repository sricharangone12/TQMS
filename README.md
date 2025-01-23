# TQMS
1. Download and install the following on the server:

        Node.js from https://nodejs.org/en/download
        Python from https://www.python.org/downloads/
        pip
    
2. How to build and start Server:

    Onetime setup:
    
        mkdir tqms/server
        cd tqms/server
        python3 -m venv venv
        source venv/bin activate
        pip install Flask
        pip install flask_pymongo
        pip install werkzeug.security
        pip install flask_jwt_extended
        pip install flask_cors

    Start Server:

        tqms/server
        Copy https://github.com/Rohith-India/CS4443/blob/main/Team-37/TQMS/server/app.py to tqms/server folder
        export FLASK_APP=app.py
        flask run

3. How to build and start Client:

    Onetime setup:

        cd tqms/server
        npx create-react-app client
        cd client
        npm install react-router-dom
        npm install reactstrap

    Start Client:
    
        cd tqms/client
        npm start



4. The following default user is created with the above setup:

        user name        password           role
        =========        ========           =====
        admin            a                  admin

5. How to access UI:

    http://localhost:3000
