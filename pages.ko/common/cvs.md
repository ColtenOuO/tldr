# cvs

> 수정 관리 시스템이며 동시성 버전 관리 시스템.
> 더 많은 정보: <https://manned.org/cvs>.

- 새로운 저장소를 생성 (`CVSROOT` 환경 변수를 외부에서 설정해야 함):

`cvs -d {{경로/대상/레포지토리}} init`

- 저장소에 프로젝트를 추가:

`cvs import -m "{{메시지}}" {{프로젝트_이름}} {{버전}} {{벤더}}`

- 프로젝트 체크아웃:

`cvs checkout {{프로젝트_이름}}`

- 파일에 대한 변경 사항 표시:

`cvs diff {{경로/대상/파일}}`

- 파일 추가:

`cvs add {{경로/대상/파일}}`

- 파일 커밋:

`cvs commit -m "{{메시지}}" {{경로/대상/파일}}`

- 원격 저장소에서 작업 디렉터리를 업데이트:

`cvs update`
