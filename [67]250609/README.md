# 시스템 아키텍처
    - Frontend
        - Streamlit 기반
        - 이미지 업로드,설명입력,결과표시(리뷰, 유사도, 상세추천)
    - Backend
        - sommeiler.py, 이미지분석, 벡터DB검색, LLM프롬프트 처리
    - 외부서비스
        - OpenAI API : GPT-4o mini(LLM) , texte-emdedding-3-small(임베딩)
    - 환경설정
        - .env파일로 처리
# 주요 사용 기술
    - 주요라이브러리
        - openai, langchain_openai,  ..
    - 모델
        - 토큰임베딩 : texte-emdedding-3-small
        - LLM :  GPT-4o mini
    - 벡터DB
        - Pincone(us-east1-aws, consine metric, dimension = 1536)       
