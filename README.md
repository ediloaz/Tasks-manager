# Task Manager

This program was created as an evaluation of a online course of React in [edX](https://www.edx.org/). Using the React framework (components, state, JSX), and bootstrap. 

## Input

In the app the user can enter the data thought a simple form, the data is the following:
* Title
* Responsible
* Description
* Priority (low, medium, high)

When the data is complete (or if you want not) the "Add" button can be pressed. 

![Screenshot of the input of data](https://raw.githubusercontent.com/ediloaz/Tasks-manager/master/settings/screenshot-interface-empty.gif)
Screenshot of the interface without data

![Screenshot of the interface with example data](https://raw.githubusercontent.com/ediloaz/Simplex-Algorithm/master/settings/screenshot-interface-example.png)
Screenshot of the interface with example data

## Output

In a latex presentation is showed the result of this. The information is the following:
* Cover (of the University)
* Short explain about the Algorithm Simplex
* Problem with math representation
* Initial table
* Intermediate tables
* Final table
* Solution
* Special cases

A .tex file is created and convert to pdf with *pdflatex command*  and is opened with *evince command*. All these files are saved in **Salida** folder.

![Screenshot of the intermediate tables in the Output](https://raw.githubusercontent.com/ediloaz/Simplex-Algorithm/master/settings/screenshot-output.png)
Screenshot of the intermediate tables in the Output

Also, detected and explained if the problem had the following special cases:
1. Not Limited Problem
2. Not Feasible Problem
3. Degenerated Problem
4. Problem with multiple solutions


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


