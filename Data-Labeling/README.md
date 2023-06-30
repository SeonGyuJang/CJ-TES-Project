# 이 스레드는 데이터 라벨링에 대한 내용을 자세하게 서술할 예정입니다.

---- -

데이터 라벨링을 하는 이유는 모델이 스스로 예측할 수 있도록 특정 정보를 이해하도록 학습해야하기 때문입니다. 따라서 학습 데이터는 사용 용도에 맞게 적절하게 분류되고 라벨링 되어야 합니다.
일반적인 데이터( 강아지, 고양이, 사람, 차 등 )는 이미 라벨링 되어 있거나, 다양한 알고리즘을 통해 쉽게 라벨링이 가능합니다.
하지만 제공받은 데이터는 일반적인 것을 분류해내는 것이 아닌, 특정 정보를 예측하고 분류해야하기 때문에 직접 라벨링 하는 과정이 필요합니다.

---- -

저는 데이터 라벨링을 위해 labelImg 모듈을 사용하였습니다.

![image](https://github.com/SeonGyuJang/CJ-TES-Project/assets/126837434/ed23742c-c706-4c19-a4f5-cbd25f146ea7)

아래는 라벨링 예시입니다.

![image](https://github.com/SeonGyuJang/CJ-TES-Project/assets/126837434/40004bb3-08d5-4788-960f-ea2309868e9e)

다음과 같이 사진과 .xml이 생성된 것을 볼 수 있습니다.

![image](https://github.com/SeonGyuJang/CJ-TES-Project/assets/126837434/3a514014-e1a4-400e-9848-f3abfe1bcac0)

![image](https://github.com/SeonGyuJang/CJ-TES-Project/assets/126837434/d51e5184-a21e-4f2e-bb73-e32e47014dfa)

---- -
* 본격적으로 제공받은 데이터를 필요에 맞게 라벨링 하도록 하겠습니다. 저는 Yolo를 사용할 것이기 때문에 Yolo 형태로 저장하겠습니다.
