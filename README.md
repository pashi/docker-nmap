Run docker
----------

docker run -i --rm -t pashi/nmap /usr/bin/nmap -sV --version-light --script ssl-poodle -p 443 www.example.com
