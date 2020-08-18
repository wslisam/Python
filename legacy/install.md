
 ✔  13:24:39  wsli1998  ~/Documents/Python 
 /usr/local/opt/python@3.8/bin/python3.8 /Users/wsli1998/.vscode/extensions/ms-python.python-2020.6.91350/pythonFiles/pyvsc-run-isolated.py pip install -U pylint --user
Collecting pylint
  Downloading pylint-2.5.3-py3-none-any.whl (324 kB)
     |████████████████████████████████| 324 kB 92 kB/s 
Collecting mccabe<0.7,>=0.6
  Downloading mccabe-0.6.1-py2.py3-none-any.whl (8.6 kB)
Collecting toml>=0.7.1
  Downloading toml-0.10.1-py2.py3-none-any.whl (19 kB)
Collecting astroid<=2.5,>=2.4.0
  Downloading astroid-2.4.2-py3-none-any.whl (213 kB)
     |████████████████████████████████| 213 kB 335 kB/s 
Collecting isort<5,>=4.2.5
  Downloading isort-4.3.21-py2.py3-none-any.whl (42 kB)
     |████████████████████████████████| 42 kB 342 kB/s 
Collecting wrapt~=1.11
  Downloading wrapt-1.12.1.tar.gz (27 kB)
Collecting lazy-object-proxy==1.4.*
  Downloading lazy-object-proxy-1.4.3.tar.gz (34 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
    Preparing wheel metadata ... done
Requirement already satisfied, skipping upgrade: six~=1.12 in /usr/local/Cellar/protobuf/3.12.3/libexec/lib/python3.8/site-packages (from astroid<=2.5,>=2.4.0->pylint) (1.15.0)
Building wheels for collected packages: wrapt, lazy-object-proxy
  Building wheel for wrapt (setup.py) ... done
  Created wheel for wrapt: filename=wrapt-1.12.1-cp38-cp38-macosx_10_15_x86_64.whl size=32590 sha256=42b831306fa7a744071a5ffa9e8aef30a13f52670b966b687379315477f342f4
  Stored in directory: /Users/wsli1998/Library/Caches/pip/wheels/5f/fd/9e/b6cf5890494cb8ef0b5eaff72e5d55a70fb56316007d6dfe73
  Building wheel for lazy-object-proxy (PEP 517) ... done
  Created wheel for lazy-object-proxy: filename=lazy_object_proxy-1.4.3-cp38-cp38-macosx_10_15_x86_64.whl size=19531 sha256=c7d0d9b6db7e4d21667445449605bccf06988e3145aa8e501a52bde4a159ce0e
  Stored in directory: /Users/wsli1998/Library/Caches/pip/wheels/d7/f7/3b/6853df4a25a106662f20e70ad6bd448c8ae07d12ce80fb9063
Successfully built wrapt lazy-object-proxy
Installing collected packages: mccabe, toml, wrapt, lazy-object-proxy, astroid, isort, pylint
  WARNING: The script isort is installed in '/Users/wsli1998/Library/Python/3.8/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts epylint, pylint, pyreverse and symilar are installed in '/Users/wsli1998/Library/Python/3.8/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed astroid-2.4.2 isort-4.3.21 lazy-object-proxy-1.4.3 mccabe-0.6.1 pylint-2.5.3 toml-0.10.1 wrapt-1.12.1

 ✔  13:25:06  wsli1998  ~/Documents/Python 
                                                                                                                                                                  493





```

 ✔  15:47:53  wsli1998  ~/Documents/Python 
 source /Users/wsli1998/Documents/Python/.venv/bin/activate                         502

 ✔  15:47:54  wsli1998  ~/Documents/Python 
 python3 -m pip install matplotlib                                                  503
Collecting matplotlib
  Downloading https://files.pythonhosted.org/packages/10/40/81bdeaf5fd9928b46b671ba5af588dfa5cb118bbf134fab47747c1e59fa4/matplotlib-3.3.0-1-cp38-cp38-macosx_10_9_x86_64.whl (11.4MB)
     |████████████████████████████████| 11.4MB 672kB/s 
Collecting numpy>=1.15 (from matplotlib)
  Downloading https://files.pythonhosted.org/packages/2f/c0/09c526b4167ed4dd3bcb6d6aa2103b4b50899e8eae89acde6455d43a37e4/numpy-1.19.1-cp38-cp38-macosx_10_9_x86_64.whl (15.3MB)
     |████████████████████████████████| 15.3MB 585kB/s 
Collecting pyparsing!=2.0.4,!=2.1.2,!=2.1.6,>=2.0.3 (from matplotlib)
  Downloading https://files.pythonhosted.org/packages/8a/bb/488841f56197b13700afd5658fc279a2025a39e22449b7cf29864669b15d/pyparsing-2.4.7-py2.py3-none-any.whl (67kB)
     |████████████████████████████████| 71kB 655kB/s 
Collecting cycler>=0.10 (from matplotlib)
  Downloading https://files.pythonhosted.org/packages/f7/d2/e07d3ebb2bd7af696440ce7e754c59dd546ffe1bbe732c8ab68b9c834e61/cycler-0.10.0-py2.py3-none-any.whl
Collecting kiwisolver>=1.0.1 (from matplotlib)
  Downloading https://files.pythonhosted.org/packages/f6/d7/d7516741c1043c3b9a55b9eb7762ec06bab4df1187705efd7dbb37d6f5ee/kiwisolver-1.2.0-cp38-cp38-macosx_10_9_x86_64.whl (60kB)
     |████████████████████████████████| 61kB 667kB/s 
Collecting python-dateutil>=2.1 (from matplotlib)
  Downloading https://files.pythonhosted.org/packages/d4/70/d60450c3dd48ef87586924207ae8907090de0b306af2bce5d134d78615cb/python_dateutil-2.8.1-py2.py3-none-any.whl (227kB)
     |████████████████████████████████| 235kB 533kB/s 
Collecting pillow>=6.2.0 (from matplotlib)
  Downloading https://files.pythonhosted.org/packages/53/7d/c0db10e5f990905aa4bc4f8166414d8a30fb766c1624ced9fe9a43a211d9/Pillow-7.2.0-cp38-cp38-macosx_10_10_x86_64.whl (2.2MB)
     |████████████████████████████████| 2.2MB 259kB/s 
Collecting six (from cycler>=0.10->matplotlib)
  Downloading https://files.pythonhosted.org/packages/ee/ff/48bde5c0f013094d729fe4b0316ba2a24774b3ff1c52d924a8a4cb04078a/six-1.15.0-py2.py3-none-any.whl
Installing collected packages: numpy, pyparsing, six, cycler, kiwisolver, python-dateutil, pillow, matplotlib
Successfully installed cycler-0.10.0 kiwisolver-1.2.0 matplotlib-3.3.0 numpy-1.19.1 pillow-7.2.0 pyparsing-2.4.7 python-dateutil-2.8.1 six-1.15.0
WARNING: You are using pip version 19.2.3, however version 20.2.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.

 ✔  15:49:00  wsli1998  ~/Documents/Python 
                                                                                    504
```


```
 pip install opencv-python                                                                                                                                        597
Collecting opencv-python
  Downloading https://files.pythonhosted.org/packages/1b/88/004fff6e1b85d0eee63bb35f959000a170b1a16cc7503b93232d4f4284ea/opencv_python-4.4.0.40-cp38-cp38-macosx_10_13_x86_64.whl (52.6MB)
     |████████████████████████████████| 52.6MB 566kB/s 
Collecting numpy>=1.17.3 (from opencv-python)
  Using cached https://files.pythonhosted.org/packages/2f/c0/09c526b4167ed4dd3bcb6d6aa2103b4b50899e8eae89acde6455d43a37e4/numpy-1.19.1-cp38-cp38-macosx_10_9_x86_64.whl
Installing collected packages: numpy, opencv-python
Successfully installed numpy-1.19.1 opencv-python-4.4.0.40
WARNING: You are using pip version 19.2.3, however version 20.2.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.
```