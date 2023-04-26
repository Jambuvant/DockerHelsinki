from ubuntu:20.04
workdir /app
copy curl_search.sh .
run chmod +x curl_search.sh
run apt-get update && run apt install curl
cmd ./curl_search.sh
# after entering docker by using following command apt-get update ran successfully
# $ docker exec -it --net=host bash
