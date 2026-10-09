# HourlyAlarm 시간 설정 추가판

## 다운로드

- [Windows 실행 파일 다운로드](https://github.com/Mr-Nober-1/effective-run/raw/refs/heads/main/downloads/HourlyAlarm_TimeSettings.exe)
- [복구 코드·편집용 소스 ZIP 다운로드](https://github.com/Mr-Nober-1/effective-run/raw/refs/heads/main/downloads/HourlyAlarm_Recovery_Source.zip)
- [사용 방법과 복구 범위](downloads/README.txt)
- [실행 파일 SHA256](downloads/SHA256.txt)

기존 분 입력(0–59) 아래에 **시간 설정** 버튼을 추가했습니다. 버튼을 누르면 같은 창에 시·분 입력란이 나타나며, 확인 한 번으로 적용합니다. 시·분을 지정하면 매일 해당 시각에 알립니다. 창 제목, 버튼, EXE, 트레이에 GitHub 고양이 아이콘을 적용했습니다. **매시 알림 사용**으로 기존 방식으로 돌아갈 수 있습니다.

원본 실행 코드는 Python 3.14 바이트코드로 복구·보존했습니다. 원본 Python 소스를 완전히 디컴파일한 결과가 아니며, 새 설정 기능은 편집 가능한 Python 소스로 제공합니다.

Linux 가상 화면에서 설정 창과 알림 로직 등 20개 테스트를 통과했습니다. Windows에서 EXE를 직접 실행한 검증은 수행하지 않았습니다.

메인 창의 **종료**는 창만 숨기며 트레이 아이콘과 알림을 유지합니다. 트레이 메뉴의 **열기**로 복귀하고 **완전히 종료**로 실제 종료합니다.

[편집용 hourly_alarm.py 다운로드](https://github.com/Mr-Nober-1/effective-run/raw/refs/heads/main/downloads/hourly_alarm.py)
