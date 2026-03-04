## Running

```sh
# Install uv
curl -LsSf https://astral.sh/uv/install.sh | sh

# Create the venv and activate it
uv venv 
source .venv/bin/activate

# Install this repo.
uv pip install -e .

# Add your API keys and edit PROMPT.md with your goal.
echo "HL_SECRET_KEY=f1...." >> .env
# Edit PROMPT.md — put your goal under the "## Goal" heading.

# Run the agent.
python3 agent.py
```
