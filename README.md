
IoT-LAB cli-tools provide a basic set of operations for managing IoT-LAB
experiments from the command-line.  The following commands are available:


  command          |  functions
  ---------------  |  -------------------------------
``auth-cli``       |  configure account credentials
``experiment-cli`` |  start, stop, query experiments
``node-cli``       |  start, stop, reset nodes
``profile-cli``    |  manage nodes configurations


Commands are self-documented, and usually have sub-commands which are also
self-documented.  Use e.g. ``node-cli --help``, ``profile-cli add --help``.

The cli-tools leverage the IoT-LAB [[REST API]] and simply wrap calls to
module ``iotlabcli``, which is a Python (2.5 or higher) client for the API. 

The cli-tools come as an installable Python package and require that
module ``setuptools`` be installed before tools installation can happen.
Please grab the relevant python-setuptools package for your distribution.
Installing cli-tools automatically fetches additional dependencies as needed.

Further documentation: https://github.com/iot-lab/iot-lab/wiki/CLI-Tools
