# Swarm-assisted conversational vendor data aggregator

## Demo
[Watch the demo video](https://youtu.be/TRBFcSanQ_c)

[Read about our experiments](https://github.com/linomp/swarmagan-junction2023/tree/main/experiments)

## Meet the team

**Steven Esposito🇮🇹🤌** Head of Data, AI and media.    
**Erald Keshi🇦🇱🦅** UI/UX Revolutionary Disrupter.    
**Martin Põhjakivi🇪🇪🍄** Estonian Food and Beverage Import/Export Domain Expert.    
**Lino Mediavilla Ponce🇪🇨🍌** Head of Indoor Logistics.    
**Sergi Martinez Rodriguez🇪🇸😴** Chairman of the Board.    

## Run the backend

1. Crate an .env file based on the .env.template file
2. Add open AI key to the .env file
3. On Linux run:
    ```bash
    source venv/bin/activate
    pip3 install -r requirements.txt
    python3 api/main.py
    ```

Server will run on port 8000, visit http://localhost:8000/docs

## Run the frontend

 ```bash
 cd client
 npm install
 npm run dev
 ```
