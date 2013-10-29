PredictionIO ClientBundle
=========================

The `ClientBundle` provides a wrapper for the [PredictionIO](https://github.com/PredictionIO/PredictionIO-PHP-SDK)
library into the Symfony2 framework.

Installation
------------

Using Composer:

Add the following dependencies to your project's composer.json file:

.. code-block::

    "require": {
        # ..
        "predictionio/predictionio-bundle": "*"
        # ..
    }

and add the following to your project's app/AppKernel.php file:

.. code-block::

    # ..
    new PredictionIO\ClientBundle\PredictionIOClientBundle(),
    # ..

