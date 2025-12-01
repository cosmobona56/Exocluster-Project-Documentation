# Exocluster Project Documentation
This is our documentation on our Exocluster AI Project, connecting multiple PCs to run the AI.
# WARNING: This Documentation is still work in progress and is still NOT complete.
Have fun reading!




# 1. Boot testing
So first we grabbed one PC with following specs:
  OPTIPLEX 7010<br />
  RAM: 4GB DDR3 SDRAM (Upgrade to 8GB planned) <br />
  CPU: Intel Core i5 3570 @3,4 Ghz <br />
  HDD: Generic 80GB HDD <br />

Like you see, the specs are pretty low, but we will get multiple PCs pretty soon so the specs will combine and get better.

# 2. Operative System
For the Project we used Linux. Exo is highly compatible with Linux. We didnt try WSL (Windows Subsystem for Linux), so it could work but also not.
First we tried using CachyOS, but it was a pain of trying things to install and work. So we switched to Fedora, and it worked better. You can decide whether you are a Arch or Debian person.

# 3. Python
To install the dependencies we need pip, so we need Python. Python Version 3.12 or higher will work.

# 4. Installing Exo
Installing Exo is pretty easy, but installing dependencies was hard. <br />
So to get Exo on the Computer, you need to clone the Git-Repository <br />

```console
git clone https://github.com/exo-explore/exo.git
```
Then, cd into the exo folder for setup <br />

```console
cd exo
```

The exo guide tells you to install the dependencies using 
```console
pip install -e .
```
