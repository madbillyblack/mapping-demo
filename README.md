# Mapping Demo

Browser-based version of
[PlanetMap3D](https://github.com/madbillyblack/Space_Engineers_Scripts/tree/master/PlanetMap_3D).


## Developer Setup

Requires:

* Python 3.9
* Windows 10

From within the `mapping-demo` project folder:

1. Setup a virtual env:

```
python -m venv .venv
.venv\Scripts\activate.bat
```

2. Install the requirements:

```
pip install -r requirements.txt
```

3. Start the local development server:

```
python backend\manage.py runserver
```

You can visit [localhost:8000](http://localhost:8000) to see the project
running.
