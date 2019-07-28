## Usage

Then run the following commands to run php 7:


```
docker run -v $(pwd):/var/www php7.4-cli "php --version"
```

## Commands inside the container

Run:

```
docker run -it $(pwd):/var/www php7.4-cli /bin/sh
```

Then run your commands with `php`.



Based on Geshan Manandhar's docker image.
