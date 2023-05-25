# tryOpenCalm
```zsh
# Start up
$ docker compose up -d --build

# Check created image and container
$ docker image ls
$ docker container ls

# Access container('python3' is container name)
$ docker compose exec python3 bash

# If didn't install below lib
bash> pip install transformers accelerate

# Run
bash> python main.py
```
