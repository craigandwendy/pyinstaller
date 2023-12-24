# Pyinstaller

## Installation
From terminal run this command:
```
pip install pyinstaller
```
or
```
pip3 install pyinstaller
```

## Use
In the terminal navigate to the folder with your Python project and run this command:
```
pyinstaller my_app.py  
```
Now you can exit the terminal and go to the folder where you Python project was saved. You will find a folder called dist, double-click the file and now you're running your own real app.

If you want to get rid of the prompt/terminal showing up (-w) and even have an app icon, run this command:
```
pyinstaller -w  --onefile --icon=my_app.icns  my_app.py 
```
Keep in mind store your icon file in the same folder as your Python project and make sure that your icon is a .icns file.
You can now exit the terminal and go to dist and double-click the file inside. This time you app will start without showing a prompt/terminal.


## Final

## Useful Links
Official docs https://pyinstaller.org/en/stable/

YouTube tutorial https://www.youtube.com/watch?v=QWqxRchawZY

Free icons https://icon-icons.com
