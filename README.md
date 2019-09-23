# Getting Started
Please, follow the instructions below for installing and run CTFR.

### Pre-requisites
Make sure you have installed the following tools:
```
Python 3.0 or later.
pip3 (sudo apt-get install python3-pip).
```

### Installing
```bash
$ pip3 install -r requirements.txt
```

### Running
```bash
$ python3 dsearch.py --help
```

## Usage
Parameters and examples of use.

### Parameters
```
-d --domain [target_domain] (required)
-o --output [output_file] (optional)
```

### Examples
```bash
$ python3 dsearch.py -d starbucks.com
```
```bash
$ python3 dsearch.py -d facebook.com -o /home/$USER/subdomains_fb.file
```
