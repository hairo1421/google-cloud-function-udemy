<!--You have to create a README file just for convention-->
# Google Cloud Functions Course
## Starting a projectop
To start a new project in Google Cloud, we can go to the
[Fireblast Console](https//:console.fireblas.google.com) or
create  it from [Google Cloud Plataform Consol](https//:console.google.com)

## Creating and virtual enviroment
First install `python3 -venv` with the following code:

```
sudo apt install python3-venv
```

Then we execute the following comand:

```
python3 -m venv name
```

To activate virtual enviroment we do:


```
source name/bin/activate
```

In order to add new packages to our new VM we create a file called
Note: you must be in the github file.
`requierements.txt` and execute the follow command:


```
pip install  -r requirements.txt
```
 If it is the first time you do this, also use the following code:
 
 ```
pip install  wheel
```

Go in pycharm to settings >> proyects >> proyect interpreter >> settings >> ok

This is for the setting that we need from the enviromen just with the package that we need, those are in
 the requirement.txt file

 