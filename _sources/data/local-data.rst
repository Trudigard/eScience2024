Local shared data
=================

Direct local data access
~~~~~~~~~~~~~~~~~~~~~~~~

Mounted data directories:

- ``~/shared-craas1-nn9989k-cmip6/`` subset of CMIP6 data from ESGF.

- ``~/shared-craas1-nn9989k-ns9560k/CAM6_CESM_PPE`` CAM6 output for Perturbed Parameter Experiment

- ``~/shared-craas1-nn9989k-ns9560k/`` NorESM KeyClim and ForCes data.

- ``~/shared-craas1-geo4992/data/data_group4/`` Fire emissions from CAMS and MERRA2 + aerosol data from `<https://doi.org/10.5194/acp-24-2059-2024>`_ and `<https://doi.org/10.17043/zeppelin-ebc-2015-2019-1>`_.

- ``~/shared-craas1-ns9989k-ns9600k/escience_course/`` Contains folders with the CloudSat Cloud Profiling Radar 2B-GEOPROF data and MERRA aerosol data from 2007-2010.

- ``~/shared-craas1-ns9989k-geo4992/data/data_group3/**``:

  - ``~/shared-craas1-ns9989k-geo4992/data/data_group3/NYA_radiation/`` Longwave and shortwave radiation observational data from Ny-Ålesund, 2006-2024.

  - ``~/shared-craas1-ns9989k-geo4992/data/data_group3/DMPS_ZEP/`` Aerosol size distribution observational data from Zeppelin Observatory, 2000-2020.

  - ``~/shared-craas1-ns9989k-geo4992/data/data_group3/echam_salsa_zep/`` Model output from ECHAM-SALSA with nudged surface meteorology, collocated with Zeppelin observatory from 2011-2020. Aerosol, basic meteorology and radiation parameters.

- ``~/scraas1-ns9989k-geo4992/data/data_group6/`` Hysplit(2018-2019), AMS, CCN and cloud radar derived cloud base Updraft data (warm non-precipitating clouds) from Zeppelin (Ny-Ålesund).

- ``~/shared-craas1-ns9989k-geo4992/data/data_group6/``  Hysplit (2018-19), AMS, CCN and updraft data (cloud-radar derived) for Zappelin

.. note::

  The absolute paths for ``~/shared-craas1-ns9989k**`` are actually ``/mnt/craas1-ns9989k**``. A lot of python packages do not accept symbolic links, so please, use ``/mnt/**``.
