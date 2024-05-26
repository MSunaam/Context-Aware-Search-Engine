# Context Aware Search Engine

## Getting Started

### Running the Flask Server

1. Change directory to `Flask` and install the requirements.txt file using `pip install -r requirements.txt`
2. Make sure to downlaod the BERT Model using git:

```
git lfs install
git clone https://huggingface.co/google-bert/bert-base-uncased
```

3. Place the BERT Model in the root directory of the project.
4. Run `flask --app server run --debug` to start the server in debug mode.

### Running the Front-End

1. Change directory to `fornt-end`.
2. Make sure you have a compatible version of node installed.
3. Run `npm i` to install required packages.
4. Run `npm start` to run the front-end on `localhost:3000`.

### Running the Express Server

1. Change directory to `server`.
2. Make sure you have a compatible version of NodeJs installed.
3. Run `npm i` to install the required packages.
4. Run `node index.js` to start the server.
5. Server will start at `localhost:50001`.
