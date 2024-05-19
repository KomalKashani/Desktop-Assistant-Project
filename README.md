## Desktop-Assistant-Project

1. Create a new virtual environment (for streamlit we need python 3.10)

```bash
conda create -n assistant1 python=3.10
```

2. Checkout the created virtual environment

```bash
conda env list
```

3. Activate the virtual environment

```bash
conda activate assistant1 
```

4. Install all the packages present in the requirements file

```bash
pip install -r requirements.txt
```

5. To run the desktop application which is created using python libraries

```bash
python main.py
```

6.To run the desktop application which is created using gpt api

```bash
streamlit run app.py
```
## Required Github Commands
git add .

git commit -m "message"

git push origin main
