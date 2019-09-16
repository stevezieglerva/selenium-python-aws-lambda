# Selenium Python on AWS Lambda

Based on the forked repo. This version copies the binaries from the python-selenium-simplified-08bbf830-5b37-4638-8af3-e684cf3094b9.zip layer extraction to tmp/bin where they seem to be required for execution. It also adds the execution rights in order for it to work.

Layer based on Ziegler AWS python-selenium-simplified used in the selenium2 Lambda that works.

Requires Env parameters for 
PATH = /tmp/bin
PYTHON_PATH = /opt/python