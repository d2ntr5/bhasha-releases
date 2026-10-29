# Bhasha 업데이트 배포

[Bhasha](https://github.com/d2ntr5/bhasha) 앱이 업데이트를 확인하는 저장소입니다. 소스 코드는 없습니다.

- `appcast.xml` — Sparkle 업데이트 목록(최신 버전 하나)
- `releases/Bhasha-x.y.z.zip` — 앱 zip. EdDSA 서명은 appcast에 있습니다.

릴리즈할 때 Bhasha 저장소의 CI가 deploy key로 자동으로 올립니다. 직접 고치지 마세요.
`test` 브랜치는 테스트 빌드(`0.0.0-<커밋>`)가 확인하는 시험용 appcast입니다.
