ioc-kfe-at1k4-calc IOC Startup Scripts
=====================================================

KFE/TMO AT1K4 solid attenuator calculator IOC startup script.

config.sh
---------

The IOC configuration settings are primarily in this file.

initialize.sh
-------------

This script creates the environment necessary to run the IOC.

activate\_env.sh
----------------

Use this script to activate the conda environment previously built by
``initialize.sh``.

st.cmd
------

This is the {bash, procserv, IocManager}-compatible entry point
for starting the IOC.
