# Database
Install uv on mac

`brew install uv`

`Installed on /opt/homebrew/Cellar/uv/0.4.22`

# Install packages
## pip interface
1. create virtual environment `python3.11 -m venv .venv --prompt <PromptName>`
2. `source .venv/bin/activate`
3. `uv pip install <PACKAGE>`

## uv project
1. `uv init .` to define a uv project
2. `uv add <PACKAGE>`
3. `uv remove <PACKAGE>`


# Setup tables
`python connect.py` to create sqlite db
`python create_tables.py` to create tables