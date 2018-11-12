# Addon 사용 방법



## Addon 다운로드 페이지

http://ofxaddons.com/categories



## Addon 선택 시 확인 사항

- 업데이트 일자

- 대응 openFrameworks 버전

- 추천 개수



## Addon 다운로드 후 할 일

- GitHub에서 다운로드 하면 파일명 뒤에 `-master` 또는 `-stable`이 있는데 이 부분을 지운다.

- 오픈프레임웍스 폴더 > addons 폴더에 다운로드 한 파일 추가



## Addon 사용 하기

Addon 중 예제 파일을 바로 사용할 수 없는 경우가 많기 때문에 오픈프레임웍스 **projectGenerator** 를 사용해 빌드한다.

#### 참고: projectGenerator 에러

> Running on OSX Sierra or later for the first time?

openframeWorks 폴더 재지정 후 `creat/update` 버튼 클릭 후 다시 진행



### 프로젝트 생성

프로젝트 이름 설정 > Addons 추가



### Addon 예제 파일 불러오기

프로젝트 생성 시 src 코드 내에 있는 세 파일(main.cpp, ofApp.cpp, ofApp.h)을 Addon 예제 파일에 있는 것으로 교체하기

