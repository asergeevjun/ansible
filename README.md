git clone git@github.com:asergeevjun/ansible.git \
cd ansible/ \
_PY_VER=3.10 \
sudo apt install python${_PY_VER} python${_PY_VER}-venv python${_PY_VER}-dev \
python -mvenv .venv \
source .venv/bin/activate \
pip install wheel \
pip install -r requirements.txt
