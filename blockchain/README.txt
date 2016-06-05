--Steps to install pythereum on mac--

1.) Clone the repository - https://github.com/ethereum/pyethereum.git
2.) Run git submodule init and then git submodule update
3.) Install the osX dependencies - brew install pkg-config libffi autoconf automake libtool openssl
4.) Run - python setup.py install
5.) Install all the dependencies in requirements.txt and dev-requirements.txt using, pip install -r <requirements file>
6.) Check if the build is successful by running py.test in ethereum/tests
