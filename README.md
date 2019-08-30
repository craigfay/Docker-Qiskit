# Commands
`docker pull continuumio/anaconda3`
`docker run -i -t -p 8888:8888 -v 'tutorials:/tutorials/' continuumio/anaconda3 /bin/bash`
docker run -i -t -p 8888:8888 -v `pwd`tutorials:/tutorials continuumio/anaconda3 /bin/bash
`pip install Qiskit`
`cd tutorials`
`jupyter notebook --ip='0.0.0.0' --port=8888 --allow-root`

