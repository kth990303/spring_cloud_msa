## Zuul Service
- netflix.zuul 은 spring boot 2.3.x 버전까지만 사용 가능하다.
- spring boot 2.4.x 버전부터는 비동기로 사용 가능한 `spring cloud gateway`를 사용한다.
  - netflix.zuul 또한 리뉴얼 버전부터는 비동기 사용이 가능하지만, 해당 버전 역시 deprecated 되었다. 

### Architecture
![img.png](architecture.png)
![img_1.png](eureka_server.png)
