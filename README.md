
#### Steps to generate docs

* Install the Vex VS Code Plugin
* Then generate docs from vex.py like this:

      cd /Users/myusername/Library/Application Support/Code/User/globalStorage/vexrobotics.vexcode/sdk/python/V5/V5_1_0_1_15/vexv5/stubs
      python3 -m venv venv
      source ./venv/bin/activate
      pip3 install pdoc3
      pdoc --html vex.py
