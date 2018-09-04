# To setup our Python / Jupyter environment in the linux lab systems at Michigan Tech,
1. Open a terminal and navigate to a directory where you'd like the repository to be stored.
2. clone this git repository
```shell
  git clone https://github.com/ongbw/UN5550-Fall2018.git
```
3. Enter into the git repository
```shell
  cd UN5550-Fall2018
```
4. Install the python libraries that will be needed in this class
```shell
  pip install --user -r python_deps.txt
```
5.Upgrade built-in version of numpy
```shell
  pip install --user --upgrade numpy
  pip install --user --upgrade matplotlib
```
6. Setup your environment variable
```shell
  source setup_python_mtu.sh
```
7. You will need to close your terminal window and open a new window in order run
the jupyter notebook
```shell
  jupyter notebook
```

# Setup Python / Jupyter on your local system
The easiest way to get the computing platform that you need is to install
[Anaconda](https://www.anaconda.com/download/)
