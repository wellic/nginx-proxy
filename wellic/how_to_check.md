
1. git clone git@github.com:wellic/nginx-proxy.git

2. cd wellic

3. docker-compose -f docker-compose.override.yml up whoami

4. curl -H "Host: whoami.docker" localhost

Helper: https://github.com/wellic/bash_tools/blob/master/bin/sites/vhost_add.sh

