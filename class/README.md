# kimburg-html_study
1. div 남발하지 말자 

2. 속성(attribute)을 통해 추가적인 정보를 제공 
3. image경로를 설정할때 ./폴더명/이름확장자 
4. ul, ol의 자식요소는 무조건 li만 (li를 넣고 그 안에 다른태그를 추가)

5. 정의 리스트에서 주의 <br>
5-1. dt - dd 가 나오고 dt가 나오면 X  <br>
5-2. dl안에 section같은 다른 문법은 x  <Br>
5-3. dt나 dd는 dl없이 단독으로 사용 x <br>

6. Form은 사용자로 부터 데이터를 받을때(input) 사용됨 <br>
6-1. input <br>
6-1-1 type="?" input type="?"을 빼먹지 말자 <br>
6-1-2 placeholder = "아무것도 값이 없을때 input안에 보여줄 텍스트"<br>
6-1-3 maxlength = 글자제한 , minlength <br>
6-1-4 required = 무조건 입력을 해야됨(빈칸으로 전송되는것을 막는역할)<br>
6-1-5 disabled = 비활성<br>
6-1-6 value = 기본값, placeholder와 다른점은
value는 값으로 복사하거나 지울수 있다(아이디 저장같은 느낌)<br>
6-1-7 email = 말 그대로 email, @값이 들어가야된다 ,<br>
      passworld = 비밀번호, 값이 0 으로 가려진다 <br>
      url = url값을 적을수 있음 ex. https://포트폴리오.com<br>
      number = 숫자를 입력 받거나 고를수 있음 (max, min을 사용할 수 있는데 min, maxlength와 다른점은 글자수에 대한 제한과 숫자에 대한 제한으로 다르다!)<br>
6-1-8 accept = .jpg, .gif 같은 확장자에 제한을 둘수있는 태그