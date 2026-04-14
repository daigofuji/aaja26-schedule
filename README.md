# AAJA26 convention schedule web viewer

Web iframe embed to go on the convention page, showing convention session data from official GUIDEBOOK app. Also serves as a archive of session data for future reference.

## Usage

Two parts: Pythnon script to fetch and process data, and a VITE powered web page to display it.


# Python setup. 

I use pyenv to manage my python environment. `pyenv` and `virtualenv` via `brew` v3.12 
```bash
brew update
brew install python pyenv pyenv-virtualenv
pyenv install 3.13
pyenv virtualenv 3.13 AAJA
pyenv activate AAJA
pip install -r requirements.txt
```

# Web setup

Installed vite using
```bash
npx create-vite@latest . --template react-ts
npm install
```

Then run the web server with
```bash
npm start
```

