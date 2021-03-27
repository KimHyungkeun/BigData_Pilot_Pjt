# 빅데이터 파일럿 프로젝트

- 참고서적 : [실무로 배우는 빅데이터 기술 2nd](https://github.com/wikibook/bigdata2nd)

# 1. 가상머신설정 
* 가상 하둡 클러스터 환경을 제작하기 위한 과정
- Oracle Virtual Box (2대, server01, server02)
- OS : CentOS 6
- RAM : (server01 : 5GB, server02 : 3GB)

# 2. Cloudera Manager 설치 
* Hadoop 서비스를 모니터링하기위한 서비스
- Cloudera Manager 설치 
- CDH 설치 (Cloudera에서 제공하는 Hadoop ecosystem)
- 2020년 10월 이후, 정책의 변경으로 인해 개인적인 제품구매가 불가능하여 글쓴이가 제공하는 가상머신 및 설치방법을 통해 설치

# 3. 빅데이터 수집 
* 데이터 발생을 위한 시뮬레이터를 가동
- Flume
- Kafka

# 4. 빅데이터 적재
* 발생되는 데이터를 저장시킴
- HDFS(Hadoop) 
- Zookeeper : 분산 코디네이터. 분산 환경에서 작동되는 작업들을 감시, 감독한다
- HBase
- Redis

# 5. 빅데이터 탐색 
* 적재된 데이터를 다양한 방면으로 검색
- Hive : 하둡 에코시스템내의 SQL 쿼리엔진
- Spark : In-memory 방식을 통해 느린속도의 MapReduce보다 데이터를 더욱 효율적으로 처리
- Oozie : 워크플로우 지정
- Hue : HDFS 및 쿼리엔진등을 Web UI를 통해 간편하게 다룰 수 있도록 한다

# 6. 빅데이터 분석 
- Impala : Hive 쿼리보다도 더 빠른 실시간 분석을 위한 쿼리엔진. 대용량 배치처리보다는 ad-hoc 쿼리를 통한 빠른 질의결과를 요구한다
- Zeppelin 

# 7. 분석환경 확장 : R을 이용한 데이터 분석 진행


