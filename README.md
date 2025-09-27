# movie-recommendation-system
This is a movie recommendation web app build on Streamlit.

## Get started

1. Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install dependencies:

```bash
pip install -U pip
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run app.py
```

## Data and large files

- Large model/data binaries (e.g. `similarity.pkl`) are stored with Git LFS. If you clone this repo, install Git LFS first so these files are downloaded automatically:

```bash
# install git-lfs (one-time)
git lfs install
```

- Some pickle files (like `movies.pkl`) are intentionally kept local and not tracked in Git. If you need them, either add them to LFS (recommended) or upload them to external storage and update the app to download them at runtime.

## Notes

- If you see warnings about missing packages in your editor, ensure VS Code (or your editor) is using the `.venv/bin/python` interpreter.
- If you want me to add a small download script or a `requirements.txt` file, tell me and I'll add them.
