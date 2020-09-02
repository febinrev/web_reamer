# WEB_REAMER

### WEB_REAMER is a handy tool for web pentester and bug hunters! It is capable of extracting endpoints from webpages, finding admin panels from the given URL, Finding parameters, subdomain bruteforce, creating targeted wordlists from the given URL/Webpage ,analyzing word frequencies.

#### Installation:
      git clone https://github.com/febinrev/web_reamer.git
      cd web_reamer/
      python3 -m pip install -r requirements.txt
      chmod +x web_reamer.py
      ./web_reamer.py    # This will give the Usage instructions
      
#### Usage:
    1. Endpoint / Link Extraction:
      ./web_reamer.py -link -u http://sample.com/ 
 
    2. Admin Panel fuzzing:
      ./web_reamer.py -admin -u http://sample.com/ 
 
    3. Subdomain Brute Force:
      ./web_reamer.py -sub -d sample.com -w subdomains.txt 
 
    4. Find hidden parameters from webpage:
      ./web_reamer.py -param -u http://sample.com/ 
 
    5. Create Targetted Wordlist from webpage:
      ./web_reamer.py -wordlist -u http://sample.com/ -o outfile_wordlist.txt 
 
    6. Analyze Word frequencies from the WebPage :
      ./web_reamer.py -analyze -u http://sample.com/ 

    7. Help :
     ./web_reamer.py -h 
      ./web_reamer.py --help 

    8. Version / Update Check :
      ./web_reamer.py -v 
      ./web_reamer.py --version 
![USAGE](https://github.com/febinrev/web_reamer/raw/master/screenshots/web_reamer_usage.png)

Endpoint extraction
![USAGE](https://github.com/febinrev/web_reamer/raw/master/screenshots/wrlink.png)
![USAGE](https://github.com/febinrev/web_reamer/raw/master/screenshots/wrlink2.png)

Subdomain Brute-force
![USAGE](https://github.com/febinrev/web_reamer/raw/master/screenshots/wrsub.png)

parameter enumeration
![USAGE](https://github.com/febinrev/web_reamer/raw/master/screenshots/wrparam.png)

Targeted Wordlist
![USAGE](https://github.com/febinrev/web_reamer/raw/master/screenshots/wrlist.png)

Word Analysis
![USAGE](https://github.com/febinrev/web_reamer/raw/master/screenshots/wranalyze.png)





