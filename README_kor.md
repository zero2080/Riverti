#### README

간단한 서버시간 예제와 함께 당신의 SpringMVC 프로젝트를 시작해보세요!

##### 실행방법
- 프로젝트를 톰캣 경로에 배포하기 위해 빌드를 먼저한 후, 실행을 해야합니다.
- 빌드 후 실행을 하면, 프로젝트에 연결된 도메인으로 실행 결과를 확인하실 수 있습니다.

##### 빌드
- 빌드 시 .war 파일 생성 및 기존에 배포되었던 application 삭제, 생성 된 .war 파일을 Tomcat의 webapps directory에 배포하는 프로세스가 진행됩니다.
- 서버 실행 도중 빌드할 시, 빌드 완료 후 잠시 기다리면 Tomcat이 자동으로 application을 재시작합니다.


##### 환경변수 설정
- Tomcat, Maven 경로 등의 환경변수는 ~/.profile 파일에 작성되어 있어, 직접 setting이 필요한 경우 vim 등의 편집기로 열어서 수정하면 됩니다.

##### Directory Role 설정
- Sources Root 경로는 src/main/java가 기본값으로 설정되어있으며 프로젝트 속성에서 '소스 경로'를 수정하여 설정할 수 있습니다.

##### Test gitignore
ㅋㅋㅋㅋ
