# CoordinatesConverter
좌표 변환 모듈 입니다.


기상청 Open API 가 TM 좌표 기반이라 iOS 의 WGS84 를 변환하기 위해서 변환 모듈을 하나 만들었습니다.

http://www.androidpub.com/1043970 에 공개해 주신 분의 자바 코드를 스위프트 코드로 포팅했습니다.  
스위프트를 공부하면서 처음으로 개발한 모듈이라서 이상한 부분이 많을 수도 있습니다.

거의 그대로 포팅했지만 변수가 사용된 부분을 전부 상수 처리로 대체하느라 코드 구조가 약간 다릅니다.

카카오 Open API 에서 변환한 값이랑 약간의 오차가 발생하는데 제가 변환 식을 이해하고 포팅한게 아니라서 수정할 수는 없네요. 

도움을 바랍니다.

코드는 공개합니다.
https://github.com/prostars/CoordinatesConverter



