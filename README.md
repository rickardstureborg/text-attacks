# text-attacks
Code to attack NLP models using perturbations (for a course project on ML in Adversarial Settings)

# Virtual Env
To create a virtualenv from the requirements.txt:
```
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```
Then, to add the environment as ipynb kernel:
`ipython kernel install --user --name=text-attacks`

To update the requirements.txt:
`pip freeze > requirements.txt`
