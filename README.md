# SVD

An implementation of the greedy algorithm for SVD, using the power method for the 1-dimensional case.

# Setup

Run the following to set up all the requirements needed to run the code in this repository.

```
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
$ bash setup.sh   # downloads relevant NLP corpora from nltk
```

Then run `python3 topicmodel.py` for the main topic-model routine, `svd.py` for the core svd algorithm, and `demo.py` for the numpy examples from the post.

When finished, run `$ deactivate` to exit the virtual environment.
