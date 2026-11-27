# Bhasha 개인정보 처리방침

시행일: 2026-11-27

Bhasha(맥 메뉴바 앱)는 키보드마다 Caps Lock을 한/영 전환 키로 쓸지 정합니다. Bhasha는 **개인정보를 수집하지 않고, 어떤 데이터도 기기 밖으로 보내지 않습니다.**

## 다루는 데이터와 저장 위치
| 데이터 | 쓰는 곳 | 저장 위치 | 밖으로 보냄 |
|---|---|---|---|
| 어느 키보드에서 Caps Lock이 눌렸는지 (입력 모니터링 권한) | 그 키보드의 설정대로 한/영을 바꾸기 위해 | 저장하지 않음 (그 순간에만 씀). 다른 키 값 · 입력한 글자는 읽어 두거나 남기지 않음 | 아니요 |
| 연결된 키보드 이름 · 제조사/제품 번호 · 연결 방식 · 배터리 | 키보드 목록과 키보드별 설정 | 이 Mac의 앱 설정 | 아니요 |
| 키보드별 설정 · 화면 설정 | 사용자가 정한 대로 동작 | 이 Mac의 앱 설정 | 아니요 |
| 로그(앱 · 업데이트 · 설정 변경 · 입력 전환) | 문제를 찾을 때. 누른 키 · 입력한 글자 · 비밀 값은 남기지 않음 | 이 Mac의 앱 로그 폴더 | 아니요 (사용자가 「로그 내보내기…」로 직접 저장한 zip만, 사용자가 고른 곳에) |

- 분석 도구 · 광고 · 오류 보고 · 원격 설정이 없습니다. 데이터를 팔거나 다른 사람에게 주지 않습니다.
- App Store판은 네트워크에 연결하지 않습니다. 업데이트는 App Store가 합니다.
- 직접 내려받는 판(GitHub)은 새 버전을 확인할 때만 이 저장소의 `appcast.xml`을 읽습니다(GitHub 서버에 일반 웹 요청이 가며, 앱이 개인정보를 붙여 보내지 않습니다).
- 앱을 지우면 설정과 로그도 지울 수 있습니다. 설정 › 로그 › 「로그 초기화…」로 언제든 로그를 지울 수 있습니다.

문의: https://github.com/d2ntr5/bhasha-releases/issues

---

# Bhasha Privacy Policy

Effective: 2026-11-27

Bhasha (a Mac menu bar app) lets you choose, per keyboard, whether Caps Lock switches between Korean and English input. **Bhasha collects no personal data and sends no data off your Mac.**

- With Input Monitoring permission, Bhasha sees which keyboard Caps Lock was pressed on, only to switch the input source as that keyboard is set up. Other keys and typed text are not kept or logged.
- Connected keyboard names, vendor/product IDs, connection type and battery level, your per-keyboard and display settings are stored only in the app's settings on this Mac.
- Logs (app, update, settings changes, input switching) stay in the app's log folder on this Mac and never contain keys pressed, typed text or secrets. They leave the Mac only if you export them yourself with “Export Logs…”, to a place you choose.
- No analytics, advertising, error reporting or remote configuration. No data is sold or transferred.
- The App Store version makes no network connections; the App Store updates it. The version downloaded from GitHub reads this repository's `appcast.xml` only to check for new versions (a plain web request to GitHub; the app adds no personal data).
- Removing the app lets you remove its settings and logs; Settings › Logs › “Reset Logs…” deletes the logs at any time.

Contact: https://github.com/d2ntr5/bhasha-releases/issues
