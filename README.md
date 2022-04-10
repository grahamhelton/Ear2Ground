# Installation
## Make sure you're running python version 3.10!
Installing python3.10
```bash
sudo apt install software-properties-common -y
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update -y
sudo apt upgrade -y
sudo apt install python3.10
sudo apt install pip3
python3.10 --version
```

## Installing dependencies
```bash
pip install -r requirements.txt
```

# Usage
## 
Simply run `python3.10 e2g.py`
![e2g running](./e2gExample.png)
Job postings are stored in `./data/{company_name}`

The first time you run the program it will return all the job postings. After it has built the initial list of postings it will only return new job postings.
