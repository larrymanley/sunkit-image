0.2.0 (2021-05-04)
==================

Features
--------

- The minimum and maximum values of the gamma transform can now be specified for :func:`sunkit_image.enhance.mgn`. (`#60 <https://github.com/sunpy/sunkit-image/pull/60>`__)


Bug Fixes
---------

- Increased the minimum version of "skimage" to 0.18.0, preventing faulty code in :meth:`sunkit-image.utils.points_in_poly`. (`#59 <https://github.com/sunpy/sunkit-image/pull/59>`__)


Trivial/Internal Changes
------------------------

- Added multiple unit tests to increase code coverage. (`#59 <https://github.com/sunpy/sunkit-image/pull/59>`__)
- Increased minimum supported version of sunpy to 2.0.0
- Many internal package updates to documentation, the continuous integration and etc.

0.1.0 (2020-04-30)
==================

Features
--------

- Added a class (`sunkit_image.utils.noise.NoiseLevelEstimation`) for noise level estimation of an image. (`#12 <https://github.com/sunpy/sunkit-image/pull/12>`__)
- Added a new function (`sunkit_image.radial.fnrgf`) to normalize the radial brightness gradient using a Fourier approximation. (`#17 <https://github.com/sunpy/sunkit-image/pull/17>`__)
- Added a function (`sunkit_image.enhance.mgn`) for applying Multi-scale Gaussian Normalization to an image (`numpy.ndarray`). (`#30 <https://github.com/sunpy/sunkit-image/pull/30>`__)
- Added a new function (`sunkit_image.trace.occult2`) to automatically trace out loops/curved structures in an image. (`#31 <https://github.com/sunpy/sunkit-image/pull/31>`__)
- Added an implementation of the Automated Swirl Detection Algorithm (ASDA). (`#40 <https://github.com/sunpy/sunkit-image/pull/40>`__)


Improved Documentation
----------------------

- Added an example on how to use `astroscrappy.detect_cosmics <https://astroscrappy.readthedocs.io/en/latest/api/astroscrappy.detect_cosmics.html>`__ to eliminate cosmic ray hits in solar images. (`#35 <https://github.com/sunpy/sunkit-image/pull/35>`__)


Trivial/Internal Changes
------------------------

- Transferred sunkit_image.utils.noise.NoiseLevelEstimation from class object into a series of functions. (`#38 <https://github.com/sunpy/sunkit-image/pull/38>`__)
