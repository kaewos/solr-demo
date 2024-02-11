Demo localhost solr with docker, running on port 8983

Not for prod use, uses python's test server and hasn't been reviewed for security.

Fun to play with though.

---

1) setting up the docker image should kick off a pip install, but you need `flask` and `simplejson` if I'm wrong about that

2) Build the docker image `docker build -t flask-app:latest .`

3) kick it up with docker-compose
