# pocdriver

- Start the pocdriver container

```
docker run -itd --name pocdriver invazn/pocdriver
```

- Login to the shell of the container

```
docker exec -it pocdriver /bin/sh
```

- Start a test

```
java -jar POCDriver.jar -k 20 -i 10 -u 10 -b 20 -t 10 --host "<mongoURI>"
```

Note: check https://github.com/johnlpage/POCDriver for more options
