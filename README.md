# Translate-app
### 실행
1. .env 설정
    - Translate-app
    ```sh
    # "production" or "development"
    ENV =development

    # API keys
    DEEPL_AUTH_KEY=
    OPENAI_API_KEY=

    # Models
    OPENAI_MODEL=gpt-4o

    # Databases
    DB_HOST=db # docker-compose -> db # localhost -> "localhost"
    DB_USER=
    DB_PW=
    DB_PORT=
    DB_NAME=

    MYSQL_ROOT_PW=

    # SMTP 서버 설정
    SMTP_SERVER=smtp.gmail.com
    SMTP_PORT=587
    Email_LOGIN_ID=
    Email_LOGIN_PW=

    Email_SENDER=Using-AI-Tools

    EMAIL_RECEIVER_TEST=

    SURVEY_FORM_URL=
    ```
2. docker-compose 실행
    ```sh
    # 실행
    docker-compose --env-file .env up --build

    # 중지
    docker compose down -v 
    ```
## Documents
- [wiki](https://github.com/daehyun99/Translate-app/wiki)