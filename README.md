## FF-GUEST-ACCOUNT-GENERATOR

**TERMUX RUN COMMAND** 
```
pkg update && pkg upgrade -y
pkg install python python-pip unzip -y
termux-setup-storage
cd /sdcard
unzip FF-GUEST-ACCOUNT-GENERATOR.zip
pip install requests flask colorama
pip install pycryptodome
python app.py
```
