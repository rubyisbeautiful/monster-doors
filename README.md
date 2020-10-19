# TODO

## Environments

dev, cert, prod

## Users

- boo - human
- sully - scarer
- mike - scarer
- waternoose - management
- roz - cda

## Groups

scarers - full access to dev, no access to cert, prod
humans - full access to all
cda - read only access to all
management - read only access to all  

# TODO

- we need at least one instance of closet-door in each environment
    - it has to run door-script.sh on startup
    - we should probably have more than one instance of 
    closet door in a given environment... in case one of them runs out of power

- we need the function "check-doors" to run once an hour
    - we should probably store the function code in a bucket
        - we need a bucket         
