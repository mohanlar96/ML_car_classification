# ML Car Classification Project

## Setup for Python:

1. Install Python ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide))

2. Install Python packages

```
pip3 install -r requirements.txt
```

## Setup for ReactJS

1. Install Nodejs ([Setup instructions](https://nodejs.org/en/download/package-manager/))
2. Install NPM ([Setup instructions](https://www.npmjs.com/get-npm))
3. Install dependencies

```bash
cd frontend
npm install --from-lock-json
npm audit fix
```

4. Copy `.env.example` as `.env`.

5. Change API url in `.env`.


## Training the Model

1. Download about 20 images each for 'Ford_Explorer', 'Lexus_RX350', 'Toyota_Matrix' 
2. Create 3 folder ('Ford_Explorer', 'Lexus_RX350', 'Toyota_Matrix') under `training/CarImages/`
3. Run Jupyter Notebook in Browser.

```bash
jupyter notebook
```

4. Open `training/car-classification-train-a-model.ipynb` in Jupyter Notebook.
5. In cell #2, update the path to dataset.
6. Run all the Cells one by one.

## Running the API

### Using FastAPI

1. Open `api_server` folder with PyCharm 
2. Go to main.py file and right click on main method and run 

## Running the Frontend

1. Get inside `api` folder

```bash
cd frontend
```

2. Copy the `.env.example` as `.env` and update `REACT_APP_API_URL` to API URL if needed.
3. Run the frontend

```bash
npm run start
```
