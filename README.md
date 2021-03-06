<b><span style="color:red">KNU</span> 빅데이터 분석가 양성과정 NLP 미니 프로젝트</b>
# <b>네이버 영화 리뷰 감성 분류</b>

Contributors : 정희택, 류제범, 변지영, 한혜림, 유호준, 하동호

## <b>목적</b>
  네이버 영화 리뷰에 대한 긍정 · 부정 감성 분류

## <b>방법</b> (추후 정리)
  총 200,000개 리뷰로 구성된 네이버 영화 리뷰 데이터 지도 학습
  
  1. 웹크롤링을 통해 테스트데이터셋 준비
     - 네이버 리뷰
     - 다음 리뷰
        - webcrawling.ipynb 

  2. 토큰화 방법 정하기
     - kkma
     - Komoran
     - Hannanum
     - Okt
     - MeCab
       - preprocessing.ipynb 
       - mecab사용.ipynb

  3. LSTM 알고리즘 적용
     - nlp.ipynb
     
  4. GRU 알고리즘 적용
     - GRU mecab.ipynb 
     - GRU OKT.ipynb
     
  5. CNN 알고리즘 적용
     - CNN(+다음).ipynb
     - CNN.ipynb

  6. 시각화
     - 

## <b>활용 데이터</b>
  https://github.com/e9t/nsmc/

## <b>사용 툴 / 라이브러리</b> (추후 정리)
|구분|내용|설명|
|---|---|---|
|Lib|pandas|.|
|Lib|numpy|.|
|Lib|konlpy|.|
|Lib|pykospacing|.|
|Lib|hanspell|.|
|Lib|tensorflow|.|
|Lib|nltk|.|
|Lib|collections|.|
|Lib|wordcloud|.|
|Lib|matplotlib|.|
|Lib|seaborn|.|
|Lib|os|.|
|Lib|tqdm|.|
|Lib|eunjeon|토큰화|
|Tool|Tableau|.|

## <b>파일 설명</b>
+ /data
  - ratings_test.txt
  - ratings_train.txt
  - rating_train_spaced.csv
  - okt_x_train.csv
  - stopwords.csv
+ preprocessing.ipynb
 
## <b>알고리즘</b>
+ LSTM
  - nlp.ipynb
+ GRU
  - GRU 작업중.ipynb
+ CNN 알고리즘 적용
  - CNN(+다음).ipynb
  - CNN.ipynb 
  
<b></b>
<b><span style="color:red"></span>
