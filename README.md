# 판다스 복습
### 처음 알게된 정보들

```python
s = pd.Series([1, 3, 5, np.nan, 6, 8], index=dates).shift(2)
# shift를 통해서 들어갈 값을 원하는만큼 밀 수 있음
s.str.lower()
# str.lower를 통해서 소문자로 변환 가능
rng = pd.date_range("1/1/2012", periods=100, freq="s") # 1초 간격
# 범주형 변수 정렬 시 어휘 순이 아닌 범주별 순서에 따라 정렬
df.sort_values(by="grade")
```
