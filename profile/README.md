<br>

#  데이터로 보는 서울 <img src="./assets/seoul_mas.png" align=left width=90>

> 서울시 공공 API 기반 실시간 데이터 수집 및 AWS 기반 데이터 파이프라인·대시보드 구축  &nbsp;&nbsp; • <b>Data Engineering</b>



<div align=center>

  
<br />

[<img src="https://img.shields.io/badge/프로젝트 기간-2025.07.01~2025.07.28-green?style=flat&logo=&logoColor=white" />]()

<!--
<details align="left">
  <summary>목차</summary>
  <ol>
    <li><a href="#프로젝트 소개">프로젝트 소개</a></li>
    <li><a href="#팀원 소개">팀원 소개</a></li>
    <li><a href="#사용 기술">사용 기술</a></li>
    <li><a href="#아키텍처">아키텍처</a></li>
    <li><a href="#결과">결과</a></li>
  </ol>
</details>
--> 
<br><br>

## 📌 Project Overview
> 서울 열린데이터 광장의 실시간 도시데이터 API를 활용하여 날씨, 상권, 인구, 교통, 문화행사 데이터를 통합 수집하고,  
> AWS 기반 데이터 파이프라인과 인터랙티브 대시보드를 구축하는 프로젝트입니다.


<br><br>


## 👥 Contributors

| 서정원 | 이승아 | 정동영 🤴🏻 | 조원서 | 최현욱 |
|:--:|:--:|:--:|:--:|:--:|
| [@pjy05079](https://github.com/pjy05079) | [@eelb07](https://github.com/eelb07) | [@Dong-yeong0](https://github.com/Dong-yeong0) | [@chowonseo](https://github.com/chowonseo) | [@CHU4694](https://github.com/CHU4694) |


<br><br>


## 🧱 Architecture

<img src="./assets/architecture.png" width="500" />


<br><br>


## 🛠 Tech Stack 

| Category | Tools |
|----------|-------|
| **Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Data Pipeline / ETL** | ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white) ![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=aws-lambda&logoColor=white) ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white) |
| **Cloud / Infra** | ![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazons3&logoColor=white) ![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat&logo=amazonredshift&logoColor=white) ![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat&logo=amazonrds&logoColor=white) ![ElastiCache](https://img.shields.io/badge/ElastiCache-FF9900?style=flat&logo=amazondynamodb&logoColor=white) |
| **Visualization / Monitoring** | ![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat&logo=metabase&logoColor=white) ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat&logo=amazoncloudwatch&logoColor=white) |
| **Communication / Collab** | ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000?style=flat&logo=notion&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) |


<br><br>


## 📊 Dashboard



<table style="min-width: 100%; max-width: 830px; border-collapse: collapse; margin: 0 auto;">

  <!-- 실시간 탭 -->
  <tr>
    <td align="center" valign="top" style="padding: 20px;">
      <img src="./assets/tab1.gif"  alt="실시간 탭 이미지" /><br><br>
      <p style="max-width: 600px; margin: 0 auto;">
        <strong>✅ 실시간</strong><br><br>
        실시간 탭은 82개 핫스팟이 위치한 "서울"의 <br>
        종합적인 실시간 도시 정보를 모아서 보여줍니다.
      </p>
    </td>
  </tr>

  <!-- 주간 탭 -->
  <tr>
    <td align="center" valign="top" style="padding: 20px;">
      <img src="./assets/tab2.gif" alt="주간 탭 이미지" /><br><br>
      <p style="max-width: 600px; margin: 0 auto;">
        <strong>✅ 주간</strong><br><br>
        사용자가 드롭다운 리스트에서 특정 장소를 선택하면<br>
        해당 장소의 지난주 통계 정보를 제공합니다.
      </p>
    </td>
  </tr>

  <!-- 인사이트 탭 -->
  <tr>
    <td align="center" valign="top" style="padding: 20px;">
      <img src="./assets/tab3.gif" alt="인사이트 탭 이미지" /><br><br>
      <p style="max-width: 600px; margin: 0 auto;">
        <strong>✅ 인사이트</strong><br><br>
        사용자가 필터 조건을 직접 구성하여<br>
        소비 패턴과 유동인구 특성을 분석하고 정렬할 수 있습니다.
      </p>
    </td>
  </tr>

</table>
