# Setup & Installation for 6.S191 Labs

1. Make sure you have python 2.7 installed.

To check run:
`python --version`
It should return `Python 2.7.X`
Otherwise, download python 2.7 from: https://www.python.org/downloads/

2. Please copy the following commands to your bash terminal:

## Pip Instructions
If you are using pip:
```
git clone https://github.com/yala/introdeeplearning;
cd introdeeplearning;
pip install virtualenv;
virtualenv intro_dl --python=python2.7;
source intro_dl/bin/activate;
pip install --upgrade pip;
source intro_dl/bin/activate
pip install tensorflow;
pip install word2vec;
pip install jupyter;
echo 'done'
```

## Conda Instructions
Copy + Paste the following into your terminal
```
conda create -n intro_dl python=2.7;
source activate intro_dl;
conda install tensorflow;
pip install word2vec;
conda install jupyter;
echo 'done'
```

3. 

## To test that your installation worked:
```
git clone https://github.com/nicholaslocascio/intro-deeplearning-setup
cd intro-deeplearning-setup
jupyter notebook
```


FAQ:

1. What's virtualenv?
http://docs.python-guide.org/en/latest/dev/virtualenvs/
We are using virtualenv to manage all the python dependencies to make installation easier for everyone.

2. It worked, but then i restarted my computer and it stopped working. Make sure you re-activate your pip or conda virtual environment. For pip: `source intro_dl/bin/activate`, for conda `source activate intro_dl`.

3. Anything else - ask on Piazza!

