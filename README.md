# Naver Movie Review

네이버 영화 리뷰 데이터셋을 활용한 감성 분석 프로젝트입니다.

## 프로젝트 소개

네이버 영화 리뷰 데이터(`ratings_train.txt`, `ratings_test.txt`)를 이용하여 영화 리뷰의 감성을 분석하는 Python 기반 프로젝트

## 파일 구조

```
naver_movie_review/
  ├─ navermoviereview.py         # 메인 파이썬 코드
  ├─ ratings_train.txt           # 학습용 데이터셋
  ├─ ratings_test.txt            # 테스트용 데이터셋
```

## 데이터셋 설명

- `ratings_train.txt`: 학습용 리뷰 데이터 (id, document, label)
- `ratings_test.txt`: 테스트용 리뷰 데이터 (id, document, label)

각 파일은 탭(`\t`)으로 구분된 텍스트 파일입니다.


## 참고

- 데이터 출처: [AI Hub - 영화리뷰 데이터셋](https://www.aihub.or.kr/) 