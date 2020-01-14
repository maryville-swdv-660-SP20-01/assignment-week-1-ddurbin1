# CSV Compiler
This program allows for the ability to take multiple CSV files and combined them into one CSV.
## Example usage
```
$ Enter file directory: C:/Users/Gaming Rig/Desktop/CSVFiles
$ All files have been combined...
```
### Install
```
$ pipenv install
```
### Run
```
$ pipenv run python CSVCompiler.py
```
or
```
$ pipenv shell
$ python CSVCompiler.py
```
### Compile with pyinstaller
```
$ pyinstaller -F -y -n {{FileName}} CSVCompiler.py
```
