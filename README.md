# To create secret
 kubectl create secret docker-registry privatekey --docker-server=docker.io --docker-username=subhash1010 --docker-password=password --docker-email=subhashsingh307
 #after place the secret in yaml file, then run the 
 kubectl apply -f apche-private.yml
