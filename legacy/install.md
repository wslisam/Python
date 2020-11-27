
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


```
brew upgrade python3                                                     737
Updating Homebrew...
==> Upgrading 1 outdated package:
python3 3.8.3_2 -> 3.8.5
==> Upgrading python3 3.8.3_2 -> 3.8.5
==> Downloading https://homebrew.bintray.com/bottles/gdbm-1.18.1_1.catalina.bott
Already downloaded: /Users/wsli1998/Library/Caches/Homebrew/downloads/21bd17c428e48bcdca0a388899e5f618c52ea2f80af79fc5bf25f28cd59ca2b2--gdbm-1.18.1_1.catalina.bottle.tar.gz
==> Downloading https://homebrew.bintray.com/bottles/sqlite-3.33.0.catalina.bott
Already downloaded: /Users/wsli1998/Library/Caches/Homebrew/downloads/6802724262549ff9d8bb8483907888d3d4f59b87c720f6e595081ef217c6eb6c--sqlite-3.33.0.catalina.bottle.tar.gz
==> Downloading https://homebrew.bintray.com/bottles/python%403.8-3.8.5.catalina
Already downloaded: /Users/wsli1998/Library/Caches/Homebrew/downloads/9dd7cd94f1e3f75a7f2fe63c7333d9de7e8241f212eeaa1e774c45fff2da63f8--python@3.8-3.8.5.catalina.bottle.tar.gz
==> Installing dependencies for python@3.8: gdbm and sqlite
==> Installing python@3.8 dependency: gdbm
==> Pouring gdbm-1.18.1_1.catalina.bottle.tar.gz
🍺  /usr/local/Cellar/gdbm/1.18.1_1: 25 files, 641KB
==> Installing python@3.8 dependency: sqlite
==> Pouring sqlite-3.33.0.catalina.bottle.tar.gz
==> Caveats
sqlite is keg-only, which means it was not symlinked into /usr/local,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

If you need to have sqlite first in your PATH run:
  echo 'export PATH="/usr/local/opt/sqlite/bin:$PATH"' >> ~/.zshrc

For compilers to find sqlite you may need to set:
  export LDFLAGS="-L/usr/local/opt/sqlite/lib"
  export CPPFLAGS="-I/usr/local/opt/sqlite/include"

For pkg-config to find sqlite you may need to set:
  export PKG_CONFIG_PATH="/usr/local/opt/sqlite/lib/pkgconfig"

==> Summary
🍺  /usr/local/Cellar/sqlite/3.33.0: 11 files, 4MB
==> Installing python@3.8
==> Pouring python@3.8-3.8.5.catalina.bottle.tar.gz
==> /usr/local/Cellar/python@3.8/3.8.5/bin/python3 -s setup.py --no-user-cfg ins
==> /usr/local/Cellar/python@3.8/3.8.5/bin/python3 -s setup.py --no-user-cfg ins
==> /usr/local/Cellar/python@3.8/3.8.5/bin/python3 -s setup.py --no-user-cfg ins
==> Caveats
Python has been installed as
  /usr/local/bin/python3

Unversioned symlinks `python`, `python-config`, `pip` etc. pointing to
`python3`, `python3-config`, `pip3` etc., respectively, have been installed into
  /usr/local/opt/python@3.8/libexec/bin

You can install Python packages with
  pip3 install <package>
They will install into the site-package directory
  /usr/local/lib/python3.8/site-packages

See: https://docs.brew.sh/Homebrew-and-Python
==> Summary
🍺  /usr/local/Cellar/python@3.8/3.8.5: 4,341 files, 67.3MB
==> `brew cleanup` has not been run in 30 days, running now...
Removing: /usr/local/Cellar/gdbm/1.18.1... (20 files, 602.8KB)
Removing: /usr/local/Cellar/python@3.8/3.8.3... (4,125 files, 63MB)
Removing: /usr/local/Cellar/python@3.8/3.8.3_2... (4,247 files, 65.3MB)
Removing: /usr/local/Cellar/sqlite/3.32.3... (11 files, 4MB)
Error: Permission denied @ apply2files - /usr/local/lib/node_modules/yo/node_modules/extglob/lib/.DS_Store
```


```
brew install tcl-tk                                                                                                                                              855
Updating Homebrew...
^CWarning: You are using macOS 11.0.
We do not provide support for this released but not yet supported version.
You will encounter build failures with some formulae.
Please create pull requests instead of asking for help on Homebrew's GitHub,
Twitter or any other official channels. You are responsible for resolving
any issues you experience while you are running this
released but not yet supported version.

==> Downloading https://homebrew.bintray.com/bottles/openssl%401.1-1.1.1h.big_sur.bottle.tar.gz
==> Downloading from https://d29vzk4ow07wi7.cloudfront.net/81fe98e819f1d3554d98cbf615c848cc1837c65b6026cb561b0d58531b0ab65e?response-content-disposition=attachment%3Bfi
######################################################################## 100.0%
==> Downloading https://homebrew.bintray.com/bottles/tcl-tk-8.6.10.big_sur.bottle.1.tar.gz
==> Downloading from https://d29vzk4ow07wi7.cloudfront.net/b7c942f7fc15b6a402bf4d071dcea29682db9364d47ca34fcb3b7cd72c254968?response-content-disposition=attachment%3Bfi
######################################################################## 100.0%
==> Installing dependencies for tcl-tk: openssl@1.1
==> Installing tcl-tk dependency: openssl@1.1
==> Pouring openssl@1.1-1.1.1h.big_sur.bottle.tar.gz
==> Caveats
A CA file has been bootstrapped using certificates from the system
keychain. To add additional certificates, place .pem files in
  /usr/local/etc/openssl@1.1/certs

and run
  /usr/local/opt/openssl@1.1/bin/c_rehash

openssl@1.1 is keg-only, which means it was not symlinked into /usr/local,
because macOS provides LibreSSL.

If you need to have openssl@1.1 first in your PATH run:
  echo 'export PATH="/usr/local/opt/openssl@1.1/bin:$PATH"' >> ~/.zshrc

For compilers to find openssl@1.1 you may need to set:
  export LDFLAGS="-L/usr/local/opt/openssl@1.1/lib"
  export CPPFLAGS="-I/usr/local/opt/openssl@1.1/include"

For pkg-config to find openssl@1.1 you may need to set:
  export PKG_CONFIG_PATH="/usr/local/opt/openssl@1.1/lib/pkgconfig"

==> Summary
🍺  /usr/local/Cellar/openssl@1.1/1.1.1h: 8,067 files, 18.5MB
==> Installing tcl-tk
==> Pouring tcl-tk-8.6.10.big_sur.bottle.1.tar.gz
==> Caveats
tcl-tk is keg-only, which means it was not symlinked into /usr/local,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

If you need to have tcl-tk first in your PATH run:
  echo 'export PATH="/usr/local/opt/tcl-tk/bin:$PATH"' >> ~/.zshrc

For compilers to find tcl-tk you may need to set:
  export LDFLAGS="-L/usr/local/opt/tcl-tk/lib"
  export CPPFLAGS="-I/usr/local/opt/tcl-tk/include"

For pkg-config to find tcl-tk you may need to set:
  export PKG_CONFIG_PATH="/usr/local/opt/tcl-tk/lib/pkgconfig"

==> Summary
🍺  /usr/local/Cellar/tcl-tk/8.6.10: 3,037 files, 51.4MB
==> `brew cleanup` has not been run in 30 days, running now...
```