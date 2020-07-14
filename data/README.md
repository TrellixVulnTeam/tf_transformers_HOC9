# 데이터 관련 python scripts

## kowiki_prepare.py

- 최종 kowiki 파일 다운로드 및 전처리
- 출력
  - kowiki.txt.zip: 토픽 단위로 정리된 text 파일


## kowiki_word_count.py
- 형태소분석기 별로 형태소 및 단어 발생 빈도 측정
  - 향후 효과적인 vocab을 만들기 위함
- 출력
  - mecab_word_count.csv.zip: mecab을 이용한 단어 빈도수 csv 파일
  - komoran_word_count.csv.zip: komoran을 이용한 단어 빈도수 csv 파일
  - okt_word_count.csv.zip: okt를 이용한 단어 빈도수 csv 파일


## kowiki_vocab_spm.py
- sentencepiece vocab 생성
- 출력
  - kowiki_n_vocab.model: sentencepiece vocab model
  - kowiki_n_vocab.vocab: sentencepiece vocab txt