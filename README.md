# JongEon

# Git 명령어 리스트

## 기본 명령어
- `git init`: 새로운 Git 저장소 초기화
- `git clone [url]`: 원격 저장소를 로컬에 복제
- `git status`: 현재 저장소의 상태 확인
- `git add [file]`: 파일을 스테이징 영역에 추가
- `git commit -m "[메시지]"`: 스테이징 영역의 변경 사항을 커밋
- `git log`: 커밋 기록 확인

## 브랜치 관련 명령어
- `git branch`: 현재 브랜치 목록 확인
- `git checkout [branch_name]`: 브랜치 전환
- `git checkout -b [branch_name]`: 새로운 브랜치 생성 후 전환
- `git merge [branch_name]`: 브랜치를 병합

## 원격 저장소 관련 명령어
- `git remote -v`: 원격 저장소 목록 확인
- `git push origin [branch_name]`: 로컬 변경 사항을 원격 저장소에 푸시
- `git pull`: 원격 저장소의 변경 사항을 가져와 병합
- `git fetch`: 원격 저장소의 변경 사항을 가져오기 (병합은 하지 않음)

## 기타 명령어
- `git stash`: 현재 작업 중인 변경 사항을 임시로 저장
- `git stash pop`: 임시 저장된 변경 사항을 다시 적용
- `git reset --hard [commit_id]`: 특정 커밋으로 되돌리기

