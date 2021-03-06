# TDD 이야기

> [리얼타임] TDD에 대한 오해와 진실: TDD 이야기

소개

- TDD는 단기/장기적인 목표를 제시하며 성취감을 준다
- 설명서, API 문서로 사용할 수 있다



외부의 압박이 아니라 소프트웨어 장인의 마음가짐으로 TDD를 적용하려고 해야 한다



TDD는 개발속도를 저하시킨다

- TDD를 위한 환경 구축이 필요하다: 숙련되면 신경 쓸 필요가 없는 부분이다
- 추가적인 코드가 필요하다: 개발 속도를 저하시키는 다른 요소들을 개선하고 예방할 수 있다
- 요구 사항이 변경되면 테스트 코드도 변경해야 한다: 수정이 안전하다 (신뢰성 유지)



단순한 팝업 페이지를 띄우는데 테스트 코드를 도입한다면 단점만 돋보일 수밖에 없다. 하지만 조금만 규모가 커져도 테스트 코드의 유용성을 알 수 있다.

A와 B가 협업을 한다. A와 B가 같은 기능을 수정할 일이 생겼다. 서로 수정한 사항에 대해 확실히 알지 못하므로 이것저것 테스트를 해야 한다.

최종 버전이 나왔다. 그런데 테스트 코드가 없다. 무엇부터 무엇까지 테스트를 해야 할까? 결국 테스트해볼만한, 그럭저럭 중요해보이는 것들만 테스트하게 된다. 모든 기능을 테스트하지 못해서 결국 어느 순간 그 부분에서 오류가 발생하게 된다.

테스트 코드는 결국 명세서와 같다. "이러이러한 테스트를 통과할 기능을 만들어라" 라고 말하는 것이다. 이는 설계를 명확히 해주고, 단련이 되면 자연스레 코드 작성 전에 체계적으로 설계하는 힘이 길러진다.

TDD를 사용했을 경우 시간 흐름에 따른 코드 변경 비용 변화

