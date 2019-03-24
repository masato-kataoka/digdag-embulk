# What is digdag?
See https://www.digdag.io for details.

# What is embulk?
See http://www.embulk.org for details.

# Why are they bundled together?
digdag provides native support to call embulk. Embulk enables data movement in many ETL workloads. This image enables the use of the native embulk support in digdag.

# Start a digdag server instance with an in-memory database
In this mode, digdag removes the data when the server exits. Use this for test purposes only.

    $ docker-compose up

# Stop a digdag server instance with an in-memory database
In this mode, digdag removes the data when the server exits. Use this for test purposes only.

    $ docker-compose stop

# Reference 
- https://hub.docker.com/r/satvidh/digdag-embulk
- https://github.com/satvidh/digdag-embulk-docker
