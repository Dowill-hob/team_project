# 태양광 자원과 발전시설 현황을 시각화
<div align = "center">
  <img src = "https://github.com/user-attachments/assets/ed54ae53-f4a6-4381-904d-6e3c69abb1b0" width ="400" height="300"/>
</div><br>

# 태양광 자원과 발전시설 현황을 시각화
>**팀명** : 햇빛 연구소<br>
>**주제** : 태양광 자원과 발전시설 현황을 시각화<br>
>**개발기간** : 2024-12-20 ~ 2025-01-10<br>

## 📬 배포 주소
> **배포 버전** : https://dowill-hob.github.io/solar_power_map/

## 👨‍🎓 팀원 소개

김준식|오소정|정태영|임유빈
:---:|:---:|:---:|:---:
데이터 전처리,배포 & git관리,pie그래프 구현|일사량 데이터 시각화, geojson 행정동별 경계선 나누기|bar plot 생성, tabel data insert, color bar 삽입|folium map 생성, 설비용량 및 개수 시각화, layer map 구현, color bar 삽입|

## 🖥️ 프로젝트 소개
인터넷에 산개해 있는 태양광과 관련되 데이터를 한 곳에 모아 지도에 적용시켜 후에 태양광 발전시스템을 설치할 위치를 특정하는 것에 도움을 줄 수 있는 프로그램

#### 프로젝트 구동법<br>

* 배포되어 있는 사이트로 들어가 오른쪽 위에 layer를 사용하여 원하는 형식의 데이터를 결정한다.
* 그 후 원하는 지역에 마우스 커서를 가져가면 데이터 값이 출력된다.
<div align ="center">
  
  ![제목 없는 동영상 - Clipchamp로 제작](https://github.com/user-attachments/assets/a297dd1e-6e2e-4136-aa7f-6f26a7b88264)
  
</div>

## 🗄️데이터 구성 현황


![데이터 현황](https://github.com/user-attachments/assets/e6afb230-254f-4a50-a0be-a54e76ba2c00)

## 🤖 Enviroment and Config

### Environment

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

### Develoment Environment

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

### Config

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) <img src="https://img.shields.io/badge/geopandas-139C5A.svg?style=for-the-badge&logo=geopandas&logoColor=white"> <img src="https://img.shields.io/badge/folium-77B829.svg?style=for-the-badge&logo=folium&logoColor=white"> <img src="https://img.shields.io/badge/shapely-E12828.svg?style=for-the-badge&logo=geopandas&logoColor=white"> ![Matplotlib](https://img.shields.io/badge/Matplotlib-005CA0.svg?style=for-the-badge&logo=Matplotlib&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)


### Communication
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) 

## ⭐주요 기능

### 1. 2020년 8월 일사량 데이터

![image](https://github.com/user-attachments/assets/2718b460-5b5d-4925-b477-3381ebf64b4a)

* 2020년 8월의 일사량을 행정군의 경계로 확인 가능하다
* 행정군별의 8월 평균 일사량을 얻을 수 있다.

### 2. 행정동 태양광발전 설비용량 현황 (2024년 기준)

![2](https://github.com/user-attachments/assets/b787fee4-eec0-451d-835f-ac32fd4aa153)

* 2024년의 행정동기준 태양광발전 설비용량 현황을 알 수 있다.
* 태양광을 추가로 설치할 경우 이 데이터를 사용하여 어느 지역이 다른 지역에 비해 적게 설치되었는지 많이 설치되었는지 구별이 가능하다.

### 3. 2020년 8월 일사량 데이터

![3](https://github.com/user-attachments/assets/352034b3-5415-456c-a88d-47c0e312d2ff)

* 처음 맵과 같은 데이터지만 이제 시도별로 17개의 지역만 보고 싶을경우 사용하면된다.
* 행정군별로 보기전 전체적인 시도의 현황을 파악하고 행정군별로 들어가는 것이 합당하다고 생각하여 넣은 데이터이다.

### 4. 전력사용량 대비 태양광발전량 (2020년 기준) 시/도 별 태양광발전 설비현황(2023년 기준)

![image](https://github.com/user-attachments/assets/5f522f1d-84fb-4419-ac94-fe1bad1a1c71) |![4](https://github.com/user-attachments/assets/41cf0d3b-d9a9-49ed-86be-c8fbec7b7816)
---|---|

* 전 지역 발전량에서 태양광 발전량이 몇 % 인지 확인 가능한 데이터이다.
* 이 데이터에는 추가로 팝업에 그래프를 넣어 더욱 시각화를 극대화 했다.
* bar plot은 전체 발전량에 비해 태양광 발전량의 양
* pie plot은 그 지역의 산업구분별 전력 소비량
* table은 이제 bar plot의 데이터를 정리하고 단위 면적으로 값을 도출한 값이다.

### 5. 태양광발전 설비현황 (컬러맵 : 개수)

![5](https://github.com/user-attachments/assets/4a4673f1-ca2b-4903-95fb-595e163f3d05)

* 태양광발전 설비현황을 2023년 가장 최근 데이터를 사용하여 태양광 설비개수를 기준으로 시각화한 데이터이다.

### 5. 태양광발전 설비현황 (컬러맵 : 용량)

![6](https://github.com/user-attachments/assets/cf62b01e-dfad-4a73-a51b-53a97a397fc2)

* 태양광발전 설비현황을 2023년 가장 최근 데이터를 사용하여 태양광 설비 용량을 기준으로 시각화한 데이터이다.
