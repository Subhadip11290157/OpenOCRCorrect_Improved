# OpenOCRCorrect_Improved
Added and tested new features like **bold, superscript and subscripts**.
This is part of an assignment where the following improvements were to be made:-
- a. adding bold/unbold feature for selected texts
- b. adding superscript feature for selected texts
- c. adding subscript feature for selected texts

The improvements were made to this repository: https://github.com/rohitsaluja22/OpenOCRCorrect
Hence this is an improved version of the original OCR software.
- Installation, building and running guides, feature details, issues/challenges and references of 
a text editor software that incorporates similar functionalities have been provided in README section 
of this repository - https://github.com/Subhadip11290157/Textop (which constitutes part 1 of this assignment)

Specific changes-
- The trigger action prototypes for bold, superscript and subscript options were created in mainwindow.h 
- The icons for bold, superscript and subscript were added to the mainToolBar in mainwindow.ui
- The logo for the application was assigned in mainwindow.cpp
- The bold, superscript and subscript functionalities were defined in mainwindow.app 
- (corresponding to the respective prototypes in mainwindow.h)

![image](https://user-images.githubusercontent.com/64594310/154801152-bf36ded5-c2c0-4754-82c4-e1fb6b1c9ec9.png)
![image](https://user-images.githubusercontent.com/64594310/154801214-edfdee54-b4db-4be1-aaf5-ff57789db543.png)
![image](https://user-images.githubusercontent.com/64594310/154801251-ada1ce98-1cd0-4fd1-b108-b6ca6f9bb0b9.png)

All these files :- **mainwindow.h, mainwindow.cpp and mainwindow.ui**; and the icon images can be found in **FrameWorkCode** folder.
