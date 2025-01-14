1.4.1 (unreleased)
------------------

1.4.0 (2022-03-10)
------------------
- fixed matplotlib plotting issue, added explicit draw and interaction plots
- updates to package setup, removed support for TEAL interface [#63]
- changes to documentation infrastructure and text [#64]
- fixed bug in sub2full.py that required input file to be in pwd, now a file path can be supplied [#64]
- removed 'version' argument (which corresponds to the command line -r flag) from calwf3 python interface [#64]
- updates to module docstrings [#64]

1.3.5 (released)
----------------
- Documentation-only updates corresponding to calwf3 3.4.1 release
- travis sphinx install update for testing

1.3.4 (released)
----------------
- bugfix for input string to calwf3 executables

1.3.3 (released)
----------------
This release incorporates documentations changes for CALWF3 which will increase from v3.3 to v3.4 with the installation of HSTDP 2016.2 in the Space Telescope Data processing system. Included are:

- updated information on CTE correction for subarray images
- updated information on Sink pixel detection for subarray images
- updated interaction with the Jupyter notebook when interacting with the calwf3 executables
- improved logging and error return information from the kernel

1.3.2 (released)
----------------
- package reorganization
- addition of output capture/logging to the calwf3 executables, help display text in jupyter notebook
- moved the documentation to readthedocs and removed the local build, users will now be pointed to RTD from the display_help() function

