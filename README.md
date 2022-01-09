# devops-aws
CI and CD
# Spin up the AWS cloud9 
copy the sshkey in to github
execute python3 -m venv ~/.devops-aws
python3 -m venv ~/.devops-from-zero


) $ make install
pip install --upgrade pip &&\
        pip install -r requirements.txt
Collecting pip
  Downloading pip-21.3.1-py3-none-any.whl (1.7 MB)
     |████████████████████████████████| 1.7 MB 14.0 MB/s 
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 20.1.1
    Uninstalling pip-20.1.1:
      Successfully uninstalled pip-20.1.1
Successfully installed pip-21.3.1
Collecting click
  Downloading click-8.0.3-py3-none-any.whl (97 kB)
     |████████████████████████████████| 97 kB 9.0 MB/s             
Collecting pylint
  Downloading pylint-2.12.2-py3-none-any.whl (414 kB)
     |████████████████████████████████| 414 kB 21.8 MB/s            
Collecting pytest
  Downloading pytest-6.2.5-py3-none-any.whl (280 kB)
     |████████████████████████████████| 280 kB 22.6 MB/s            
Collecting black
  Downloading black-21.12b0-py3-none-any.whl (156 kB)
     |████████████████████████████████| 156 kB 34.0 MB/s            
Collecting importlib-metadata
  Downloading importlib_metadata-4.10.0-py3-none-any.whl (17 kB)
Collecting mccabe<0.7,>=0.6
  Downloading mccabe-0.6.1-py2.py3-none-any.whl (8.6 kB)
Collecting platformdirs>=2.2.0
  Downloading platformdirs-2.4.1-py3-none-any.whl (14 kB)
Collecting isort<6,>=4.2.5
  Downloading isort-5.10.1-py3-none-any.whl (103 kB)
     |████████████████████████████████| 103 kB 34.0 MB/s            
Collecting typing-extensions>=3.10.0
  Downloading typing_extensions-4.0.1-py3-none-any.whl (22 kB)
Collecting toml>=0.9.2
  Downloading toml-0.10.2-py2.py3-none-any.whl (16 kB)
Collecting astroid<2.10,>=2.9.0
  Downloading astroid-2.9.3-py3-none-any.whl (254 kB)
     |████████████████████████████████| 254 kB 23.8 MB/s            
Collecting packaging
  Downloading packaging-21.3-py3-none-any.whl (40 kB)
     |████████████████████████████████| 40 kB 7.3 MB/s             
Collecting attrs>=19.2.0
  Downloading attrs-21.4.0-py2.py3-none-any.whl (60 kB)
     |████████████████████████████████| 60 kB 9.8 MB/s             
Collecting iniconfig
  Downloading iniconfig-1.1.1-py2.py3-none-any.whl (5.0 kB)
Collecting pluggy<2.0,>=0.12
  Downloading pluggy-1.0.0-py2.py3-none-any.whl (13 kB)
Collecting py>=1.8.2
  Downloading py-1.11.0-py2.py3-none-any.whl (98 kB)
     |████████████████████████████████| 98 kB 8.7 MB/s             
Collecting pathspec<1,>=0.9.0
  Downloading pathspec-0.9.0-py2.py3-none-any.whl (31 kB)
Collecting tomli<2.0.0,>=0.2.6
  Downloading tomli-1.2.3-py3-none-any.whl (12 kB)
Collecting typed-ast>=1.4.2
  Downloading typed_ast-1.5.1-cp37-cp37m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl (843 kB)
     |████████████████████████████████| 843 kB 23.0 MB/s            
Collecting mypy-extensions>=0.4.3
  Downloading mypy_extensions-0.4.3-py2.py3-none-any.whl (4.5 kB)
Collecting lazy-object-proxy>=1.4.0
  Downloading lazy_object_proxy-1.7.1-cp37-cp37m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (57 kB)
     |████████████████████████████████| 57 kB 2.7 MB/s             
Collecting wrapt<1.14,>=1.11
  Downloading wrapt-1.13.3-cp37-cp37m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl (79 kB)
     |████████████████████████████████| 79 kB 12.0 MB/s            
Requirement already satisfied: setuptools>=20.0 in /home/ec2-user/.devops-aws/lib/python3.7/site-packages (from astroid<2.10,>=2.9.0->pylint->-r requirements.txt (line 2)) (47.1.0)
Collecting zipp>=0.5
  Downloading zipp-3.7.0-py3-none-any.whl (5.3 kB)
Collecting pyparsing!=3.0.5,>=2.0.2
  Downloading pyparsing-3.0.6-py3-none-any.whl (97 kB)
     |████████████████████████████████| 97 kB 9.9 MB/s             
Installing collected packages: zipp, typing-extensions, wrapt, typed-ast, pyparsing, lazy-object-proxy, importlib-metadata, tomli, toml, py, pluggy, platformdirs, pathspec, packaging, mypy-extensions, mccabe, isort, iniconfig, click, attrs, astroid, pytest, pylint, black
Successfully installed astroid-2.9.3 attrs-21.4.0 black-21.12b0 click-8.0.3 importlib-metadata-4.10.0 iniconfig-1.1.1 isort-5.10.1 lazy-object-proxy-1.7.1 mccabe-0.6.1 mypy-extensions-0.4.3 packaging-21.3 pathspec-0.9.0 platformdirs-2.4.1 pluggy-1.0.0 py-1.11.0 pylint-2.12.2 pyparsing-3.0.6 pytest-6.2.5 toml-0.10.2 tomli-1.2.3 typed-ast-1.5.1 typing-extensions-4.0.1 wrapt-1.13.3 zipp-3.7.0
