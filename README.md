
# Skinalyze

Skin lesion detection app, based on CNN model trained on MSLD v2.0 dataset for detecting: Monkeypox, Chickenpox, Cowpox, HFMD, Measles and healthy.


## Dependencies 

- tensorflow==2.13.0
- numpy==1.24.3
- cohere==4.19.2
- streamlit==1.24.1
## Getting started

Getting started with cloning the repository:

```bash
git clone https://github.com/guy-977/Skinalyze
cd Skinalyze
```

install dependencies via pip:

```bash
pip install -r requirements.txt
```
Add your cohere API key to secrets file:
```
mkdir .streamlit
echo "COHERE_API_KEY = "Your Actual API key"" > .streamlit/secrets.toml
```

run the streamlit app:

```bash
streamlit run main.py
```
    
## Author

- [@guy-977](https://github.com/guy-977)

 
