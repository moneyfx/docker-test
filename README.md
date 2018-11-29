# docker-test 

set your git
`git config --global core.autocrlf false`
or
`git config --global core.autocrlf input`

clone this repository:
`git clone git@github.com:moneyfx/docker-test.git`

build the image:
`docker build -t docker-test .`

run a container:
`docker run --rm docker-test`
