# TQDT11

This is the source code for my degree project.

PrefuxLibrary.zip:
- This archive contains my modified version of Prefux.
- The latest build of this library can be found under "../build/libs".
- Additional libraries related to Apache-Jena can be found under "../lib".

PrefuxTest.zip:
- This archive contains my test project for using the Prefux library.
To open the project:
  1. Start NetBeans IDE 8.0.2.
  2. Open the project.
    - NetBeans will most likely warn about problems when first opening the project.
    - These problems relate to the paths for the libraries being incorrect.
    To solve the problems:
      1. Select "Resolve". This should open a window showing all libraries that are missing.
      2. Select the library from this window, click "Resolve" and navigate to the library.
        - All libraries are provided in this repository and in the "PrefuxLibrary.zip" file.
      3. Once all problems have been resolved, "close" the window.
  3. It should now be possible to simply run the project.
    - Note: the path to the ontology (OWL file) needs to be changed in the main file "PrefuxTest.java".
    - To do this, change the path given as a parameter to the GraphOWLReader object on rows 72-97.
    
Alternatively, one can use their own application to use the Prefux library:
- It should still be required to include the libraries mentioned above in the application.
