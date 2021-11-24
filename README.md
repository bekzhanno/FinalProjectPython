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
![alt text](https://user-images.githubusercontent.com/75968886/143144729-5723028d-ce0c-415f-8c6c-f76f4372e747.png)
![alt text](https://user-images.githubusercontent.com/75968886/143144803-9560c465-4c90-4f48-a83f-421258c5f20d.png)

```

## License
[MIT](https://choosealicense.com/licenses/mit/)
