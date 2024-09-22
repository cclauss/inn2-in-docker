# inn2-in-docker
Run InterNetNews v2 (inn2) in Docker
* [inn2 documentation](https://www.isc.org/othersoftware/#INN)
* [inn2 repo](https://github.com/InterNetNews/inn)
* https://defuse.ca/inn-private-newsgroup-server-setup.htm
* https://www.eyrie.org/~eagle/software/inn/docs-2.7

---
```yaml
    services:
      inn-service:
        image: greenbender/inn
        ports:
          - 119:119
```
* https://github.com/greenbender/inn
* https://hub.docker.com/r/greenbender/inn
