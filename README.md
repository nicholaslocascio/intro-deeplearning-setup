# Setup & Installation for 6.S191 Labs

# 1. Make sure you have python 2.7 or 3.3 installed.

To check run:
`python --version`
It should return `Python 2.7.X` or `Python 3.3.X`
Otherwise, download python from: https://www.python.org/downloads/

# 2. Please copy the following commands to your bash terminal (either pip or conda):

## Pip Instructions
If you are using pip:
```
pip install virtualenv;
virtualenv intro_dl;
source intro_dl/bin/activate;
pip install --upgrade pip;
source intro_dl/bin/activate
pip install tensorflow;
pip install gensim;
pip install jupyter;
echo 'done'
```

## Conda Instructions
Copy + Paste the following into your terminal
```
conda create -n intro_dl;
source activate intro_dl;
conda install tensorflow;
pip install gensim;
conda install jupyter;
echo 'done'
```

# 3. Test that the Installation worked

## To test that your installation worked:
```
git clone https://github.com/nicholaslocascio/intro-deeplearning-setup
cd intro-deeplearning-setup
jupyter notebook
```

Open `test_script.ipynb` in the jupyter notebook. Then run the top block in the jupyter notebook (you can run with the little right-arrow button). If no errors, congrats you're all setup! Otherwise check out the FAQ or post on Piazza.


FAQ:

1. What's virtualenv?
http://docs.python-guide.org/en/latest/dev/virtualenvs/
We are using virtualenv to manage all the python dependencies to make installation easier for everyone.

2. It worked, but then i restarted my computer and it stopped working. Make sure you re-activate your pip or conda virtual environment. For pip: `source intro_dl/bin/activate`, for conda `source activate intro_dl`.

3. Anything else - ask on Piazza!

