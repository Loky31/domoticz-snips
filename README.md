Last change :
Add of lot of exemple and keywords that allow to simplify the creation of dummy switch on Domoticz side.


# Generated Snips skill

This is a generated Python 3 snips app, using the `snips-template` tool.
It is compatible with the format expected by the `snips-skill-server`

## Setup

This app requires some python dependencies to work properly, these are
listed in the `requirements.txt`. You can use the `setup.sh` script to
create a python virtualenv that will be recognized by the skill server
and install them in it.

## Executables

This dir contains a number of python executables named `action-*.py`.
One such file is generated per intent supported. These are standalone
executables and will perform a connection to MQTT and register on the
given intent using the `hermes-python` helper lib.

## Knwon issue 
This code is subject to SNIPS bug https://github.com/snipsco/snips-issues/issues/94
-  Fixed in version 1.1.2 (0.62.0)
- go on https://github.com/snipsco/snips-issues/issues/94 for workaround
