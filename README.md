# Install all dependencies

pip install -r requirements.txt

# Runs all servers before execute requests

# Servers folder

python3 nameFileServer.py

# Runs load balancer

# Src folder

python3 -m uvicorn src.main:app --reload
