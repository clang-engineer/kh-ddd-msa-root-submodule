# submodule project를 모두 내려받고 싶다면? 

```
$ git clone --recurse-submodules git@github.com:hhkbdev/jh-gateway.git
```


# submodule project을 구성한 과정
 
## gateway 

```
$ git submodule add git@github.com:hhkbdev/jh-gateway.git gateway
```

## book service

```
$ git submodule add git@github.com:hhkbdev/jh-book.git book
```


## rental service

```
$ git submodule add git@github.com:hhkbdev/kh-rental.git rental
```


