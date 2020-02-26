---
title: 'Autonomous Database'
output: 
  html_document: 
    code_folding: none
    df_print: paged
    keep_md: true
    toc: yes
    toc_depth: 5
    toc_float: true
---

---

## 소개

---

<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/ZtK4_0ZEfTY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>

---

오늘 날 다양한 산업과 업무 분야에 인공 지능을 기반으로 하는 플랫폼, 애플리케이션 및 툴들이 빠른 속도로 등장하고 발전하고 있습니다. 오라클 Autonomous Database는 오라클이 세계 최초로 머신 러닝과 AI 기술을 데이터베이스 플랫폼에 적용함으로써 탄생한 클라우드 데이터베이스 서비스입니다. 

![](ADB.png)

- 오라클Autonomous DB가 구현한 자동화는 하드웨어 인프라 단의 자동화, 데이터베이스 소프트웨어 단의 자동화, 그리고 데이터 센터 운영 단의 자동화로 구성되어 있으며, 모든 레이어에 걸쳐 최신의 머신 러닝 기법이 적용되었습니다. 
- 오라클 Autonomous DB는 급격하고 이질적인 도약이 아니라, 오라클 9i 출시 이래 20 여년에 걸쳐 일관된 목표를 가지고 지속적으로 발전되어 온 오라클 자동화 기술의 정점에 서 있는 데이터베이스 서비스입니다.
- 이와 같은 자율 운영의 제 1 목표는 IT 관리자 또는 데이터베이스 관리자 (DBA)에 의해 전통적으로 수행되어 왔던 일상적인 관리 작업에 드는 노력을 최대한 제거하여 기업의 역량을 **운영이 아닌 혁신**에 집중할 수 있도록 돕는 것입니다.

## Hands-On

---

#### Autonomous Data Warehouse 

- [인스턴스 프로비저닝하기](https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/tutorial-getting-started-autonomous-db-adw/index.html)
- [SQL Developer 접속하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/adwc/obe_connecting_sql_developer_to_autonomous_data_warehouse_and_creating_tables/connecting_sql_dev_to_adw_and_creating_tables.html)
- [데이터 로딩하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/adwc/OBE_Loading%20Your%20Data/loading_your_data.html)
- [샘플 데이터 조회하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/adwc/OBE_Running%20a%20Query%20on%20Sample%20Data/running_a_query_on_sample_data.html)
- [데이터베이스 Cloning하기](https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/tutorial-clone-autonomous-db/)

#### Autonomous Transaction Processing 

- [인스턴스 프로비저닝하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide100ProvisionAnATPDatabase.md)
- [SQL Developer 접속하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide200SecureConnectivityAndDataAccess.md)
- [인스턴스 확장하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide300ScaleAnATP.md)
- [데이터 로딩하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide400DataLoadingIntoATP.md)
- [Node.js 어플리케이션 구성하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide500Configurenode.jsAppWithATP.md)
- [Java 어플리케이션 구성하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide600ConfigureJavaAppWithATP.md)
- [Autonomous Transaction Processing에서 JDBC와 SpringBoot 프레임워크 사용하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/db/java/atp_jdbc_springboot/atp_springboot.html)
- [REST API 사용하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide700WorkingWithRESTAPIs.md)
- [Microservice 구축하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide800BuildingMicroservicesOnATP.md)
- [OCI-CLI 구성하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide900ConfigureOCI-CLI.md)
- [DevOps 마스터하기](https://oracle.github.io/learning-library/workshops/autonomous-transaction-processing/?page=LabGuide1000AppDev.md)

#### Oracle Machine Learning 인터페이스

- [프로젝트와 워크스페이스 생성하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/oml/OMLPW-create-project-workspace/html/index.html)
- [노트북을 생성하고 실행하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/oml/OMLCR-create-run-notebooks/html/index.html)
- [협업 기능 사용하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/oml/OMLNB-collaborate-use-notebooks/html/index.html)
- [SQL 스크립트 생성하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/oml/OMLCQ-create-sql-scripts/html/index.html)
- [SQL 문장 실행하기](https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/oml/OMLRS-run-sql-statements/html/index.html)

## 참고 자료

---

- 공식 매뉴얼
    - [Autonomous Data Warehouse](https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/)
    - [Autonomous Transaction Processing](https://docs.oracle.com/en/cloud/paas/atp-cloud/index.html)
- White Papaper 
    - [Oracle Autonomous Database Technical Overview](https://www.oracle.com/a/ocom/docs/database/oracle-autonomous-database-technical-overview.pdf)
    - [Oracle Autonomous Database Strategy](https://www.oracle.com/a/ocom/docs/database/oracle-autonomous-database-strategy-wp.pdf)
    - [Oracle Autonomous Database: The Industry's First Self Securing Database](https://www.oracle.com/a/ocom/docs/database/autonomous-database-self-securing-wp.pdf)
    - [Oracle Autonomous Database: The Industry's First Self Repairing  Database](http://www.oracle.com/us/products/database/autonomous-database-self-repairing-5116047.pdf)
- 기타
    - Cloud Essentials: [Run Critical Databases in the Cloud](http://www.oracle.com/us/solutions/cloud-essentials-data-mgmt-3901529.pdf)
    - Infographic: [Discover new roads with an autonomous database](https://www.oracle.com/a/ocom/docs/cloud/do-more-with-oci-adb-Infographic.pdf)
