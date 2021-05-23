# ml-fluent

# Install anaconda
https://www.anaconda.com/products/individual

## Install elasticsearch plugin for jupyter/python
conda install elasticsearch -y

# Install EFK
docker-compose up

# Install fluent-bit on raspberry pi
git clone https://github.com/fluent/fluent-bit.git
cd fluent-bit/build
cmake ..

# References
https://docs.fluentd.org/container-deployment/docker-compose
