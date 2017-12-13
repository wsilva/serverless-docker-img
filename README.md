# What

Serverless Framework.


# Install

~~~bash
echo "alias serverless='docker run -ti --rm --volume $HOME/.aws:/root/.aws --volume $PWD:/app wfsilva/serverless'" | tee -a ~/.bash_profile
source ~/.bash_profile
~~~


# Running

Since we are using a Docker image and using volumes we must run where your files are. It is not possible to navigate back on your OS like `cd ../../../`

~~~bash
cd /path/where/your/project/is/
serverless --help
~~~
