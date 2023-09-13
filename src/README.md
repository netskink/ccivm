# Dir for Source





cd ~
source myenv/bin/activate


# TODO

* select kernel runtime
* select python env
* 


# vs code notes on python venv

## create a python environment or activate one


### create
```
$ python3 -m venv myenv
$ source myenv/bin/activate
```

### activate existing
```
$ source myenv/bin/activate
```
## Install python packages

```
$ pip install --upgrade pip
$ python3 -m pip install <some package>
```

or

```
$ pip install --upgrade pip
$ python3 -m pip install -r requirements.txt
```

## Install python extension

1. `cmd shift x`
2. Type `python`
3. Install Python microsoft extension
4. Install Jupyter microsoft extension

## Create python venv

1. Type `cntrl shift ~` or Terminal in top menu bar
2. activte python env

## Open jupyter notebook and specify python interpreter

1. Type `cmd shift p`
2. Search `Python: Select Interpreter`
3. Navigate to dir where the python3 file is located in the venv created
    - eg. src/myenv/bin/python3