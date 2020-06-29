# Django Template



## Getting Started

To start, you must have the following requirements

* [Python](https://www.python.org/) (latest version is recommended)
* IDE ([VS Code](https://code.visualstudio.com/))
* [Django](https://www.djangoproject.com/) (to install see [How to Use section](#use))



<a name='use'></a>

## How to Set Up

To start, install the required packages using the requirement.txt
This step will require the [virtual env module](https://pypi.org/project/virtualenv/) (this might require admin access) and although this is completely optional, it is strongly recommended

To install virtual env do a pip install exactly like the following:

```python
pip install virtualenv
```

Next you want to activate the virtual env so in Windows enter:

```powershell
.\env\Scripts\activate
```

Otherwise, if you are on Mac or Linux, 

```shell
source env/Scripts/activate
```



Next install the requirements modules

```powershell
pip install -r requirements.txt
```

 Right now, this is just Django, so you could have done

```shell
pip install Django
```



## How to Use

Once you are in a virtual environment, you can go into template folder with the following command:

```
cd .\template\
```

Next to start the Django project

```shell
py .\manage.py runserver
```

Now you can go to http://127.0.0.1:8000/ and see the Django default homepage



If you want to rename the Django project, use the rename command

```shell
python manage.py rename #someName 
```



## How it was Made

After virtual env and Django where installed, I used the startproject command

```shell
django-admin startproject template
```

(+ some code to help rename)



## License

This code is under MIT licence.