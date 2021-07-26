# Convention

## commit convention

```
commit-type: 커밋 제목 #이슈-번호

본문
```

### type

- fix: 버그 수정
- feat: 새로운 기능
- delete: 코드, 파일 제거
- perf: 성능 개선
- revert: 작업 되돌리기
- docs: documentation 변경
- test: 누락된 테스트 추가 또는 기존 테스트 수정
- refactor: 버그를 수정하거나 기능을 추가하지 않는 코드 변경, 리팩토링
- chore: 패키지 매니저 설정할 경우, 코드 수정 없이 설정을 변경
- style: 코드 의미에 영향을 주지 않는 변경사항 ( white space, formatting, colons )
- ci: ci구성파일 및 스크립트 변경
- build: 시스템 또는 외부 종속성에 영향을 미치는 변경사항 (npm, gulp, yarn 레벨)

### Example

```
feat: 새로운 작업 내용 #1

새로운 작업에 대한 자세한 내용
```
