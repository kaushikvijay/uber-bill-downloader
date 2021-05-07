# Uber-Receipts
    Python script to download the uber receipts

# Prepare
    Go to your source dir
    mkdir receipts temp

    python3 -m pip install --user --upgrade pip
    python3 -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt

# Modify file downloader.py
    result, data  = conn.search(None, 'SINCE 1-JAN-2021 FROM "uber.com" SUBJECT "trip"')
    Here password needs to be API password from Gmail(you can also hardcode it here)    
    password = input("Your password: ")


# Run
    python3 downloader.py

