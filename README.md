# Ear 2 Ground
Ear2Ground is a python project that I created to show you new job postings from security websites (or really any site). The idea behind this is not to scrape every *site*, but to provide a framework you can modify for the company's *you're* interested in. This tool comes pre-configured to look at [Dragos](https://www.dragos.com/) and [Scythe](https://www.scythe.io) but the real power is adding your own sites! Unfortunetly this is hard to without looking at the code for each site but I've written e2g to be fairly modular and only require a few code changes to add your own. 

![e2g](https://user-images.githubusercontent.com/19278569/166077092-19dd1812-293d-4f03-a972-5467406dab0a.gif)

# Motivation
I decided to create this more as a project to help me work on my python and also give back to the community. If you find this helpful, consider adding new reputable security companies! 

## Installing ear2ground
> Make sure you're running python version 3.10!!!
```bash
python3 --version #Ensure you're running python 3.10
git clone https://github.com/grahamhelton/Ear2Ground
cd Ear2Ground
pip3 install BeautifulSoup4
python3 e2g.py # Did I mention to make sure you're on python 3.10?
```

# Usage
## 
Simply run `python3.10 e2g.py`
![e2g running](./e2gExample.png)
Job postings are stored in `./data/{company_name}`

The first time you run the program it will return all the job postings. After it has built the initial list of postings it will only return new job postings. So if you run it every monday, it will return the job postings from the previous week. 
