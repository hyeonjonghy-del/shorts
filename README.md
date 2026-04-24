# 🎬 역사 쇼츠 메이커

역사 + 경제를 연결하는 유튜브 쇼츠 콘텐츠 자동 생성 Streamlit 앱

## 기능
- 추천 주제 8개 또는 직접 입력
- 장면별 스크립트 자동 생성
- 나레이션 전문 (타입캐스트 바로 붙여넣기용)
- Pexels 이미지 검색 링크 자동 연결
- 해시태그 10개 자동 생성
- 제목 후보 3개 제안

## 제작 워크플로우
1. 이 앱에서 스크립트 생성
2. 나레이션 → [타입캐스트](https://typecast.ai) 붙여넣기
3. 이미지 → Pexels 링크 클릭 후 다운로드
4. CapCut에서 편집 + 자막 자동생성
5. YouTube 업로드 (해시태그 복붙)

## 로컬 실행 방법
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Streamlit Cloud 배포
1. GitHub에 push
2. [share.streamlit.io](https://share.streamlit.io) 접속
3. 레포 연결 후 Secrets에 `ANTHROPIC_API_KEY` 입력
