pkg update && pkg upgrade -y
pkg install git python -y
git clone https://github.com/somrat3376-sys/SCL.git
cd SCL
python -m pip install -r requirements.txt
python main.py
