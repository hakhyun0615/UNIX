# 파일과 디렉토리를 둘러볼 때 사용하는 command
* pwd(print working directory) cf) working directory: 현재 위치해 있는 directory
* cd(change directory) ex) cd /: root directory로 이동, cd ~: home directory로 이동, cd -: 이전 directory로 이동
* ls(list): directory의 내용물들을 쭉 보여줌 ex) ls /bin: bin directory의 내용물 확인 

# 상대 경로 command
* 현재 디렉토리 = . ex) cd (./)django: 현재 디렉토리에서 밑의 django로 이동
* 상위 디렉토리 = ..
* 너무 멀어서 상대 경로가 너무 많으면 헷갈리니 절대경로 이용
* 디렉토리 안에 공백이 있으면 '',"",\ 사용(애초에 공백이 없는게 더 바람직)

# 디렉토리 만들기
* mkdir 디렉토리_이름1 디렉토리_이름2

# 파일 만들기
* touch 파일1 파일2

# CLI 환경에서 파일 내용 작성
* GUI 환경: Microsoft Word, VS Code, PyCharm, 메모장..
* CLI 환경: VIM
## VIM의 4가지 사용 모드
* 일반 모드(esc)
* 입력 모드(i)
* 비주얼 모드(v)
* 명령 모드(:)
## VIM 단축기 정리
* 텍스트 입력: 입력 모드(i) → 텍스트 입력
* 텍스트 한 줄 복사: 일반 모드 → 복사하고 싶은 줄에 커서 위치 → yy
* 텍스트 한 줄 잘라내기: 일반 모드 → 잘라내고 싶은 줄에 커서 위치 → dd
* 특정 영역 복사: 비주얼 모드(V는 줄 단위, v는 글자 단위) → 복사하고 싶은 영역 커서로 설정 → y
* 특정 영역 잘라내기: 비주얼 모드(V는 줄 단위, v는 글자 단위) → 잘라내고 싶은 영역 커서로 설정 → d
* 텍스트 붙여넣기: 일반 모드 → 붙여넣고 싶은 위치에 커서 위치 → p
* 파일 저장: 명령 모드(:) → w + enter
* 파일 저장 + vim 종료: 명령 모드(:) → wq + enter
* vim 종료 (내용 저장되지 않음): 명령 모드(:) → q! + enter

# 파일 내용 살펴보기
* cat(concatenate) 파일1 파일2: 파일 내용 한꺼번에 출력
* less 파일1 파일2: 파일 내용 페이지 단위로 나눠서 출력 cf) f/b: 페이지 이동, g/G: 첫/마지막 페이지로 이동, q:종료
* head 파일1 cf) head -n 5 파일1: 보고싶은 정확한 줄 수 입력 가능
* tail 파일1


