from golang:1.16

# set working dir
workdir /mybackend

# set env variables
ENV PORT=8080

# this wasn't told in 1.12, but in 1.13 readme
ENV REQUEST_ORIGIN=https://example.com  

# copy source code
copy . .

# build project
run go build

# test project
run test ./...

# execute the project
cmd ["./server"] 
