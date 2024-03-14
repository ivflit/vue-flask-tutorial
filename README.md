## frontend

### Project setup
```
npm install
```

#### Compiles and hot-reloads for development
```
npm run serve
```

#### Compiles and minifies for production
```
npm run build
```

#### Lints and fixes files
```
npm run lint
```

#### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## backend

### virtual environment
We used pipenv for our virtual environment since it allows for easy management of virtual environments. It assigns a special code to each virtual environment so it saves you the hastle of naming.
```
python -m pip install pipenv
pipenv --python 3.9
pipenv shell
pipenv install -r requirements.txt
```
### project setup

```
cd backend
python3 main.py
```
