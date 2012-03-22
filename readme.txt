The "_ssl.pyd" file in this folder was taken from the ActivePython Community Edition of Python,
available at: http://www.activestate.com/activepython/downloads. Without this file, the embedded
version of DocsFlow fails the first login attempt with an error:

    [Errno 8] _ssl.c:503: EOF occurred in violation of protocol

First install using the python installer in this folder, and then replace the "_ssl.pyd" file,
located at: <Install Location>\Python27\DLLs
