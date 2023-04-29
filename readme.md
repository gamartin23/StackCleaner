# StackCleaner

StackCleaner is a Python tool that helps clean up and compare Unreal Engine callstacks saved as text files.

StackCleaner was developed for internal use in a GQA team based in Tucumán, Argentina. Since several teams around the world have to deal with Unreal Engine's callstacks and comparing them, StackCleaner has been made available to the general public. Probably other better tools exist out there, but for third-party QA teams... not so much.
Developed and mantained by Kovadev.
## Installation

Download and execute "stackcleaner10setup.exe" or download the project as a zip file, and unzippit before use.


## Usage
In standard mode, select a text file with the "dirty" callstacks and observe the cleaned result below. Save it to a file, or copy it to the clipboard.

In compare mode, select two text files with callstacks, either "dirty" or "clean" callstacks work just fine. Coincidences between the files will be shown below, indicating line number and "clean" function names.


## License

[GNU](https://choosealicense.com/licenses/gpl-3.0/)