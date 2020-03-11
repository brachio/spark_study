# Spark 공부를 위한 Spark 초기 설정
컨테이너를 날려도 노트북이 날아가지 않고 저장되도록 한다.
해당 도커 이미지는 제가 제작한 것이 아님을 밝힙니다.
Spark The Definitive Guide 한글 번역판의 "부록A 스파크 설치 및 실행"를 통해서 다운받은 도커이미지를 docker-compose로 커스토마이즈 한 것이다.

```bash
# 실행방법
# notebook 경로를 mount하기 때문에, image를 삭제해도 내가 작성하던 zeppelin notebook이 날아가지 않는다.
$> docker-compose up -d
```

# 설정 관련하여 남은 일
현재는 zeppelin 내에 image를 삽입했을 때, 이미지가 날아가버릴것이다.
이미지가 날아가지 않도록 하려면 이미지도 마운트하여야 한다.
