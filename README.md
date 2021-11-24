# Final_project_python
Final project
## Title:
Final project.Summary from CoinGecko
## Installation

PyPI
```bash 
pip install flask
pip install flask_SQLAlchemy
pip install request
pip install BeautifulSoup
pip install Transformers
pip install jwt
```
or from source
```bash
flask - https://flask.palletsprojects.com/en/2.0.x/
flask_SQLAlchemy - https://flask-sqlalchemy.palletsprojects.com/en/2.x/
request - https://pypi.org/project/requests/
BeautifulSoup - https://www.crummy.com/software/BeautifulSoup/bs4/doc/
Transformers - https://pypi.org/project/transformers/
jwt - https://pyjwt.readthedocs.io/en/stable/
```
## Usage
```bash
app.config['SQLALCHEMY_TRACK_MODIFICATIONS'] = False
app.config.update(dict(
    SECRET_KEY="powerful secretkey",
    WTF_CSRF_SECRET_KEY="a csrf secret key"))
app.config['SQLALCHEMY_DATABASE_URI'] = 'sqlite:///site.db'
```
## Examples
Outputs will be like these:
```Firstly, we create account and sing in with this account. After, we can see search page. Here, for example we searched bitcoin.
![alt text](https://user-images.githubusercontent.com/75968886/143173900-9450cbe1-0571-4465-a097-d690186ea4b7.png)

![alt text](https://user-images.githubusercontent.com/75968886/143173977-5229050c-d381-49cf-86ae-1bc1914ec539.png)


```

## License
[MIT](https://choosealicense.com/licenses/mit/)
