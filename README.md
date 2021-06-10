```bash
#!/bin/bash

apt -y update
apt -y install nginx
git clone https://github.com/MasonEgger/do-scuba-school-session1.git
cp do-scuba-school-session1/* /var/www/html
```
