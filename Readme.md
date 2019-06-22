### PHP/MYSQL Docker Starter 

This compatible with CPANEL version and good to work with.


Mysqli installing

$ docker exec -it <phpcontainerid> bash  
inside the docker container bash terminal

# docker-php-ext-enable mysqli
if mysqli is not installed which you will come to know from the output of above command

# docker-php-ext-install mysqli
then i commited this change so the same image

$ docker commit -p <phpcontainerid> <new or same image name>

extension=php_mysqli.dll