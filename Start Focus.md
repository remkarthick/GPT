
```
git clone https://github.com/lllyasviel/Fooocus.git
cd Fooocus
python3 -m venv fooocus_env
source fooocus_env/bin/activate
pip install -r requirements_versions.txt
```
```
cd /opt/fooocus/Fooocus/
source fooocus_env/bin/activate
python entry_with_update.py --always-cpu
```
Or, if you want to open a remote port, use

source fooocus_env/bin/activate
python entry_with_update.py --listen
