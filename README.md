# Remove(rm) by Extension(ext)

Assume a situation when you have to delete a lot of files of certain extension recursively from hundreds of folder. This program makes that task very easy.

## Requirements

* Python 3

## Installation

```shell
pip install git+https://github.com/fhsinchy/rmbyext.git#egg=rmbyext
pip freeze
```

Output &ndash;

```shell
rmbyext==1.0.0
```

## Usage

Once you have installed the package it should be available everywhere in your system. The generic command for executing this script is

```shell
rmbyext <file extension>
```

or in case of multiple extensions

```shell
rmbyext <file extension> <file extension>
```

Lets say you want to delete all the **PDF** files from a directory. You simply put this script on that directory and execute

```shell
rmbyext pdf
```

The script will look for all **PDF** files recursively and delete all of them. As stated above you can also pass multiple extensions separated by space

```shell
rmbyext pdf txt
```

This command will delete all **PDF** and **TXT** files.

List of the deleted files will be shown on the console as well as written inside `delete_log.log` file in the same directory.
