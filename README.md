# Link21 CEO AX 특강 시제품

## 컨셉
Claude Fable 영상의 핵심인 “AI를 도구가 아니라 직원처럼 책임을 주고 쓰라”를 Link21 CEO AX 특강 홍보용 랜딩/진단 도구로 바꾼 시제품.

## 핵심 액션
방문자가 업종, 줄이고 싶은 업무, 현재 AI 수준을 선택하면 “우리 회사 첫 번째 AI 직원 업무기술서”를 생성한다.

## 타깃
중소·중견기업 CEO/C레벨.

## 전환 흐름
1. AI 직원 시대 메시지로 문제 인식
2. AI 업무 위임 3단계 설명
3. 진단 폼 입력
4. 첫 AI 직원 업무기술서 생성
5. 화요 새벽 CEO AX 특강 신청 CTA

## 다음 개발 단계
- 신청 폼: 이름/회사/직책/연락처 저장
- CRM/구글시트 연동
- 진단 결과 PDF 다운로드
- 업종별 AI 직원 템플릿 20개 확장
- 광고 A/B 테스트용 제목·썸네일 카피 자동 생성


## GitHub Pages 배포 준비

이 폴더는 정적 HTML 사이트입니다. GitHub 저장소에 push하면 `.github/workflows/deploy-pages.yml` 워크플로우가 GitHub Pages로 배포합니다.

필요 조건:
1. GitHub 저장소 생성
2. Settings → Pages → Source를 `GitHub Actions`로 설정
3. `main` 브랜치 push

로컬 확인:
```bash
python3 -m http.server 4174
```
