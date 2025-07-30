#  데이터로 보는 서울 <img src="./assets/seoul_mas.png" align=left width=90>

> 서울시 공공 API 기반 실시간 데이터 수집 및 AWS 기반 데이터 파이프라인·대시보드 구축  &nbsp;&nbsp; • <b>Data Engineering</b>



<br />

[<img src="https://img.shields.io/badge/프로젝트 기간-2025.07.01~2025.07.28-green?style=flat&logo=&logoColor=white" />]()

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

</div>

## 프로젝트 소개
서울 열린데이터 광장의 실시간 도시데이터 API를 활용하여 날씨, 상권, 인구, 교통, 문화행사 데이터를 통합 수집·분석하고, AWS 기반 데이터 파이프라인과 인터랙티브 대시보드를 구축하는 프로젝트입니다.


## 팀원 소개
| ![](https://github.com/Dong-yeong0.png?size=120) | ![](https://github.com/chowonseo.png?size=120) | ![](https://github.com/eelb07.png?size=120) | ![](https://github.com/pjy05079.png?size=120) | ![](https://github.com/CHU4694.png?size=120) |
|:---:|:---:|:---:|:---:|:---:|
| [정동영](https://github.com/Dong-yeong0) | [조원서](https://github.com/chowonseo) | [이승아](https://github.com/eelb07) | [서정원](https://github.com/pjy05079) | [최현욱](https://github.com/CHU4694) |

## 사용 기술
[![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1753771205354?alt=media&token=ea2ae8c2-f877-485a-a312-a6a92b0cd4e5)](https://github.com/msdio/stackticon)




## 아키텍처
<img src="./assets/architecture.png" width="500" />



<div align=center>

## Tech Stack 

| Category | Tools |
|----------|-------|
| Language | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| Data Pipeline / ETL | ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white) ![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=aws-lambda&logoColor=white) ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white) |
| Cloud / Infra | ![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazons3&logoColor=white) ![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat&logo=amazonredshift&logoColor=white) ![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat&logo=amazonrds&logoColor=white) ![ElastiCache](https://img.shields.io/badge/ElastiCache-FF9900?style=flat&logo=amazondynamodb&logoColor=white) |
| Visualization / Monitoring | ![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat&logo=metabase&logoColor=white) ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat&logo=amazoncloudwatch&logoColor=white) |
| Communication / Collab | ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000?style=flat&logo=notion&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) |


<br><br>

## Dashboard

<table style="min-width: 100% !important; max-width: 830px !important; border-collapse: collapse;">
  <!-- 실시간 탭 -->
  <tr>
    <td align="center" valign="middle" width="80%">
      <img src="./assets/tab1.gif" width="600" />
    </td>
    <td align="center" valign="middle" width="20%">
      <p>
        <strong>✅ 실시간</strong><br><br>
        설명 설명 설명 설명 설명  <br><br>
        설명 설명 설명 설명 설명 설명 설명 설명 설명 설명 
      </p>
    </td>
  </tr>

  <!-- 주간 탭 -->
  <tr>
    <td align="center" valign="middle" width="80%">
      <img src="./assets/tab2.gif" width="600">
    </td>
    <td align="center" valign="middle" width="20%">
      <p>
        <strong>✅ 주간</strong><br><br>
        설명 설명 설명 설명 설명  <br><br>
        설명 설명 설명 설명 설명 설명 설명 설명 설명 설명 
      </p>
    </td>
  </tr>

  <!-- 인사이트 탭 -->
  <tr>
    <td align="center" valign="middle" width="80%">
      <img src="./assets/tab3.gif" width="600">
    </td>
    <td align="center" valign="middle" width="20%">
      <p>
        <strong>✅ 인사이트</strong><br><br>
        설명 설명 설명 설명 설명  <br><br>
        설명 설명 설명 설명 설명 설명 설명 설명 설명 설명 
      </p>
    </td>
  </tr>
</table>
