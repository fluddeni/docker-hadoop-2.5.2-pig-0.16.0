Hadoop & Pig
==============================

Docker container to run Pig 0.16.0 with hadoop 2.5.2

This container is based on [SequenceIQ Hadoop-Docker image](https://registry.hub.docker.com/u/sequenceiq/hadoop-docker/) 

# Pull the image

```
docker pull fluddeni/hadoop-pig16
```

# Start a container

In order to use the Docker image use:

```
docker run -i -t fluddeni/hadoop-pig16 /etc/bootstrap.sh -bash
```

# Test Pig

Once the container has started, execute
```
pig -x local
```
