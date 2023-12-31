# 2023_1_TizenTV
2023년 1학기 모바일SW 과목 기말 프로젝트 - **C#** 과 **Xamarin**을 활용한 **Tizen**환경에서의 **TV UI/UX** 구성

> 상세 동영상 링크: https://youtu.be/8qPjuhEZSD0

## 프로젝트 조건
- 디지털 시계 & 아날로그 시계 UI가 필수적으로 들어가있어야 함
- 그 외에 실제 TV에서 사용 가능한 실용적이고 창의적인 기능을 UI/UX 구현
  
## 프로젝트 기간
2023.05.10 ~ 2023.05.28

## 개발 환경
- Tizen
- C#
- Xamarin
- .NET framework
- Visual Studio

## 화면 구성
### 홈 화면
![image](https://github.com/Taebee00/2023_1_TizenTV/assets/104549849/ea326a6f-2ae1-4a02-9476-0f3f4f2d5ac7)

1. 디지털 시계: 날짜, 시간을 나타내는 디지털 시계를 화면 왼쪽 상단에 배치
2. 아날로그 시계: 시간을 나타내는 아날로그 시계를 화면 왼쪽 하단에 배치
3. 이미지 버튼: 리모컨을 통해 버튼을 조작(이동 및 클릭)할 수 있으며, 클릭되었을 때 각각의 기능을 하는 화면으로 전환
4. 미리보기: 이미지 버튼이 Focus 되었을 때, 이미지 버튼의 기능을 설명해주는 미리보기를 이미지 버튼 하단에 배치 

### 날씨 화면
![image](https://github.com/Taebee00/2023_1_TizenTV/assets/104549849/b7402588-7516-4e4b-8316-4a707ddb0295)

1. 기상청 전국중기예보 Rss 파일을 가져온 후, Xml 파일로 변환하여 날씨 정보를 받아옴
2. 미리 받아온 날씨 이미지 파일과 현재 전국의 날씨를 비교하여 이미지와 텍스트를 통해 전국의 날씨를 효과적으로 알려줌 

### 스마트홈 화면
![image](https://github.com/Taebee00/2023_1_TizenTV/assets/104549849/eaa84d19-1ed2-4146-824f-b1a96f02b7d7)

1. Turn On All, Turn Off All 버튼을 통해 한번에 모든 스마트홈 가구 제어 가능
2. 버튼 클릭을 통한 스마트홈 가구 개별 제어 가능

### 설정 화면
![image](https://github.com/Taebee00/2023_1_TizenTV/assets/104549849/2be7961b-1a3a-4df3-bfb0-705046686b45)

1. 리모컨 이동을 통해 원하는 이미지를 선택하면 배경화면이 변경되어 적용됨



