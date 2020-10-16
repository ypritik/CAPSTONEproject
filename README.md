Usage notes
===========

All commands are from this directory.

To test app.py
--------------

``` {.bash}
~$ python app.py
```


To test the model directly
--------------------------

see the code at the bottom of [model.py]{.title-ref}

``` {.bash}
~$ python model.py
```
Run the unittests
-----------------

Before running the unit tests launch the [app.py]{.title-ref}.

To run only the api tests

``` {.bash}
~$ python unittests/ApiTests.py
```

To run only the model tests

``` {.bash}
~$ python unittests/ModelTests.py
```

To run all of the tests

``` {.bash}
~$ python run-tests.py
```
