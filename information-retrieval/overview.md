# overview

## 정밀도와 재현율
__정밀도__ precision 는 검색된 결과들 중 관련 있는 것으로 분류된 결과물의 비율이고, __재현율__ recall 은 관련 있는 것으로 분류된 항목들 중 실제 검색된 항목들의 비율이다.


- [wiki](https://ko.wikipedia.org/wiki/%EC%A0%95%EB%B0%80%EB%8F%84%EC%99%80_%EC%9E%AC%ED%98%84%EC%9C%A8)
- [google 머신러닝 코스](https://developers.google.com/machine-learning/crash-course/classification/precision-and-recall?hl=ko)

## wildcard
query가 들어왔을 때 가장 먼저 진행하는 일은 사전에 해당 query가 있는지에 대한 여부이다. 사전의 키는 해싱되어 들어 있는데, 만약 query에 오류가 있다면 (철자가 틀렸다던가) 해시 값이 완전히 달라지므로 원하는 결과를 얻을 수 없을 것이다.

이를 위해 사용하는 것이 와일드카드(wildcard) 연산이다.
