* 토큰나누기를 할때, '{' 값과 '}' 값을 따로 나눔,:는 key값과 같이 있을 수 있도록 나눔"{'dominate':13}"를 나눈걸 예시로들면
 ['{','dominate:','13','}']이런 형식으로 나눌 수 있도록. ':'값이 존재하면 ':'값 이전까지 type이 object key인 value 값에 넣어 주도록 하고, child는 '[]' 로.

* 분석을 할때, { 값이 나오면 새로운 제이슨 데이터를 만들도록. child에는 getChild가 여전히 들어가도록 하고, { 다음에 오는 값은 무조건 ':' 를 포함하고 있을 테니, 그값만 key로 만들고 뒤의 값은 이전과 같은 방식으로 만들 수 있도록 하기. '}'가 나올때 까지.  