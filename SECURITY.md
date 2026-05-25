# Security Notes

이 Starter Vault에는 다음을 절대 커밋하지 마세요.

- `.env`, API 키, 토큰, 쿠키
- 개인 카카오톡/디스코드/Gmail 원문 로그
- 비공개 프로젝트 정산서, 계약서, 개인정보
- Obsidian 플러그인 설정 안에 저장된 API key
- 자동화가 만든 raw transcript 전체 덤프

공개하기 전에는 아래 명령으로 민감 문자열을 검색하세요.

```powershell
Get-ChildItem -Recurse -File -Force |
  Where-Object { $_.FullName -notmatch '\\.git\\' } |
  Select-String -Pattern 'api_key|apikey|OPENAI_API_KEY|sk-|token|password|secret' -ErrorAction SilentlyContinue
```
