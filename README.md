연도별 인기가요 가사 언어분석
==================================
- 성명: 김지훈  
- 학번: 201500844  
- 전공: 경영학전공  
- 과목명: 중국문화데이터포트폴리오  
- 담당교수: 김바로 교수님  
- 주제: 연도별 인기가요 가사 언어분석  

[![Video Label](http://img.youtube.com/vi/HOyc77GOx7w/0.jpg)](https://youtu.be/HOyc77GOx7w?)  
[연도별 인기가요 가사 언어분석_프로젝트 기획서]   
   
개요:  
&nbsp;&nbsp;&nbsp;&nbsp;본 프로젝트는 연도별 인기가요의 가사를 형태소 분석을 통해 분석하고 해석하여 인기가요의 추세, 사람들의 언어 사용의 변화 등과 같은 유의미한 인사이트를 도출하고자 한다. 명사, 형용사, 동사, 부사의 각각 품사별로 분석과 해석을 진행하여, 도대체 어떤 가사가 대중들에게 인기와 많은 공감을 얻는지 파악하는 것이 본 프로젝트의 목적이다. README.md에는 배경, 목적, 대상, 방법, 파일, 진행상황이 기술되어 있으며, 더욱 자세한 분석과 해석은 보고서 파일에 기술되어 있다.   
(중국문화데이터포트폴리오_프로젝트최종보고서_김지훈_201500844.docx)   

## 1. 배경

&nbsp;&nbsp;&nbsp;&nbsp;'가사를 보면 시대상이 보인다.'  
&nbsp;&nbsp;&nbsp;&nbsp;'어떤 가사의 노래가 대중으로부터 인기를 얻을까?'  
  
&nbsp;&nbsp;&nbsp;&nbsp;오늘날 빠르게 변화하는 현대 사회 속에서 대중 문화 역시 자주 그 모습이 바뀌고, 이는 그 당시 시대를 반영하는 유행과 트렌드를 만들어가고 있다. 그리고 시대상은 그 당시에 나온 문학이나 예술 작품에도 잘 반영된다. 예를 들어, 10년 전 아이돌 그룹인 '원더걸스'의 히트곡 'Tell Me'와, '빅뱅'의 '마지막 인사'는 당시 모르는 사람들이 없을 정도로 유명했고, 많은 사람들이 좋아했으며, 한국 가요계의 인기차트를 휩쓸었던 곡들이다. 이 두 곡은 제목만 들어도 저절로 멜로디를 흥얼거릴 정도로 사람들에게 친숙하고 또 유명한 곡들인데, 이는 당시 사람들의 기호를 잘 맞추면서도 유행과 트렌드를 선도했기 때문이라고 할 수 있다. 하지만 오늘날 이 두 곡을 다시 찾아 듣게 된다면, 익숙해서 반갑지만 또 한편으로는 낯설고 조금은 촌스러운 느낌이 들지도 모른다. 이는 시대가 변화하고 세상이 달라지면서, 당시 유행하던 가요 장르와 현대의 인기 장르가 확연하게 차이가 나기 때문이다. 흔히 대중가요는 시대의 감수성을 대변한다고들 한다. 우리가 선호하는 스타일과 유행하는 트렌드는 가요 속에 그대로 반영되어 있고 따라서 시대가 가요 속에 분명하게 녹아서 남아있다는 것이다.  
  
&nbsp;&nbsp;&nbsp;&nbsp;이러한 시대상은 가수의 패션 스타일, 안무 동작, 음악 멜로디, 사용되는 악기 등 다양한 부분에 전반적으로 영향을 미치며, 노래 가사 역시 이러한 시대상에 많은 영향을 받는다고 할 수 있다. 특히, 노래 가사는 그 당시 사람들의 내적 가치관이나 생각을 잘 반영하고 있다. 예를 들어, 세계적으로 유명한 K-POP 아이돌인 방탄소년단의 경우에는 성공 요인에 있어 다양한 요인들이 존재하지만 그 중에서 가장 큰 이유 중 하나로 멤버들이 직접 곡을 쓰고 가사를 적는 싱어송라이터로 이루어져 있다는 점과 노래 가사들이 사람들의 공감을 사면서도 당시 사회의 모습과 메시지를 담고 있다는 것이다. 퍼포먼스나 멜로디만큼이나 노래의 성공 요인이 될 수 있는 것이 가사이다. 가사가 청중들로 하여금 많은 공감과 울림을 이끌어낼 때 그 노래가 더욱 성공할 수 있기 때문이다. 각 시대를 대표하는 인기 가요의 가사 내용의 변천을 통해서 사회와 문화, 그리고 당시 가지고 있던 사람들의 가치관의 변화상을 파악할 수 있을 것이라 생각한다. 따라서 우리나라에서 크게 인기를 끌었던 가요들의 가사를 데이터 분석하여 이로부터 우리나라 유행과 추세, 트렌드의 변화, 사람들의 가치관의 변화, 또 사용하는 언어 스타일의 변화 등에 대한 인사이트를 도출하고자 한다.   
  
## 2. 목적

- 데이터 분석을 통한 국내음악 가사의 내용적 특징 파악 및 해석  
- 연도별 가사 트렌드와 대중들의 선호의 변화에 대한 인사이트 도출  
  
&nbsp;&nbsp;&nbsp;&nbsp;우리나라 인기가요의 가사 데이터를 수집하고, 이를 분석하여 우리나라 당시 시대상과, 유행, 추세, 트렌드의 변화상을 파악하고자 한다. 나아가, 사람들의 가치관은 어떻게 변화했고, 당시에는 무엇을 중시했는지, 그리고 사용하는 단어나 말투는 시간의 흐름에 따라 어떻게 변화했는지 알아보고자 한다. 
  
## 3. 대상

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~~2000년 1월 1일부터 2020년 10월 1일까지의 멜론 월별 차트 10위 안의 국내음악의 가사 (중복 제외)~~ (변경)  
  
- 중복을 제외한 1964년부터 2020년 10월 31일까지의 멜론 연도별 차트 50위 안의 국내음악의 가사
  
&nbsp;&nbsp;&nbsp;&nbsp;중복을 제외한 1964년부터 2020년 10월까지의 멜론 연간 순위 50위까지의 노래들의 가사를 데이터 분석 대상으로 할 것이다. 이와 같이 분석 대상을 구체화한 것은 시기의 범위를 확장하는 것이 보다 가사에 담긴 문화나 시대상의 다양성을 잘 보여줄 수 있을 것이라고 생각했기 때문이다. 시간이 많이 흐른 시기의 노래 가사는 최근의 노래 가사와 비교했을 때, 내용적인 측면에서나 형식적인 측면에서 많은 차이를 보일 것이다. 그리고 이러한 차이는 당시 시대상의 반영으로 인한 것으로 사회 문화와 가치관이 어떻게 변화했는지 잘 보여줄 수 있는 지표가 될 것이다. 따라서 근 60년 간 국내 가요계를 휩쓸었던 인기가요의 가사를 분석 대상으로 하고 이에 대한 형태소 분석을 통해 어떠한 가사가 그 당시에 많이 쓰였는지, 그리고 왜 많이 쓰였는지 등의 해석으로 인사이트를 도출할 것이다. 
  
## 4. 방법

연도별로 분류된 국내음악 가사에 대한 언어 분석 (형태소 분석) 수행  

## 5. 파일

1. README.md  
2. rawdata_김지훈_201500844.tsv  
3. 가요 가사 데이터_100개_김지훈_201500844.xlsx  
4. 가요 가사 데이터_20개_김지훈_201500844.xlsx  
5. 데이터셋_김지훈_201500844.xlsx  
6. 데이터스크래핑_김지훈_201500844.ipynb  
7. 동사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx  
8. 멜론_데이터_스크래핑_연도별_김지훈_201500844.ipynb  
9. 멜론_데이터분석결과_김지훈_201500844.xlsx  
10. 멜론_데이터수집_김지훈_201500844.xlsx  
11. 멜론_언어분석_심화_김지훈_201500844.ipynb  
12. 명사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx  
13. 부사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx   
14. 중국문화데이터포트폴리오_최종발표PPT_김지훈_201500844.pdf   
15. 중국문화데이터포트폴리오_프로젝트최종보고서_김지훈_201500844.docx   
16. 프로젝트기획서_김지훈_201500844.pdf   
17. 형용사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx   

  
## 6. 진행상황
### 2020-10-21 16:25:50
진행현황  
- 프로젝트 기획서 작성 완료  
  - 배경
  - 목적
  - 대상
  - 방법
  - 데이터 스키마
    - id
    - title
    - singer
    - album
    - genre
    - year
    - lyrics
<p align="center">[아래 사진 클릭 시 동영상 이동]</p>  
<p align="center"><a href="https://youtu.be/HOyc77GOx7w?" target="_blank"><img src="https://user-images.githubusercontent.com/74039406/101237018-ea06f780-3718-11eb-95d7-011c5599f954.png" alt="프로젝트 기획 동영상" border="10" /></a></p>  
  
![슬라이드2](https://user-images.githubusercontent.com/74039406/101236644-546a6880-3716-11eb-9294-8c98c0654b6a.PNG)
   
   
![슬라이드3](https://user-images.githubusercontent.com/74039406/101236650-5cc2a380-3716-11eb-9d7d-e1215301a77d.PNG)
  
  
- 주제 관련 샘플 데이터 20개 수집 완료  
  
해당 파일  
- rawdata_김지훈_201500844.tsv  
- 프로젝트기획서_김지훈_201500844.pdf  

---------------------------------------
  
### 2020-11-01 12:28:58  
진행현황  
- 주제 관련 데이터 100개 수집 완료  
(스크립트 사용하지 않고 수동으로 웹사이트에서 직접 수집,  
많은 시간이 소요되는 것에 대하여 데이터 수집 스크립트의 필요성 제기)  
- 데이터 스키마
  - id
  - title
  - singer
  - album
  - genre
  - year
  - lyrics  
    
![데이터100개](https://user-images.githubusercontent.com/74039406/101237400-afeb2500-371b-11eb-8759-68c7441039d7.png)  
  
해당 파일  
- 가요 가사 데이터_100개_김지훈_201500844.xlsx  
- 데이터스크래핑_김지훈_201500844.ipynb  
  
---------------------------------------
  
### 2020-11-10 09:37:44  
진행현황  
- 데이터 스크래핑 스크립트 완성  
(멜론 연도별 인기가요 100순위)  
- 총 수집 데이터: 2,500개  
  
![그림1](https://user-images.githubusercontent.com/74039406/101238127-6e5d7880-3721-11eb-8aca-32a44a630229.png)  

변경사항  
- 분류: 월별 → 연도별  
- 범위: 2010 ~ 2020 → 1964 ~ 2020  
- 데이터 스키마
  - id
  - title
  - singer
  - lyrics 
  
해당 파일  
- 멜론_데이터_스크래핑_연도별_김지훈_201500844.ipynb  
- 멜론_데이터수집_김지훈_201500844.xlsx  
  
---------------------------------------
  
### 2020-11-13 19:19:11
진행현황  
- 언어분석 스크립트 완료  
  
![분석스크립트](https://user-images.githubusercontent.com/74039406/101238424-7cac9400-3723-11eb-93aa-84b75dd07fa4.png)  
  
- 분석결과 데이터 정제 완료  
  
![분석결과](https://user-images.githubusercontent.com/74039406/101238440-98b03580-3723-11eb-8c63-e4adee336ae9.png)  
  
- 피벗테이블 완료  
  
![피벗테이블](https://user-images.githubusercontent.com/74039406/101238445-a8c81500-3723-11eb-90cd-b2ad6c0e9ffc.png)  
  
  
변경사항  
- 데이터 개수(노래 개수): 2595개 → 2276개(중복 제거)  
- 분류: 개별 연도 → 10년 단위로 묶음(ex: 2010년대)  
  
해당 파일  
- rawdata_김지훈_201500844.tsv  
- 멜론_언어분석_심화_김지훈_201500844.ipynb  
- 멜론_데이터분석결과_김지훈_201500844.xlsx  
  
---------------------------------------
  
### 2020-11-24 08:28:05  
진행현황  
- 대명사 형태소 분석 완료  
  
![대명사](https://user-images.githubusercontent.com/74039406/101238484-f9d80900-3723-11eb-95fa-e85fbcd0db51.png)
  
  
해당파일  
- 명사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx  
  
---------------------------------------
  
### 2020-12-02 01:39:28  
진행현황  
- 명사 형태소 분석 완료  
  
![명사](https://user-images.githubusercontent.com/74039406/101238582-8a164e00-3724-11eb-88cd-bbc0dbb4e6f2.png)  
  
  
해당파일  
- 명사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx  
  
---------------------------------------  
  
### 2020-12-05 18:07:30  
진행현황  
- Github README.md 업데이트
- 동사 형태소 분석 완료
  
![동사분석](https://user-images.githubusercontent.com/74039406/101244156-1ab25580-3748-11eb-8753-0e03487bc6a7.png)   
  
- 형용사 형태소 분석 완료
  
![형용사분석](https://user-images.githubusercontent.com/74039406/101244197-4e8d7b00-3748-11eb-9996-3ee19eb345e3.png)  
  
- 부사 형태소 분석 완료
  
![부사분석](https://user-images.githubusercontent.com/74039406/101274532-27838780-37e2-11eb-9cf9-a110b6f8ba2a.png)   
  
  
해당파일
- 동사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx  
- 형용사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx  
- 부사_멜론 가사 분석 및 해석_김지훈_201500844.xlsx  
  
---------------------------------------  

  
