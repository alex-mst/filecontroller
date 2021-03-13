***********
Information
***********

What is FileController?
=======================

FileController is a utilized Python 3 library to make working with files easier than ever. It offers all of the built-in
Python File Management Utilities (open, create, delete) etc. as well as more advanced features like a ZIP viewer, a file
combiner, a user-friendly file editor etc. It can make working with files in Python so much more comfortable and easy,
and with it's utilities and tools it can change the way people work with files. It is easily accessible, small and
effective at the same time! All you have to do is download FileController and start using it!

Why should you use FileController?
==================================

As mentioned before, FileController is a PyPi Project with a large scale of tools and utilities to make the user's
experience with files easy and quick. It can be used any time the user wants to access, modify or delete any files. You
can easily access it through the code at any given time, and use it in all sorts of projects that involve files. It can
save you time and space, and it can make it easier to access or modify multiple files at once without getting lost.
FileController also features more advanced utilities like the ZIP reader and archive makes, merging files, deleting/editing
specific lines etc.

What is coming up in the future?
================================

Improvements and bug-fixed are happening every day, so there is no way to guess exactly what is changing in the next
versions, but here are a few planned things to change:

* FileManager and ZipViewer split and more features added to both of them
* GUI Interface for ZIP Creator and file editor
* ZIP Archiving for all types of files
* File Encrpytor and Decryptor
* File Protector that can password-protect files
* File Type Changer (With GUI Interface)

Apart from all that, new bugfixes and small features are being made on a daily basis and the source code is always public
for other developers to help. If you experience any errors with FileController feel free to contact me on GitHub or on
my discord (Scarface#3902)

********************
Using FileController
********************

1 - Getting Started
===================


1.1 - Installing FileController
-------------------------------

Windows
~~~~~~~

1. Open up Command Prompt by clicking the Windows Key + R on your keyboard and typing ``cmd``
2. After you have CMD open, type ``pip install filecontroller`` (if you use a Virtual Enviroment type the same thing on
   the IDE's command line)
3. After you have done that, check it by typing ``pip list``
4. If you see ``filecontroller`` in the list, you are good to go! If not, try the command ``pip install --upgrade pip``
   and try the process again

MAC
~~~
1. Open Terminal and type ``pip install filecontroller`` (if ``pip`` is not on your compter, type ``easy_install pip``)
2. After you've installed that, check if it's installed by typing ``pip list``.
3. If you see ``filecontroller`` in the list, you are good to go! If not, try the command ``pip install --upgrade pip``
   and try the process again

Linux
~~~
Linux installation depends on your version of linux, look up ``how to install python modules on (version)`` and you
should find some helpful information.


1.2 - Setting up FileController
-------------------------------

To set up FileController, open up any python project and do the following:
1. Import the project by typing ``from filecontroller import *``
2. Set the ``fileController()`` class to an object by typing ``my_object = fileController()``
3. Every time you want to use a function, type ``my_object.function()`` to call it.

Here is a full example of a code that can read a 'test.txt' file assuming it's on the same directory:

.. code-block:: python
    :linenos:

    from filecontroller import *
    my_object = fileController()

    my_object.readFile('test.txt')


Note: From now on I'll be refering to the Class Object as ``fc``

1.3 - Basic Functions of FileController
---------------------------------------

Although all the functions are listed on the Code Documentation with their exact usages, here I'll be listing some of
the most basic functions of FileController:

* fc.readFile('test.txt') -> Opens a 'test.txt' file
* fc.writeToFile('test.txt', 'Test Note') -> Writes 'Test Note' at the bottom of the 'test.txt' file
* fc.editFile('test.txt', 2, 'Edited Line') -> Will edit the line 2 of the file (not supporting binary, 0 is 1)
* fc.deleteFile('test.txt') -> Deletes the contents of the 'test.txt' file
* fc.renameFile('test.txt', 'renamed.txt') -> Renames 'test.txt' to 'renamed.txt'

These are the most basic functions of FileController. Other functions are as useful, but these are the mostly used in
normal python file management

1.4 - Advanced Functions of FileController
------------------------------------------

As we mentioned above, FileController also has some advanced functions like the ZIP-Viewer. Here are a few functions of
the ZIP Viewer and some other advanced functions:

* fc.zipFiles(2, 'zipped.zip') -> You set the number of .txt files you want to archive into a ZIP, then you put each
  file/directory when it asks you to input them into the console, and you have a ready .ZIP archive in that directory!
* fc.readZIP('zipped.zip') -> Displays a tree view of the .ZIP file you choose (it works with directories too)

1.5 - Errors and Problems
-------------------------

If you encounter any error while using FileController, don't hesitate to contact me on discord as I've mentioned before
(Scarface#3902) or on my GitHub Profile (alex.m). This project is beta and I'm making everything by myself, so I'd
appreciate and bug reports that will help me make FileController as good as possible. But, until I make the next release,
I have good news. If you've encountered an error and you've messaged me, chances are, within some hours or days, it will
be fixed on the GitHub Open Source page of the project, where I constantly post stability updates and I resolve issues.
Because I won't be releasing PyPi versions for every little issue, GitHub is the way to go. Moreover, if you know
Python well enough and you're interested in helping me with the projects, feel free to contact me on Discord, and we
can start working! I'd really appreciate any help that will make me make the project as good as possible, so any help
you can provide is much appreciated.

********************
Conclusion
********************

Hope you liked this simple explanation of FileController. If you want more information about each function and their usages,
feel free to go into the Code Documentation to find out more.

--End--
