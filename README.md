# spring_actuator
spring actuator 세팅을 위한 도커파일

🚨 현재 폴더 하위 grafana 폴더 생성 후 진행

- 프로메테우스 설정파일에서 actuator 대상 확인 후 실행
- 서버 docker-compose 에 추가할 경우 prometheus 서비스에 depends_on 추가
- docker-compose down [service] 를 실행하면 특정 서비스만 내릴 수 있다.

```
docker compose up -d
```