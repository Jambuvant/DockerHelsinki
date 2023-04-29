from node:16

# expose port
expose 5000

workdir /myfrontend

copy . .
run npm install 

# build static files
run npm run build

# serving static files
run npm install -g serve

# start app on port 5000
cmd ["serve","-s", "-l", "5000", "build"]
