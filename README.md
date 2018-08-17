# Task Manager

This program was created as an evaluation of a online course of React in [edX](https://www.edx.org/). Using the React framework (components, state, JSX), and bootstrap. 

## Input

In the app the user can enter the data thought a simple form, the data is the following:
* Title
* Responsible
* Description
* Priority (low, medium, high)

When the data is complete (or if you want not) the "Add" button can be pressed. 

![Gif of the input of data](https://raw.githubusercontent.com/ediloaz/Tasks-manager/master/settings/add_task.gif)


### Prerequisites

It is necessary to have installed *latex* (including *pdflatex*), *pkg-config* and *evince* in your linux. You can install it with the following commands:
```
sudo apt-get install texlive-full
```
```
sudo apt-get install evince
```
```
sudo apt install pkg-config
```

## Running

First is necessary compile the main file (*main.c*) with the command
```
 gcc -o gladewin main.c -Wall `pkg-config --cflags --libs gtk+-3.0` -export-dynamic -w
```

and then it can be opened
```
./interface
```

## Built With

* [Sublime text](https://www.sublimetext.com/3)
* [NetBeans IDE 8.2](https://netbeans.org/community/releases/82/)
* [Glade](https://glade.gnome.org/)


## Authors

* **Edisson López** - *Main developer* - [ediloaz](https://github.com/ediloaz)
* **Alonso Rivas** - *Complementary developer*
* **Daniel Herrera** - *Tester*

See also the list of [repositories](https://github.com/ediloaz?tab=repositories) who I participated/created.


