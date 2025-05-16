# keyword-eval-app-kr
키워드 평가 산점도 Voila 앱_2025

## 폰트 경고(WARNING:matplotlib.font_manager) 관련 안내
Binder 또는 Jupyter 환경에서 아래와 같은 경고 메시지가 보일 수 있습니다.
```
WARNING:matplotlib.font_manager:Could not save font_manager cache [Errno 2] No such file or directory: '/root/.cache/matplotlib/fontlist-....json.matplotlib-lock'
```
이 메시지는 Matplotlib이 폰트 캐시 파일을 저장하지 못할 때 표시되는 경고입니다.
이는 Binder와 같은 임시(에페메랄) 환경 특성상 캐시 디렉토리가 없거나 권한이 없어서 발생하는 것으로,
그래프 및 한글 폰트 출력에는 아무런 영향을 주지 않습니다.

**실행 결과에 영향이 없는 harmless(무해한) warning이므로, 무시하셔도 됩니다!**

- requirements.txt, apt.txt(예: fonts-nanum-extra)만 정상적으로 설치되면 한글폰트와 그래프 출력에 문제가 없습니다.
- 혹시 폰트 깨짐, 그래프 출력 오류가 있으면 알려주세요!

