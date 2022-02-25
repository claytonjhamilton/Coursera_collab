# University of Chicago Group Project - Question 2

## Project set-up

1. Clone repo
2. Execute the following to create and activate your virtual environment:

```python
# Windows computers
mkdir .venv
python -m venv .venv
.venv\Scripts\activate
```

```bash
# Macbook computers
python -m venv --prompt .venv .venv
source .venv/bin/activate
```

3. Install package dependencies:

```bash
pip install -r requirements.txt
```

4. If you need to update/over-write the requirements file:

```bash
pip freeze > requirements.txt
```

## Important

Please do not push the data (csv) to this repository. Coursera asked us to keep this data internal and I will have to delete the repo if data is pushed. Of note, I added the file to the .gitignore so feel free to add to your directory to run the code from.