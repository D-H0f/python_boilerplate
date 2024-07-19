This adds my preferred python boilerplate clode and logging config to whatever directory it's cloned into.
Make sure you're in the directory you want to populate, then copy/paste this into your terminal:
```bash
git clone https://github.com/D-H0f/python_boilerplate . &&\
rm -rf ./.git ./README.md &&\
python3 ./main.py
```
If you want to use this as a quick terminal command, add the following to your .bashrc:
```bash
alias populate-python-boilerplate='git clone https://github.com/D-H0f/python_boilerplate . && rm -rf ./.git ./README.md && python3 ./main.py'
```
