# wenum

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
python wenum/src/wenum-cli.py -w wordlist.txt -u "https://IP:PORT?parametro=FUZZ" --hc 404
