<table>
  <tr style='font-weight: bold;'>
    <td style='font-weight: bold;'>구분</td>
    <td>데이터 타입</td>
    <td>설명</td>
  </tr>
  <tr>
    <td rowspan="6">원시 타입</td>
    <td>숫자 타입</td>
    <td>숫자. 정수와 실수 구분 없이 하나의 숫자 타입만 존재</td>
  </tr>
  <tr>
    <td>문자열 타입</td>
    <td>문자열</td>
  </tr>
  <tr>
    <td>불리언 타입</td>
    <td>논리적 참(true)와 거짓(false)</td>
  </tr>
  <tr>
    <td>undefined 타입</td>
    <td>var 키워드로 선언된 변수에 암묵적으로 할당되는 값</td>
  </tr>
  <tr>
    <td>null 타입</td>
    <td>값이 없다는 것을 의도적으로 명시할 때 사용하는 값</td>
  </tr>
  <tr>
    <td>심벌 타입</td>
    <td>ES6에서 추가된 7번째 타입</td>
  </tr>
  <tr>
    <td colspan="2">객체 타입</td>
    <td>객체, 함수, 배열 등</td>
  </tr>
</table>

<table>
  <tr>
    <td>컴파일러 언어</td>
    <td>인터프리터 언어</td>
  </tr>
  <tr>
    <td>코드가 실행되기 전 단계인 컴파일 타임에 소스코드 전체를 한번에 머신 코드로 변환한 후 실행한다.</td>
    <td>코드가 실행되는 단계인 런타임에 문 단위로 한 줄씩 중간 코드인 바이트로 변환한 후 실행한다.</td>
  </tr>
  <tr>
    <td>실행 파일을 생성한다.</td>
    <td>실행 파일을 생성하지 않는다.</td>
  </tr>
  <tr>
    <td>컴파일 단계와 실행 단계가 분리되어 있다. 명시적인 컴파일 단계를 거치고, 명시적으로 실행 파일을 생성한다.</td>
    <td>인터프리트 단계와 실행 단계가 분리되어 있지 않다. 인터프리터는 한 줄씩 바이트코드로 변환하고 즉시 실행한다.</td>
  </tr>
  <tr>
    <td>실행에 앞서 컴파일은 단 한번 수행된다.</td>
    <td>코드가 실행될 때마다 인터프리트 과정이 반복 수행된다.</td>
  </tr>
  <tr>
    <td>컴파일과 실행 단계가 분리되어 있으므로 코드 실행 속도가 빠르다.</td>
    <td>인터프리트 단계와 실행 단계가 분리되어 있지 않고 반복 수행되므로 코드 실행 속도가 비교적 느리다.</td>
  </tr>
</table>
