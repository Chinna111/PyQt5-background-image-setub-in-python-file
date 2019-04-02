# PyQt5-background-image-setub-in-python-file
PyQT5 background image not showing properly

after, long duraation i got a solution for the Pyqt5 background imgae does not showing with python file.
During form creation at the pyqt you need to give ".qrc" file for making the image url. If the ".qrc" file does not supported after convert to .py file
If the solution is you require to change ".qrc" to ".py" file, commend given below.

>Pyrcc5 source.qrc -o source1.py
