# Ingress NGINX Controller

nginx 보안 문제가 생기면서  ingress-nginx-controller 의 EOL 문제로 어딘가 패치해서 사용중이잖을까 싶어서 찾아보니 몇군대 있길래 
소스는 공개하지만 자기들 레포에서만 서비스 하길래 소스 가져와서 직접 빌더하여 올렸다.


### Supported Versions table

All images use unified date-based versioning. The version indicates when the software was last maintained.

| Supported | Ingress-NGINX-Controller version | k8s supported version        | Alpine Version | NGINX Version | 
| :-------: | --------------------- | ---------------------------- | -------------- | ------------- |
|    ✅     | **v1.15.7**         | 1.35, 1.34, 1.33, 1.32, 1.31, 1.30 | 3.24.1         | 1.31.2        |
|    🔄     | **v1.15.6**         | 1.35, 1.34, 1.33, 1.32, 1.31, 1.30 | 3.23.4         | 1.31.1        |

 

## 다운로드 위치 

https://hub.docker.com/r/loveis/ingress-nginx-controller 

실제로 k8s 1.30에서 테스트했는데 이전버전도 적용해보면 되잖을까 싶다.

 


 
## License

[Apache License 2.0](https://github.com/kubernetes/ingress-nginx/blob/main/LICENSE)
