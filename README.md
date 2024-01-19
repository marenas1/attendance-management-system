# attendance-management-system

Created By: **Matthew Arenas**

Tech: **Java,JavaFX,ControlsFX,Maven**

This is a gui application that allows users to add, delete, modify and keep track of various students and the data that pertains to them. Additionally, it allows mass printing of certificates and documents which are autofilled to contain the student's information. Packaged and available for any windows machine when run with the .dat file in the same directory. Download under the releases tab.

Development Period **August-December 2023**

## Features

- [ ] Keep track of many students and have different ways to sort them, club, belt, name etc.
- [ ] Keeps track of last seven days of attendance allowing you to see what days people came to class.
- [ ] Has a student search that pops up all student data and last classes attended.
- [ ] Autofills certificates based on what students are chosen and send this to print.
- [ ] Allows the choosing of your own certificate files
- [ ] Student data is all stored in a student object allowing for easy retreival.
- [ ] Saves student objects and encrypts student data in a .dat file. Done using serialization with java.
- [ ] Bundled into exe containing jre and javafx and controlsfx libraries so any windows machine can run it.
 
## Notes

Challenges Faced:

Exporting JavaFX project to an exe. Ultimately done using by creating a maven project and and creating an image using Jlink that includes the JRE, JavaFX and Controls FX library. Then using warp-packer it is turned into an exe.

## License

    Copyright [2024] [Matthew Arenas]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
