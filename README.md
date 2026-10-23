# 앱 다운로드

한 번 설치한 앱을 계속 업데이트해서 사용할 수 있는 배포판입니다.

| 앱 | Windows PC | 안드로이드 |
|---|---|---|
| 말풍선교정소 | [설치하기](https://github.com/kimjerky/app-releases/releases/download/apps-2026.10.23.4/proofreader-setup.exe) · 0.17.1 | — |
| 어디보자 | [설치하기](https://github.com/kimjerky/app-releases/releases/download/apps-2026.10.23.4/eodiboja-setup.exe) · 0.1.4 | — |
| RPG타이머 | [설치하기](https://github.com/kimjerky/app-releases/releases/download/apps-2026.10.23.4/rpg-timer-setup.exe) · 0.8.5 | — |
| 폰티 | [설치하기](https://github.com/kimjerky/app-releases/releases/download/apps-2026.10.23.4/ponti-setup.exe) · 0.1.28 | [APK 설치](https://github.com/kimjerky/app-releases/releases/download/apps-2026.10.23.4/ponti-android.apk) · 0.29 |
| BGM for Work | [설치하기](https://github.com/kimjerky/app-releases/releases/download/apps-2026.10.23.4/bgm-for-work-setup.exe) · 0.1.27 | [APK 설치](https://github.com/kimjerky/app-releases/releases/download/apps-2026.10.23.4/bgm-for-work-android.apk) · 0.1.0-alpha.25 |

PC는 Windows x64용입니다. 폰티 Android는 Android 10 이상, BGM Android는 Android 13 이상 ARM64 기기용입니다.

## 업데이트 방법

**PC:** 설치 후 생긴 바로가기로 계속 실행하세요. 새 버전이 배포되면 앱 사용 중에 내려받고 다음 실행 때 적용합니다. 작업 중인 앱을 강제로 종료하지 않습니다. 인터넷이 없어도 설치한 버전은 사용할 수 있습니다.

**안드로이드:** 앱을 열면 주기적으로 새 버전을 확인합니다. 알림에서 업데이트를 선택하면 파일을 검증한 뒤 Android 설치 화면을 엽니다. 처음에는 이 앱의 업데이트 설치 허용이 필요할 수 있습니다. 기존 앱을 삭제하지 말고 덮어 설치하세요.

## 이전 버전을 쓰고 있었다면

업데이트 기능이 없던 이전 배포판은 이번에 한 번 새 설치판으로 교체해야 합니다. PC에서는 설치 전 기존 앱을 종료하세요. 말풍선교정소는 최초 실행 때 기존 프로그램 폴더를 선택하여 기록을 가져올 수 있습니다. 어디보자는 기존 베타 설정을 유지하고, 다른 기존판은 `config.json`을 선택하여 이어받을 수 있습니다. RPG타이머·폰티·BGM은 기존 사용자 데이터 저장 위치를 그대로 사용합니다.

어디보자에서 기존 분석 폴더를 이어받았다면 원래 폴더를 유지하세요. 개인 AI 모델·작업 자료는 공개 설치판에 포함하지 않았습니다.

전체 파일과 변경 내용은 [배포 페이지](https://github.com/kimjerky/app-releases/releases/tag/apps-2026.10.23.4)에서 확인할 수 있습니다. `.nupkg`와 `releases.*.json`은 앱이 사용하는 파일이므로 직접 실행할 필요가 없습니다.

각 앱의 정보 메뉴에서 제작자 kimjerky를 확인할 수 있습니다.

말풍선교정소·어디보자·RPG타이머·폰티는 시작할 때 간단한 사용 안내를 보여줍니다. **다시 보지 않기**를 선택하면 다음 실행부터 숨깁니다. 정보 메뉴에서 오프라인 사용설명서를 언제든 다시 볼 수 있습니다. 폰티는 PC와 안드로이드 모두 지원합니다.

이번 안정화 수정판에서는 RPG타이머 자세히 보기의 공정 수 오류, 어디보자 설치 파일 누락, 폰티 창 생성 안정성, 교정소 의도 표현 기억을 수정했습니다. 이전 PC판이 실행 직후 계속 종료되면 앱을 닫고 위 새 설치판을 덮어 설치하세요. 기존 자료는 유지됩니다.
