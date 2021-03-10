# 언론사 프레임 분석을 위한 벡터기반의 단어 표현: 코로나 19 를 중심으로 (Vector-based word representation for media frame analysis: focused on covid-19)
---
## 요약(abstract)
 본 논문에서는 언론사 프레임 분석을 위해 2020 년 2 월 1 일부터 7 개월간 코로나 19 를 언급한
기사 데이터를 수집하여 단어 임베딩을 수행하고, 언론사별 중복단어 행렬로 K-Means Clustering 을
수행하여 군집별로 모인 언론사들의 분포를 살펴본다. 또한, 언론사별 중복되지 않는 유일단어들의
긍정, 부정, 정치적, 경제적 등의 특성에 따라 프레임을 분석하여 파악한다. 이를 통해, 특정 기간동
안 코로나 19 관련 기사에서 나타나는 언론사별 프레임을 비교 및 분석하고자 한다.


## 목차 (contents)
1. 서론
2. 관련 연구
3. 언론사 프레임 분석
   1. 데이터수집 및 단어 임베딩
   2. Word2Vec
   3. 중복단어 행렬 및 차원축소
   4. K-means Clustering 수행
4. 프레임 분석 결과
5. 결론 및 향후 연구계획
6. 참고문헌

---

### 3.2 Word2Vec
![image](https://user-images.githubusercontent.com/57992071/110603615-8afac800-81ca-11eb-96df-03e0fdc10ef3.png)   
(그림1) Word2Vec 모델의 CBOW, Skip-Gram 방식

### 3.3 중복단어 행렬 및 차원축소
![image](https://user-images.githubusercontent.com/57992071/110603756-b382c200-81ca-11eb-992e-206ce4b6b53f.png)   
(그림 2) 중복단어 행렬 (좌)과 차원축소 행렬 (우)

### 3.4 K-Means Clustering 수행
![image](https://user-images.githubusercontent.com/57992071/110603818-c39aa180-81ca-11eb-93c2-c9f97c3ea923.png)   
(그림 3) 최적의 클러스터 개수(Elbow 기법)

![image](https://user-images.githubusercontent.com/57992071/110603870-ce553680-81ca-11eb-82f0-ecdbae431656.png)   
(그림 4) K-Means Clustering 그래프

### 4. 프레임 분석결과
![image](https://user-images.githubusercontent.com/57992071/110603967-eb8a0500-81ca-11eb-9cde-e085185a3db0.png)   
![image](https://user-images.githubusercontent.com/57992071/110604011-f5ac0380-81ca-11eb-9f05-65601d562772.png)   
![image](https://user-images.githubusercontent.com/57992071/110604028-fba1e480-81ca-11eb-8b45-212562537b2b.png)



