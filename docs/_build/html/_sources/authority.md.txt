Cheetah 권한별 내용
-------------------

### 2.1. 그룹관리자
그룹관리자는 그룹사용자들에게 자원 할당 및 컨테이너 관리를 하는 역활입니다.

#### 2.1.1. 대시보드
그룹관리자는 그룹 안에 사용자들의 모든 신청 사항들을 관리하고 한눈에 볼 수 있습니다.

<img src="/Users/ghungnamnoh/Documents/GitHub/template/docs/image/test6.png" width="1000px" height="300px" title="그룹관리자 대시보드" alt="그룹관리자 대시보드" />

#### 2.2.2. 내정보관리
그룹관리자의 정보를 볼 수 있습니다.

<img src="/Users/ghungnamnoh/Documents/GitHub/template/docs/image/test7.png" width="1000px" height="300px" title="그룹관리자 내정보" alt="그룹관리자 내정보" />

파란색 수정버튼을 통하여 이름, 전화번호, 이메일 변경된 정보의 수정이 가능합니다.

#### 2.2.3 SSH Keys
Cheetah는 퍼블릭 키 암호화 기법을 사용하여 로그인 정보를 암호화 및 복호화합니다.<br/> 
퍼블릭 키와 프라이빗 키를 키 페어라고 합니다. 퍼블릭 키 암호화 기법을 사용하면 암호 대신 프라이빗 키를 사용하여 컨테이너에 안전하게 액세스할 수 있습니다.<br/>
SSH key에 대한 다운로드와 분실 했을 경우 재생성 또한, 사용자의 기존의 PEM파일 추가가 가능합니다.<br/>
SSH key에 대한 사용권한을 부여하는 방법은 아래와 같습니다. (MAC, Linux)

<img src="/Users/ghungnamnoh/Documents/GitHub/template/docs/image/test8.png" width="1000px" height="300px" title="SSH Keys" alt="SSH Keys" />

```bash
chmod 400 my-key-pair.pem
```

#### 2.2.3 그룹관리

