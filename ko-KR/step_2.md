## 서스펜스

위험이 알리는 소리를 만들면서 시작해봅시다.

+ 첫 번째 특수 효과를 만들려면 `:ambi_choir` 샘플을 빈 버퍼에 추가합니다.
    
    ![스크린샷](images/effects-suspense-sample.png)

+ 샘플이 재생되는 **속도**를 바꿀 수 있습니다. `rate`값이 `1`인 것은 샘플의 기본 재생 속도를 의미하며, 1보다 작은 `rate`값을 사용하면 샘플의 재생 속도를 늦출 수 있습니다.
    
    ![스크린샷](images/effects-suspense-rate-low.png)

+ 샘플이 천천히 재생되는 것을 들으려면 'run'을 누르세요. 샘플의 소리가 어떤가요?

+ `rate`가 1보다 높으면 샘플의 재생 속도가 빨라집니다.
    
    ![스크린샷](images/effects-suspense-rate-high.png)

+ 샘플을 다시 들어보세요. 이제는 어떻게 들리나요?

+ 루프에 넣어 샘플을 몇 번 반복 할 수 있습니다. 이때는 샘플을 재생한 후 `sleep`를 추가해야 합니다.
    
    ![스크린샷](images/effects-suspense-repeat.png)