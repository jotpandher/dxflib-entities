dxfrwentities
=============
This code takes up the text file which contains the information about the entities to be drawn and there parameters creates the corresponding dxf files. Point, line, rectangle, arc, ellipse and circle are implemented.

Compile the entities.pro file by running following commands: 
For creating Dxf file -
qmake test.pro

make

./test.sh

For reading Dxf file -
qmake test.pro

make

./test <dxf file>
