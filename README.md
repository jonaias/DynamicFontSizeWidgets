# DynamicFontSizeWidgets
Dynamic font size QPushButton and QLabel

Implemented dynamic font size according to defined widget size and accounts for QLabel new lines. Tested with Qt5/Android, Qt5/Linux and Qt4. Tested with QSizePolicy::MinimumExpanding and QSizePolicy::Fixed.


# Components

## DynamicFontSizeLabel
 - Added setTextColor (Altought it overwrites stylesheets).
 - Added click signal
 
## DynamicFontSizePushButton
 - Added setTextColor (Altought it overwrites stylesheets).
 
# How to use

Use QtDesigner guide found in http://doc.qt.io/qt-5/designer-using-custom-widgets.html


# Example

Open example/ project to see in action. A box frame is set in example to make it clear.


# TODO

 - Add/Improve examples
 - Self tests?
 - Improve size fitting algorithm
 - Add other components
 
 # Inspiration

Main inspiration: http://www.qtforum.org/article/32092/dynamic-font-size-in-qlabel-based-on-text-length.html

Other useful link
 - https://stackoverflow.com/questions/42652738/how-to-automatically-increase-decrease-text-size-in-label-in-qt/42690033#42690033

 - https://stackoverflow.com/questions/40861305/dynamically-change-font-size-of-qlabel-to-fit-available-space

 - https://stackoverflow.com/questions/36331651/dynamic-text-size-qlabel
 
 # History
 
 DynamicFontSizeLabel initial version was developed inside Exacta Balanças ( @exactabal ) which gently opened code as retribution to great work done by many Open Source projects.
