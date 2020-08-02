To create a virtual environment in Windows, run the following command:

PS D:\Repos\SimplestCalcLib> & ./calcenv/scripts/activate.ps1
(calcenv) PS D:\Repos\SimplestCalcLib>

Once activated, you should see the prefix (calcenv) at the beginning of the path.
That's means it's the first directory searched when running an executable on the command line. Thus, the shell uses our virtual environment instance's of Python instead of the system-wide version.

To write unit tests, we need to install pytest framework
(calcenv) PS D:\Repos\SimplestCalcLib> pip install pytest pytest-cov

