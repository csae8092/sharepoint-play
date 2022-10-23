# sharepoint-play

download excel file from sharepoint, read it into pandas dataframe and save it as csv

## install

* clone the repo
* create virtual env and install requirmentes with e.g. `pip install -r requirements.txt`
* create a file called `.secret` and add your sharepoint credentials as sketched below

```
SP_USER=firstname.lastname@oeaw.ac.at
SP_PW=verysecret
```
* run `./export_env_variables.sh`
* adapt `download_files.py` to your needs, e.g. adapt `FILE_URL`