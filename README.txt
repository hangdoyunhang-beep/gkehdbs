클릭 머니 게임 - Firebase 설정 포함 ZIP

프로젝트 설정값을 index.html에 넣어두었습니다.
프로젝트 ID: zmfflr2-cb430

ZIP 파일:
- index.html: 게임
- firebase-rules.json: 데이터베이스 권한 규칙
- README.txt: 이 안내

설치 순서:
1. Firebase 콘솔에서 프로젝트 zmfflr2-cb430을 엽니다.
2. Authentication -> 로그인 방법에서 이메일/비밀번호 로그인을 사용 설정합니다.
3. Realtime Database -> 규칙 탭으로 갑니다.
4. firebase-rules.json을 메모장으로 열고 전체 내용을 복사해 규칙 편집기에 붙여넣고 게시합니다.
5. 게임을 인터넷에 공개하기 전에 먼저 닉네임 '하도윤'으로 회원가입합니다. 최초 하도윤 계정이 개발자 계정이 됩니다.
6. index.html을 Netlify 등에 배포하면 다른 사람도 같은 데이터베이스를 이용합니다.

문제가 있으면 Realtime Database의 규칙 탭에 규칙이 게시되었는지 확인하세요.
이 게임의 KRW는 실제 현금이 아니라 가상 게임 머니입니다. 닉네임 로그인은 내부용 이메일 주소를 사용하므로 이메일로 비밀번호를 복구하는 기능은 없습니다.
일반 사용자는 다른 사용자의 프로필을 읽거나 수정할 수 없도록 규칙을 설정했습니다. Firebase 웹 앱 설정은 사이트에 들어가지만, Admin SDK 비밀키나 서비스 계정 키는 웹에 넣으면 안 됩니다.
