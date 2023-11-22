# Vector - Python SDK

This is a fork of a fork of the original Anki Vector Python SDK. 
Extremely unofficial and it's just to keep my Vector alive according to my taste. 

## Quick install

```sh
git clone git@github.com:kingardor/vector-python-sdk.git

git submodule update --init --recursive

pip3 install -r requirements.txt

python setup.py install

pip3 uninstall protobuf

pip3 install protobuf==3.20
```