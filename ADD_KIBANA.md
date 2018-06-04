# add x-pack 

Sau khi cài đặt `docker-compose up`. Thực hiện generate ra password trong container `elastic`

```bash
docker container ls
# tìm và lấy id của elastic

docker exec -it [id] bash

bin/x-pack/setup-passwords interactive

```
