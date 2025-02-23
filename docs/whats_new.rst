.. currentmodule:: bayspar

What's New
==========

.. _whats-new.0.0.4:

v0.0.4
------

Enhancements
~~~~~~~~~~~~
- Minor improvements to documentation.

Bug fixes
~~~~~~~~~
-


.. _whats-new.0.0.3:

v0.0.3
------

Enhancements
~~~~~~~~~~~~
- Many minor changes to documentation.


.. _whats-new.0.0.2:

v0.0.2
------

Enhancements
~~~~~~~~~~~~
- :py:attr:`Prediction.location` refactored to :py:attr:`Prediction.latlon` (`Issue #8 <https://github.com/brews/baysparpy/issues/8>`_).
- Removed unused :py:attr:`Draws.alpha_samples_field` and :py:attr:`Draws.beta_samples_field` to cut down package size. Also, we dropped the maximum MCMC parameter ensemble size to 10,000 to further reduce size (`Issue #1 <https://github.com/brews/baysparpy/issues/1>`_).
- Many ``assert`` errors replaced with full errors (`Issue #7 <https://github.com/brews/baysparpy/issues/7>`_).
- Improved ``pip`` and ``conda`` install instructions (`Issue #6 <https://github.com/brews/baysparpy/issues/6>`_).

Bug fixes
~~~~~~~~~
- Minor corrections to documentation and docstrings (`Issue #10 <https://github.com/brews/baysparpy/issues/10>`_, `Issue #5 <https://github.com/brews/baysparpy/issues/5>`_).
- Trim burnin from tau2 MCMC params (`Issue #3 <https://github.com/brews/baysparpy/issues/3>`_)

.. _whats-new.0.0.1:

v0.0.1
------

- This is the first release of **baysparpy**.
