
## 배포 사이트 [![Netlify Status](https://api.netlify.com/api/v1/badges/945be37c-a642-4932-8c8a-41d02b2805d6/deploy-status)](https://app.netlify.com/sites/boring-wright-b65a64/deploys) 

- https://boring-wright-b65a64.netlify.app
- 'Project_list.json', 'Chart.json' 파일 필요

## 최종영상
![최종영상](https://user-images.githubusercontent.com/79704928/156330426-00136574-3192-448e-9952-a06a127d821d.gif)

## 기능구현
### project list Page
#### Import_Button
- 브라우저 기본 파일 탐색기 호출
- 지정한 파일 첨부가 아니면 팝업표시
- 지정한 파일이면 Import 완료한 project list 화면이 나타남

![button_import](https://user-images.githubusercontent.com/79704928/154635381-0c119bbe-2878-4b4d-8c8f-51017c0d96b9.gif)

#### Add service
- service name을 입력하라는 알림창이 뜸
- 소문자와 숫자로만 입력 후 게시물이 추가됨
- 그렇지 않을시 에러메세지가 나타남
- 게시물 삭제기능

![sweetalert알림창](https://user-images.githubusercontent.com/79704928/154966799-eebb0250-dac4-45ef-b257-e48339728754.gif)
![게시물추가삭제](https://user-images.githubusercontent.com/79704928/154966819-6cbb2052-143a-4d18-94a7-32b733dde4a7.gif)

#### Export_Button
- 화면에 있는 project list를 json 파일로 다운받음

![download](https://user-images.githubusercontent.com/79704928/154635384-db699b78-d5e7-4333-9958-da8eed7bf556.gif)

### Chart Page
#### Import_Button
- 브라우저 기본 파일 탐색기 호출
- 지정한 파일 첨부가 완료되면 차트를 출력

![chartPage](https://user-images.githubusercontent.com/79704928/154635388-12cb4f24-b69e-4634-a94c-15f3b51e523e.gif)



