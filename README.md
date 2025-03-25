## 1. 🖥 개발자를 꿈꾸는 정필문입니다. </br>
### **도전을 두려워하지 않습니다.** </br>
데이터 분석을 위한 AI 소프트웨어 개발 과정을 이수했습니다. </br>
**<ins>Python</ins>, <ins>JAVA</ins>, <ins>Html</ins>, <ins>CSS</ins>, <ins>Javascript</ins>** 를 토대로</br>
**<ins>머신러닝</ins>, <ins>딥러닝</ins>** 에 대하여 중점적으로 학습하였고, </br>
기초를 보강하기 위해 **<ins>정보처리기능사</ins> , <ins>데이터분석준전문가</ins>** 자격증을 취득했습니다. </br></br>
### **프로젝트 진행 경험이 있습니다.** </br>
2개의 팀 프로젝트간 **<ins>요구사항정의서</ins>, <ins>기능 정의서</ins>, <ins>마일스톤</ins>, <ins>WBS</ins>** 를 작성하여 </br>
프로젝트에 대한 계획을 수립하고 체크하며 진행했으며, </br>
최종적으로 **<ins>테스트케이스</ins>** 를 통해 이슈사항을 체크하여 보완하였습니다.</br></br>

---

## 2. 📃 프로젝트</br>
### 1. 데이터 분석 솔루션 웹 구현</br>
* **프로젝트 소개** </br>
데이터 분석기능을 제공하는 웹사이트를 주제로 하여 프로젝트를 진행했습니다. </br>
회원가입, 로그인, 게시판 기능 외에 데이터 분석기능을 토대로 </br>
대시보드에 F1-score, Precition, Recall와 같은 지표와 ScreePlot을 표기합니다.</br>
[소스코드(github)](https://github.com/feelmoonjung/Project1_java_web)</br>
[ 결과보고서](https://github.com/feelmoonjung/portfolio/blob/main/src/project1_%EA%B2%B0%EA%B3%BC%EB%B3%B4%EA%B3%A0%EC%84%9C.pptx)</br></br>
* **기간 : 24.08.02 ~ 24.10.11** </br>
  * 팀빌딩 및 그라운드룰 정의</br>
  * 요구사항정의서, 기능정의서 작성</br>
  * 개발계획서, WBS, UI/UX 설계</br>
  * 소프트웨어 설계, 데이터 모델링</br>
  * 설계모듈 구현</br>
  * 테스트케이스 진행</br>
  * 결과보고서 작성</br></br>
* **담당 업무**</br>
  * **회사소개**</br>
  UI/UX 디자인</br>
  프론트엔드 (Html, CSS, Javascript)</br></br>
  * **분석사례**</br>
  UI/UX 디자인</br>
  프론트엔드 (Html, CSS, Javascript, jsp)</br></br>
  * **분석**</br>
  UI/UX 디자인</br>
  프론트엔드 (Html, CSS, Javascript, jsp)</br>
  분석결과 메일 전송기능 구현 (smtp)</br>
  분석 기능 구현 (Servlet, Process builder, MariaDB, Python, Scikit-learn)</br></br>
  ![담당소개1](https://github.com/feelmoonjung/portfolio/blob/main/images/source1.png)
  ![담당소개2](https://github.com/feelmoonjung/portfolio/blob/main/images/source2.png)
* **트러블슈팅**</br>
  * **Process builder .py 분석기능 미동작**</br>
  기존 .py파일 직접 실행 방식에서 batch 파일을 통한 형식으로 변경</br></br>
  * **분석 결과 -> 문의하기 버튼 미동작**</br>
  post -> getParameter -> Sendredirect 과정 중 오류로 판단</br>
  onclick -> a 태그로 변경하여 해당 기능 작동 확인</br></br>
  * **분석 결과 confusion matrix 불러오기 실패**</br>
  페이지 내에서 local 폴더 접근할 수 없는 것으로 확인</br>
  base64.getEncoder() 활용하여 href 재지정하여 해결</br></br>

---
  
### 2. 반도체 소자 양품/불량 Object detection model 구현</br>
* **프로젝트 소개** </br>
Ultralytice YOLO를 활용하여 반도체 소자 양품/불량 이미지 데이터를 학습시켜</br>
반도체 이미지를 업로드했을때 양품/불량을 판단하는 객체탐지모델을 구현하였습니다.</br>
웹 기반으로 진행하였으며, 결과와 예측 정확도를 함께 출력합니다.</br>
[소스코드](https://github.com/feelmoonjung/project2_ultralytics_yolo_object_detection)</br>
[결과보고서](https://github.com/feelmoonjung/portfolio/blob/main/src/project2_%EA%B2%B0%EA%B3%BC%EB%B3%B4%EA%B3%A0%EC%84%9C.pptx)</br></br>
* **기간 : 24.09.23 ~ 24.10.15** </br>
  * 데이터 선정</br>
  * 데이터 라벨링</br>
  * 모델 학습</br>
  * 웹 연동</br>
  * 결과보고서 작성</br></br>
* **담당 업무**</br>
  * **데이터 라벨링** </br>
LabelImg 활용 이미지 데이터 라벨링</br></br>
  * **YOLO 활용 데이터 학습**</br>
jupyter 가상환경 구축 및 이미지 데이터 학습</br>
버전에 따른 mAP 확인을 위한 Roboflow 활용 이미지 데이터 학습</br></br>
  * **웹연동**</br>
Flask 활용 업로드 기능 및 웹 분석기능 구현</br></br>
![담당소개3](https://github.com/feelmoonjung/portfolio/blob/main/images/source3.png)
* **트러블슈팅**</br>
  * **detect 예측 결과 내 양품/불량 외 다른 클래스 출력**</br>
  라벨링 classes.txt 확인 결과 양품/불량 외 다른 클래스 기입 확인</br>
  train 0~100 이미지 데이터 classes.txt 수정 및 라벨링 재진행</br></br>
  * **predict image 미출력**</br>
  result 저장 경로 로컬 폴더에서 가상 환경 내 폴더로 변경</br>
  plot 객체 저장 시 이미지 형태가 아닌 array 형태로 저장 확인</br>
  PIL - Image import 후 fromarray 활용하여 이미지로 변환</br></br>

---
  
## 3. 💡 기술
#### [기초]
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

#### [응용]
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)

