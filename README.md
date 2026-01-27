# cursor_demo

## Setup Instructions

### Step 1: Create a Virtual Environment

Create a Python virtual environment:

```bash
python3 -m venv venv
```

### Step 2: Configure pip

Activate the virtual environment and move the `pip.conf` file into the `venv` folder:

```bash
source venv/bin/activate  # On Windows: venv\Scripts\activate
cp pip.conf venv/pip.conf
```

Edit `venv/pip.conf` and fill in your username and password:

```
[global]
extra-index-url=https://<USERNAME>:<PASSWORD>@training-eu.vaultspeed.com/api/artifacts/pip/vaultspeed-sdk/simple
```

Replace `<USERNAME>` and `<PASSWORD>` with your actual credentials.

### Step 3: Install Requirements

Install the required packages from `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Step 4: Install openspec

Install openspec into the repository:

```bash
npm install -g @fission-ai/openspec@latest
```

```bash
openspec init
```

```bash
/opsx:new <what-you-want-to-build>
```

https://github.com/Fission-AI/OpenSpec

