# German open access repositories that have records of a type that may contain software

## Setup

Requires:

- Python3
- Pip3

On `bash`:

```bash
# Create a virtual environment
$> python3 -m venv .venv
# Activate the environment
$> . .venv/bin/activate
# Update pip
$> pip install --upgrade pip
# Install dependencies
$> pip install -r requirements.txt
```

## Run

Requires:

- In the directory root, a file `.env` that contains a [Sherpa](https://v2.sherpa.ac.uk/api/) API key:

```ini
SHERPA_TOKEN=<Your Sherpa API key>
```

On `bash`:

```bash
# Start the Jupyter server locally
jupyter notebook
```

Open the Jupyter interface and run the notebook.
