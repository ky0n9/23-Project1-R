# 권용대

## 2021/03/09
GIT 설치, CMD창에서 git -v 혹은 git --version으로 설치 확인 </br>
VS Code 설치, 실행 후 </br>
__git config --global user.name “유저 이름"__ </br>
__git config --global user.email "유저 메일"__ </br>
을 이용해 사용자 정보 등록 (공유 PC에선 --global 옵션 제거 권장) </br>
__git config --global user.name__ </br>
__git config --global user.email__ </br>
로 설정된 내용 확인 </br></br>
사용할 폴더를 연 후, source control의 Initialize Repository를 클릭하거나 </br>
터미널에 git init 명령어로 해당 폴더를 초기화 한다. </br>
초기화 된 폴더에 파일을 생성, 혹은 변경사항 발생 시 source control에 숫자가 표시된다. </br>
source control 선택 후 commit을 하려는 파일의 파일 이름 옆 + 버튼을 클릭해 stage로 이동시킨 후 Message라고 쓰여있는 곳에 commit 제목과 설명을 적는다. </br>
* 제목은 동사 원형으로 시작하며 50글자 이내로 작성한다. </br>
* 엔터키를 두번 누른 후 설명을 작성한다. </br></br>

변경된 내용 중 일부 파일만 push하는 경우 케밥 메뉴를 클릭하고 ‘Push’를 선택, GitHub에 아직 Repository가 없다면 Add Remote 버튼을 클릭한 후 원하는 repository를 선택한다. </br>

변경된 내용을 모두 push하는 경우 더 이상 커밋할 파일이 없으면 commit 버튼이 ‘Publish Branch’로 바뀌는데, 이 버튼을 클릭하면 Push 된다. </br>
위의 경우와는 다르게 repository가 없으면 새로 만들어 Push한다. </br>
현재 작업 폴더와 같은 이름으로 원격에 저장소를 생성한다. </br>
다른 이용자가 해당 내용을 볼 수 있게 하려면 public을, 비공개로 하려면 private를 선택한다. </br>

기본 브라우저로 GitHub에 로그인 후 </br>
스테이터스 바의 구름 아이콘을 클릭하거나 Push시에 나타나는 팝업창에서 VS Code와 GitHub를 연동한다. </br>

### __R언어__ 
R은 비교적 최근에 개발된 프로그래밍 언어다. </br>
다른 언어들과 달리 R은 통계를 포함한 데이터 분석 작업에 특화된 언어다. </br>
