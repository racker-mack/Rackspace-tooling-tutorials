###FAWS notes ###
3/18/2020

V.1

##FAWS##

jose9615

#login to passport
passport auth login --racker

#Create access request with faws

faws passport create-access-request -r 978328 -a 368554665132 -R us-east-2


faws env -r 978328 -a 445613135036

##set alias:

<xxxx=yyy>

##then in CLI use:

$xxx



#### list stacks with AWS CLI

aws cloudformation list-stacks --region ap-northeast-1


##Set faws env:

faws env -r 1277637 -a 445613135036

## Set values for CLI ##

eval "$(faws -r 1277637 env -a 985828831524)"


Rackspace Account ID: 1277637
AWS Account:          985828831524

eval "$(faws -r 978328 env -a 368554665132)"
 -r 978328 -a 368554665132


faws passport list-servers -R us-east-2  -r 978328 -a 368554665132

Passport connect <id of server>

