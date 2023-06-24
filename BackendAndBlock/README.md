
### Install all requirements for the project 
```
pip install -r req.txt
```


### install ganache-cli using npm 
**make sure that npm installed** 
``` 
npm install -g ganache-cli
```
### Install enviroment 
```
pip install virtualenv
```
### make another inviroment
**you can skip this step and use the exsiting env folder** 
```
virtualenv venv
```
### Activate the enviroment 

**in windows**
``` 
venv\Scripts\activate.bat
```
**in linux**
```
source env/Scripts/activate
```
### i have deprecated packages:  
**pywin32==304** as i am using WSL which is not nessery for this kind of system, still don't know if it is going to affect the software or not, but we see.
**NOTE** you may need to add **pywin32==304** into req.txt if you uses Windows OS


# DATABASE SCHEMA 

**Users** 
| Column | Type |
|--------|------|
| Id     | STRING /UUID |
| IdCode     | STRING /UUID |
| First/Last Name | STRING |
| Passwords | STRING | 
| E-mail | STRING |
| contract_address | STRING |
| UserName | STRING |
| user_role | STRING | 




 