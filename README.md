Go read the full README on jwilder's repo - this adds nothing new apart from the ability to proxy to containers using the `host` network.

## Host proxying

Ensure the container has:
- `VIRTUAL_IP` - this should be the private IP and resolvable by the NGINX container
- `VIRTUAL_PORT` - this should be the port traffic is directed to.

## Does this do X, Y, Z?

Probably not, if the base image doesn't.
