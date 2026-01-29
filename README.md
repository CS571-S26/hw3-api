build
```bash
docker build . -t ctnelson1997/cs571-s26-hw3-api
docker push ctnelson1997/cs571-s26-hw3-api
```

run
```bash
docker pull ctnelson1997/cs571-s26-hw3-api
docker run --name=cs571_s26_hw3_api -d --restart=always -p 58103:58103 -v /cs571/s26/hw3:/cs571 ctnelson1997/cs571-s26-hw3-api
```