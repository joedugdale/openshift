# openshift
instructions
https://medium.com/@danmartines/how-to-setup-openshift-on-aws-ec2-d764bca28c8e

wget https://github.com/openshift/origin/releases/download/v3.6.0/openshift-origin-client-tools-v3.6.0-c4dd4cf-linux-64bit.tar.gz

untar and cd into dir

sudo cp oc /usr/local/bin/
 oc cluster up --routing-suffix=54.174.253.180.nip.io --public-hostname=ec2-54-174-253-180.compute-1.amazonaws.com
