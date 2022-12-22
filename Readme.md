```
 3310  aws cloudformation create-stack --stack-name sbcntr-base --template-body file://network_step1.yml
 3314  aws cloudformation describe-stack-events sbcntr-base
 3318  aws cloudformation describe-stack-events --stack-name sbcntr-base
```
