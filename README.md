# 임희정 커리어 사이트

개인 소유 정적 사이트입니다. 계정 종속이 없어 이직해도 그대로 유지됩니다.

## 채워 넣을 자리 (index.html 안의 `{ }` 표시)
- `{개인_이메일}` — 공개용 개인 이메일 (회사 이메일 X)
- `{리멤버_프로필_URL}`
- `{커리어리_URL}`
- `{GitHub_URL}` — 개인 GitHub 프로필
- `{링크드인_URL}` — 계정 복구 후

## 개인 GitHub Pages로 배포하기 (무료)

**중요: 반드시 개인 GitHub 계정으로 하세요 (회사 계정 X).**

1. 개인 GitHub에서 새 저장소 생성 — 이름을 `<내아이디>.github.io` 로 (예: `huijeong.github.io`)
2. 이 폴더(`career-site`)의 `index.html`을 그 저장소에 올림
   ```bash
   cd career-site
   git init
   git add index.html
   git commit -m "커리어 사이트 첫 배포"
   git branch -M main
   git remote add origin https://github.com/<내아이디>/<내아이디>.github.io.git
   git push -u origin main
   ```
3. 몇 분 뒤 `https://<내아이디>.github.io` 에서 열림
4. (선택) 내 도메인 연결 — 저장소 Settings → Pages → Custom domain

## 업데이트
`index.html` 수정 → `git add . && git commit -m "..." && git push` → 자동 반영.
내용(경력·글·링크)만 정본으로 여기서 관리하고, 리멤버·커리어리엔 맞춰 붙여넣으면 됩니다.
