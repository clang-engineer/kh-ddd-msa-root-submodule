# submodule project를 모두 내려받고 싶다면? 

```sh
git clone --recurse-submodules https://github.com/clang-engineer/kh-ddd-msa-root-submodule.git
```

# submodule project을 구성한 과정
 
## gateway service

```sh
git submodule add https://github.com/clang-engineer/kh-gateway.git gateway
```

## book service

```sh
git submodule add https://github.com/clang-engineer/kh-book.git book
```

## book-catalog service

```sh
git submodule add https://github.com/clang-engineer/kh-book-catalog.git book-catalog
```


## rental service

```sh
git submodule add https://github.com/clang-engineer/kh-rental.git rental
```


