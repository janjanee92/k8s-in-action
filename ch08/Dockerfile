FROM python:3.12

# 작업 디렉토리 설정
WORKDIR /app

# 필요한 패키지 설치
RUN pip install --no-cache-dir kubernetes

# Python 스크립트 복사
COPY list_apis.py .

# 컨테이너 실행 시 Python 스크립트 실행
CMD ["python", "list_apis.py"]