# What is this tutorial?

I wanted to get familiar with vue and a python backend so I searched for tutorials that had both. I found this [tutorial](https://www.youtube.com/watch?v=lenV5aVOMp8&t=1850s). It really helped consolidate my understanding on the connection between a frontend and a backend whilst helping me learn and understand Vue.js.

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
