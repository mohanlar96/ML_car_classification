# ML Car Classification Project

## Setup for Python:

1. Install Python ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide))

2.Clone the Project and  Install pip3 

```
python3 api_server/get-pip.py
```

3.Install Python Jupyter (MAC)

```
pip3 install jupyter
```

3. Install Required Python packages

```
cd ML_car_classification 
pip3 install -r training/required_python_pacakges.txt
pip3 install -r api_server/packages.txt

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

1. Download about 20 images each for `Ford_Explorer`, `Lexus_RX350` and `Toyota_Matrix` 
2. Create 3 folder `Ford_Explorer`, `Lexus_RX350` and  `Toyota_Matrix' under `training/CarImages/`
3. Run Jupyter Notebook in Browser.

```bash
jupyter notebook
```

4. Open `training/car-classification-train-a-model.ipynb` in Jupyter Notebook.
6. Run all the Cells one by one.

## Running the API

1. Open `api_server` folder with PyCharm 
2. Go to main.py file and right click on main method and run 

## Running the Frontend

1. Get inside `frontend` folder

```bash
cd frontend
```

2. Copy the `.env.example` as `.env` and update `REACT_APP_API_URL` to API URL if needed.
3. Run the frontend

```bash
npm run start
```
