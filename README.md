# GraphiteClient
Docker image for graphite client for monitoring of dockers and system

docker run -i  -e EP_HOST=graphite.host -e EP_PORT=graphiteport -e ENV=PREFIX -e NODE=HOSTNAME -v /proc:/host_proc:ro -v /var/run/docker.sock:/var/run/docker.sock:ro dockerstat


