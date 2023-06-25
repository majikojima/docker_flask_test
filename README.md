reference

[https://gray-code.com/blog/flask-on-docker/]

**contents**

- [Usage](#usage)

## Usage

```bash
$ docker image build -t flask .

$ docker run -p 5000:80 -v ${PWD}/app:/app -d flask
```

URL access:

```url
localhost:5000
```

```bash
$ docker image ls

$ docker stop containerID
```