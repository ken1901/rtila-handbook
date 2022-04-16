Automated form filling
======================

.. toctree::

HTML uses many form elements like input (text, password, checkbox, radio), label, textarea, select, option etc. In this use case we will work with this demo site: https://testpages.herokuapp.com/styled/basic-html-form-test.html

Start a new project
-------------------

.. image:: ../../Images/Screenshot_323.png

.. image:: ../../Images/Screenshot_324.png

Configure commands
------------------

In this project only the automation panel will be used.

Multiple values variable
~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_325.png

.. image:: ../../Images/Screenshot_326.png

.. image:: ../../Images/Screenshot_327.png

We will work with data below to fill the form, you can change file paths for accurate results.

::

    username_1;password_1;comment_1;C:\Users\MY-PC\Documents\RTILA\filenames\1.txt;cb1;rd1;ms1,ms2;dd1;hidden_1
    username_2;password_2;comment_2;C:\Users\MY-PC\Documents\RTILA\filenames\2.txt;cb2;rd2;ms3,ms4;dd2;hidden_2
    username_3;password_3;comment_3;C:\Users\MY-PC\Documents\RTILA\filenames\3.txt;cb3;rd3;ms1,ms4;dd3;hidden_3
    username_4;password_4;comment_4;C:\Users\MY-PC\Documents\RTILA\filenames\4.txt;cb1;rd1;ms2,ms3;dd4;hidden_4
    username_5;password_5;comment_5;C:\Users\MY-PC\Documents\RTILA\filenames\5.txt;cb2;rd2;ms4,ms2;dd5;hidden_5
    username_6;password_6;comment_6;C:\Users\MY-PC\Documents\RTILA\filenames\6.txt;cb3;rd3;ms3,ms1;dd6;hidden_6

.. image:: ../../Images/Screenshot_328.png

**Parsing parameters and variables**

::

    {{variable name}}

::

    {{variable name|column index}}

.. image:: ../../Images/Screenshot_375.png

.. image:: ../../Images/Screenshot_376.png

Text input
~~~~~~~~~~

.. image:: ../../Images/Screenshot_329.png

.. image:: ../../Images/Screenshot_330.png

.. image:: ../../Images/Screenshot_331.png

Password input
~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_332.png

.. image:: ../../Images/Screenshot_333.png

.. image:: ../../Images/Screenshot_334.png

Textarea element
~~~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_335.png

.. image:: ../../Images/Screenshot_336.png

.. image:: ../../Images/Screenshot_337.png

File upload input
~~~~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_338.png

.. image:: ../../Images/Screenshot_339.png

.. image:: ../../Images/Screenshot_364.png

Checkbox input
~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_340.png

.. image:: ../../Images/Screenshot_341.png

.. image:: ../../Images/Screenshot_342.png

Radio input
~~~~~~~~~~~

.. image:: ../../Images/Screenshot_343.png

.. image:: ../../Images/Screenshot_344.png

.. image:: ../../Images/Screenshot_345.png

Select multiple dropdown options
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_346.png

.. image:: ../../Images/Screenshot_347.png

.. image:: ../../Images/Screenshot_348.png

Select single dropdown option
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_349.png

.. image:: ../../Images/Screenshot_350.png

.. image:: ../../Images/Screenshot_351.png

Click on submit button
~~~~~~~~~~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_352.png

.. image:: ../../Images/Screenshot_353.png

.. image:: ../../Images/Screenshot_354.png

.. image:: ../../Images/Screenshot_355.png

.. image:: ../../Images/Screenshot_356.png

.. image:: ../../Images/Screenshot_357.png

.. image:: ../../Images/Screenshot_358.png

.. image:: ../../Images/Screenshot_359.png

.. image:: ../../Images/Screenshot_360.png

.. image:: ../../Images/Screenshot_361.png

Run the project
---------------

.. image:: ../../Images/Screenshot_362.png

.. image:: ../../Images/Screenshot_363.png

.. image:: ../../Gifs/Animation_1.gif

Pull data from a CSV file
-------------------------

All CSV and plain text files are supported. The Comma separator is used to work with multiple values so it's recommended to use other separators like Semicolon.

.. image:: ../../Images/Screenshot_365.png

.. image:: ../../Images/Screenshot_366.png

Absolute path
~~~~~~~~~~~~~

Absolute paths are for local projects, if you want to generate standalone bots you will need to specify relative paths.

.. image:: ../../Images/Screenshot_367.png

Relative path
~~~~~~~~~~~~~

.. image:: ../../Images/Screenshot_368.png

.. image:: ../../Images/Screenshot_369.png

.. image:: ../../Images/Screenshot_370.png

.. image:: ../../Images/Screenshot_371.png

.. image:: ../../Images/Screenshot_372.png

.. image:: ../../Images/Screenshot_373.png

.. image:: ../../Images/Screenshot_374.png

