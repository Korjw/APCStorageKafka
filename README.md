# 시작

---

apache kafka 설치(윈도우 기준)

https://kafka.apache.org/downloads
Scala 2.13 버전 설치

---

---

윈도우 cmd

---

저장소 내 zookeeper.properties, server1.properties, server2.properties, server3.properties을 apache kafka config 폴더 내로 이동

1. bin\windows\zookeeper-server-start.bat config\zookeeper.properties 주키퍼 실행
2. bin\windows\kafka-server-start.bat config\server1.properties 카프카 서버 1 실행
3. bin\windows\kafka-server-start.bat config\server2.properties 카프카 서버 2 실행
4. bin\windows\kafka-server-start.bat config\server3.properties 카프카 서버 3 실행

---

windows : kafka.bat 실행
Linux(Ubuntu 22.04 LTS) : start.sh 실행

---

---

localhost 접속

---
