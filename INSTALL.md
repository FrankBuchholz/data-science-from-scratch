# How to Install Python

If you don't already have Python, I strongly recommend you install the Anaconda version,
which includes many of the libraries needed for data science. Get the Python 3 version, not the Python 2 version.

https://www.anaconda.com/distribution/#download-section

Follow the instructions indicated for your platform.

## Setup

Update conda  
```conda update -n base -c defaults conda```

Create virtual environment  
```conda create -n dsfs python=3.9```

Activate virtual environment  
```conda activate dsfs```

Install required python packages  
```pip install -r requirements.txt```

Install iPython  
```python -m pip install ipython```

## Usage

Change directory  
```cd %USERPROFILE%\Documents\GitHub\data-science-from-scratch```

Activate virtual environment  
```conda activate dsfs```

Start iPython  
```ipython```
