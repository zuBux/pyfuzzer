# pyfuzzer
A file-format fuzzer for Windows, utilising [pyZZUF] (https://github.com/nezlooy/pyZZUF) for input mutation and [WinAppDbg] (http://winappdbg.sourceforge.net/) for crash detection. It was created for demostrational purposes, for the second part of a tutorial on basic fuzzing concepts which was never completed.

## Usage

pyfuzzer expects the following options:

* -i <path> : Input testcase folder
* -t <type> : Target filetype. Searches the input folder for a matching testcase
* -p <path> : Path of the target executable

Example :

```
python pyfuzzer.py -i C:\Users\user\testcases -t mp4 -p C:\Program Files\TargetPlayer\player.exe
```
