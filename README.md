![thedevilseye](https://user-images.githubusercontent.com/74001397/131686521-16aa3d2e-dcc6-4d99-a760-eff9fcb90dd2.png)

![Python Version](https://img.shields.io/badge/python-3.x-blue?style=flat&logo=python)
![OS](https://img.shields.io/badge/OS-GNU%2FLinux-red?style=flat&logo=linux)
![GitHub](https://img.shields.io/github/license/rlyonheart/thedevilseye?ystyle=flat)
![CodeFactor](https://www.codefactor.io/repository/github/rlyonheart/thedevilseye/badge)
![Lines of code](https://img.shields.io/tokei/lines/github/rlyonheart/thedevilseye)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/rlyonheart/thedevilseye) 
![GitHub repo size](https://img.shields.io/github/repo-size/rlyonheart/thedevilseye)

Darkweb OSINT tool.
This tool searches the *darkweb* for information relating to the user's query and returns the results including *.onion* links and their description.
**Note**: *Tor* is not required to use this tool.

# Installation
**Clone the repo**:
> <code>$ git clone https://github.com/rlyonheart/thedevilseye.git</code>

>  <code>$ cd thedevilseye</code>

> <code>$ pip install -r requirements.txt</code>

# Usage
> <code>$ python thedevilseye -q QUERY -p PAGE NUMBER (default is 1)</code>

*Or*
> <code>$ python thedevilseye --query QUERY --page PAGE NUMBER</code>

**Example**:
> <code>$ python thedevilseye -q cybersecurity -p 1</code>

*Or*
> <code>$ python thedevilseye --query cybersecurity --page 1</code>




