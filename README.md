# VSCODE WEB 사용

> 이 글은 vscode.dev을 사용하여 작성하였습니다.

미국 기준으로 10월 20일에 [vscode web](https://code.visualstudio.com/blogs/2021/10/20/vscode-dev)이 공개되었네요. 이제 vscode를 설치하지 않고 브라우저에서 vscode를 사용할 수 있습니다.

[vscode.dev(!)](https://code.visualstudio.com/blogs/2021/10/20/vscode-dev) 포스트와 [VS Code for the Web: vscode.dev](https://youtu.be/sy3TUb_iVJM)를 보고 직접 사용해 보았습니다.

## 1. VSCODE 시작

[vscode.dev](https://vscode.dev)로 접속하면 바로 vscode가 열립니다.

## 2. Github 연동
Github와 연동해서 바로 사용할 수 있다고 하네요. repository 생성 후, 주소 앞에 접두사로 "vscode.dev"를 붙이기만 하면 됩니다. Github 로그인을 요청하는데 로그인하면 repository을 불러옵니다.

> 예) https://github.com/donggov/vscode-web -> https://vscode.dev/github.com/donggov/vscode-web

vscode web은 terminal을 사용할 수 없다 보니, Git CLI를 사용할 수 없네요. 아쉬운 대로 vscode 내에 있는 `source control`을 사용하여 commit 하였습니다.

![vscode for the web](/img/github.png)


## 3. Extension (확장 프로그램)

주로 사용하는 Extension들을 설치해보았습니다.

### 3-1. 테마
제가 원래 사용하던 `Material Theme`은 아직 지원하지 않네요.

`Sublime Material Theme`을 설치하였습니다. 잘되네요.

![theme](/img/theme.png)

### 3-2. Prettier

코드 포매터입니다. 잘되네요. (.prettierrc 파일은 인식 못하고, vscode extention 내에서 설정한 값이 적용되는 것 같음)

![prettier](/img/prettier.png)

### 3-3. Material Icon Theme

파일 아이콘을 귀엽게 표시해주는 확장 프로그램입니다. 아이콘이 귀엽게 변경되었습니다.

![Material Icon Theme](/img/iconTheme.png)

## 4. 단축키

브라우저와 겹치는 단축키를 외에는 잘됩니다. 

예를들어 `Ctrl+N`이나 `Ctrl+W` 같이 브라우저와 겹치는 단축키는 사용할 수 없습니다.

## 5. Live Share

잘 됩니다. Live Share Extension을 설치하면 사용할 수 있습니다. Live Share URL이 생기고, 익명 참가자에게도 read & write 권한 모두 줄 수 있네요. 처음 써보는데 신기하고 좋아 보입니다.

아래는 익명 사용자로 Live Share에 참여한 화면입니다.

![Live Share](/img/liveshare.png)

## 정리

- 브라우저 샌드박스 내에서 동작하다 보니, 터미널이나 디버거 등의 기능 제한이 아쉽네요.
- 대신 이 문서처럼 간단한 마크다운 작성 등의 작업은 편합니다.
- 파이썬이나 뷰, 노드 등도 한번 해봐야겠습니다.

## 참고
- [vscode.dev(!)](https://code.visualstudio.com/blogs/2021/10/20/vscode-dev)
- [VS Code for the Web: vscode.dev](https://youtu.be/sy3TUb_iVJM)
