# VSCODE WEB 사용

> 이 글은 vscode.dev로 작업하였습니다.

미국 기준으로 10월 20일에 [vscode web](https://code.visualstudio.com/blogs/2021/10/20/vscode-dev)이 공개되었네요. 이제 vscode를 설치하지 않고 브라우저에서 vscode를 사용할 수 있습니다.

[vscode.dev(!)](https://code.visualstudio.com/blogs/2021/10/20/vscode-dev) 포스트와 [VS Code for the Web: vscode.dev](https://youtu.be/sy3TUb_iVJM)를 보고 직접 사용해 보았습니다.

## 1. VSCODE 시작

[vscode.dev](https://vscode.dev)로 접속하면 바로 vscode가 열립니다.

## 2. Github 연동
Github와 연동해서 바로 사용할 수 있다고 하네요. repository 생성 후, 주소 앞에 접두사로 "vscode.dev"를 붙이기만 하면 됩니다. Github 로그인을 요청하는데 로그인하면 repository을 불러옵니다.

> 예) https://github.com/donggov/vscode-web -> https://vscode.dev/github.com/donggov/vscode-web

아쉬운 점은 vscode web은 terminal을 사용할 수 없다 보니, Git CLI를 사용할 수 없네요.

아쉬운 대로 vscode 내에 있는 source control을 사용하여 commit 하였습니다.

![vscode for the web](/img/github.png)


## 참고
- [vscode.dev(!)](https://code.visualstudio.com/blogs/2021/10/20/vscode-dev)
- [VS Code for the Web: vscode.dev](https://youtu.be/sy3TUb_iVJM)
