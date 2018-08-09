익숙하지 않은 라이브러리/프레임워크를 짧은 시간안에 어느 정도 적응할 수 있는지 확인하기 위한 과제입니다.

웹 서비스에서 자주 있는 폼을 구성하면 됩니다.
Mithril 프레임워크로 작성된 기본 코드에 기능을 추가해야 합니다.

(첨부 파일 보안 이슈로 webpack.config.js 파일명을 .j로 설정했습니다. .js로 변경하시고 진행하시면 됩니다.)

# 요구사항
* 각 컨트롤에 placeholder를 추가해주세요.
* 휴대폰 번호 입력 컨트롤을 추가해주세요.
    * 잘못된 번호 입력시 에러를 표시합니다.
    * 숫자만 입력해도 자동으로 -를 추가해서 표시합니다.
* 인스타그램 소유 여부를 선택하는 라디오 버튼을 추가해주세요. (sample\_instagram.png 참고)
    * 기본 값은 어느 것도 선택되지 않은 상태입니다. `인스타그램 보유 여부를 선택해주세요.`라는 메시지를 표시해줍니다.
    * 인스타그램 소유 선택시 주소를 입력하는 컨트롤을 표시합니다. (미소유 선택시 컨트롤을 표시하지 않습니다)
    * 주소 입력시 혼란을 막기위해 컨트롤 앞에 `https://www.instagram.com/`를 표시해줍니다.
* 소유한 핸드폰 개수를 입력 받는 컨트롤을 추가해주세요.
    * 가능한 값은 0, 1, 2, 3, 4, 5개 이상입니다.
    * 기본값은 0입니다.
    * 값은 숫자로 저장합니다. 5개 이상은 5로 저장합니다.
* 재활용성을 높이도록 적절하게 기존 컨트롤 클래스를 수정 또는 새로운 컨트롤 클래스를 추가해주세요.
* 이메일/암호/암호 확인/인스타그램 소유 여부/핸드폰 개수는 필수 입력 사항입니다. 이름/휴대폰 번호는 필수가 아닙니다.
* 입력된 값에 오류가 있는 경우 `Sign up` 버튼을 누를 수 없습니다.
* TSLint 규칙을 지켜주세요.

# 평가기준
* 요구사항 만족도
* 코드 구성 / 코드 가독성 (불필요한 주석은 없는 것을 선호합니다)