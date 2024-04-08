# 2024-04-08 CSS POSITION 내용 정리

position 속성:

css에서 position 속성은 HTML 문서 상에서 요소가 배치되는 방식을 결정합니다. 많은 경우, position 속성은 요소의 정확한 위치 지정을 위해서 top, left, bottom, right 속성과 함께 사용됩니다.

positon:static

position 속성ㄷ을 별도로 지정해주지 않으면 기본값인 static이 적용됩니다.
position 속성이 static인 요소는 HTML 문서 상에서 원래 있어야하는 위치에 배치됩니다.

position: relative

position 속성을 relative로 설정하게 되면 요소를 원래 위치에서 벗어나게 배치할 수 있게 됩니다. 요소를 원래 위치를 기준으로 상대적으로 배치해준다고 생각하시면 이해가 쉬워집니다.

position: absolute

position 속성이 absolute일 떄 해당 요소는 배치 기준을 자신이 아닌 상위 요소에서 찾습니다.

position 속성을 absolute로 설정하면, 부모 요소의 position 속성을 relative로 지정해주는 것이 관례입니다.

position: fixed

position 속성을 fixed로 지정하면 이렇게 요소를 항상 고정된(fixed)위치에 배치할 수 잇습니다.

이게 가능한 이유는 fixed 속성값의 배치 기준이 자신이나 부모 요소가 아닌 뷰포트(viewport), 즉 브라우저 전체화면이기 떄문입니다.

position: sticky

position: sticky 속성을 적용한 박스는 평소에 문서 안에서 position: static 상태와 같이 일반적인 흐름에 따르지만 스크롤 위치가 임계점에 이르면 positioㅜ: fixed와 같이 박스를 화면에 고정 할 수 있는 속성입니다.
