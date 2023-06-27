# submodule project를 모두 내려받고 싶다면? 

```
$ git clone --recurse-submodules https://github.com/hhkbdev/jh-root-submodule.git
```

# submodule project을 구성한 과정
 
## gateway service

```
$ git submodule add https://github.com/hhkbdev/jh-gateway.git gateway
```

## book service

```
$ git submodule add https://github.com/hhkbdev/jh-book.git book
```


## rental service

```
$ git submodule add https://github.com/hhkbdev/kh-rental.git rental
```


