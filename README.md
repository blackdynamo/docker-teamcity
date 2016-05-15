# docker-teamcity

To run:

`docker run -d -v <Teamcity Volume>:/var/lib/teamcity -v /var/run/docker.sock:/var/run/docker.sock -p 8111:8111 relincd/teamcity`
