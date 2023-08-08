# HQU News Crawler

> Powered by **flask**

### Preview

Click [here](https://hdxw.kancy.life/) to visit the page deployed by github action.

### Installation

1. Clone this repo
    ```bash
    git clone https://github.com/sunflower2333/HQUNewsCrawler.git
    cd HQUNewsCrawler
    ```
2. Install needed pip packages.
   ```bash
       # Create Venv firstly
       python -m venv .venv
       . .venv/bin/activate
       # Install flash via pip
       pip install --upgrade -r pip-requirements.txt
   ```

3. Run this app.
   ```bash
      python -m flash --app crawler.py run
   ```
4. Open Web Browser and check this link.  
   - *you may need to insure port 5000 is not occupied by other apps.*
   ```bash
   http://localhost:5000
   ```

