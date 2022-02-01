# visualization_cattle_slaughter
![slaughter](https://user-images.githubusercontent.com/49854618/150788331-7b29a89b-ea52-444f-8810-49bdd2bc9dd7.gif)
---

# Power BI를 이용한 도축량 분석


## 분석배경 
- 한해 도축량이 얼마일까?
- 1등급은 얼마나 많을까?
- 1등급은 얼마의 개월수에서 도축을 하는게 확률이 높을까?

## 데이터 구하기
도축량 데이터는 https://data.mafra.go.kr/main.do에서 구하여 사용하였습니다.

## 데이터 전처리 
![123](https://user-images.githubusercontent.com/49854618/150790350-598019ce-fc49-4832-a4b4-c7ca2be9caa1.PNG)   
데이터는 클린데이터라 판단하여 기본 제공 데이터로 사용하였습니다. 

## 첫번째 페이지 설명   
![도축량](https://user-images.githubusercontent.com/49854618/150788640-1bf6e1a2-6776-462d-9613-4e57bea9f2af.PNG)   
- 왼쪽 아래 월별 도축량을 보게 되면 1월과 8~9월에 도축량이 많은 것을 알 수 있다. 이것을 신년행사나 명절이 있는 시기에 소 도축이 늘어난다는 것을 알 수 있습니다.
- 2015년에 가장 많은 도축이 이루어졌다는 것도 알수 있습니다.


## 두번째 페이지 설명
![등급표](https://user-images.githubusercontent.com/49854618/150788926-ca8ba02a-ccdf-4f13-add4-58844224dd42.PNG)
- 1++등급은 어떻개월수에서 가장 많이 나올까?   
![1414124](https://user-images.githubusercontent.com/49854618/150791155-d618baa8-c810-4422-a838-8157dd7456dc.PNG)
- 1++ 등급은 29~32개월의 소가 제일 많이 나오는 것으로 보인다. 가장 건강하고 가장 노후가 안된 소가 높은 등급을 받는 것으로 풀이됩니다.
- 등급이 내려갈수록 40개월이 넘어가는 소가 많이 나오게 되는데 이는 암소가 있어 암소는 송아지를 낳기 때문에 소도 나이가 들면 등급이 낮은 것으로 나오고 또한, 노후가 된 소가 등급이 낮은 것으로 풀이 됩니다.     
![거세](https://user-images.githubusercontent.com/49854618/150789834-c1b4c6bd-3a3d-43b8-8616-b17d7b656852.PNG)
- 위에 사진을 보면 거세가 높은 등급을 받을 확률이 높은 것으로 보인다. 암소보다는 거세를 선호하는게 좋을 것으로 보입니다.
