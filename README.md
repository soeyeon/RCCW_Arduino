충돌경고회로

LED의 색을 제어해야 하기 때문에 LED함수를 만들어서 RGB 값을 인수로 제어하는 함수를 만들고, 조건문을 통해 초음파 센서의 거리를 상황별로 나눠줍니다. 
30CM 이상일 때는 R과 G의 값은 점점 0으로, B의 값은 점점 오르게 하여 서서히 색이 바뀌도록 합니다. 
반대로 30CM 이하일 때는 B와 G의 값은 0으로, R의 값은 점점 오르게 구현하여 점점 빨간색이 나오게 해줍니다. 
그리고 cm에 따라 delay를 다르게 주어 깜빡거리는 기능을 추가합니다. 
