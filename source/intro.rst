=================================
Intro
=================================


Build Systems :
---------------
Build systems describe exactly how to build targets.
 * They define dependencies
 * They handle command for each compilation (make, ninja, invoke or rake)




Build system generator :
---------------
Build system generators describe general relationships.

 * write build system file 
 * BUT let the build system do the build.


Cmake syntaxe
---------------

.. code-block:: bash

    cmake -S . -B build 
    cmake --build build

**Explication** 

- `cmake -S . -B build` configure le projet en utilisant le répertoire courant comme source et crée les fichiers de build dans le répertoire `build`.
- `cmake --build build` compile le projet en utilisant les fichiers de build générés.

-S source (.)  \
-B dossier de build  
puis build le dossier.  