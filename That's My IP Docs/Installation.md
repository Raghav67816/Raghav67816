## Development Environment

This API uses Python 3 packages listed in requirements.txt located in config directory of the project.
Using virtual environment is recommended. It also uses IP2Location LITE Database downloadable from [IP2Location LITE Database 11](https://bit.ly/3S1ilvG) and MongoDB.

NOTE: You have to download D11 database. I have not included it here because of it's big size. However, after installing move that BIN file namely IP2LOCATION-LITE-DB11.IPV6.BIN to config directory.

## Setup

Clone this repository

```bash
    git clone https://github.com/Raghav67816/that-s-my-ip-api
    cd <repo-folder>
```

Now create virtual environment - Recommended. However, you can skip this step.

```bash
    pip install virtualenv
    virtualenv <env-name>
    pip install -r config\requirements.txt
```

For setting up MongoDB visit [That's My IP API](https://youtube.com)

Environment is ready now !
## Run Locally

Now our environment is ready, we can now run this API locally.
```bash
    cd <repo-folder>
    source <env-name>/Scripts/activate
    uvicorn api:app --reload
```

Congratulations ! Our local server is now running at localhost. Now, open your browser and open the url provided in the terminal.