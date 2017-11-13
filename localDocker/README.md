# local docker

## build
``
    $ docker build -t raiden .
``

## run

    $ docker run -it -v {$LocalKeyStorePath}:/blockchain/parityStore  -p 5002:80 raiden bash
    
    $ echo {$YourAddressPassword} >> pass
    
    $ nginx
    
    $ pm2 start raiden_pm2.json
    
    $ pm2 logs
    

> raiden will run in 5002 port 

