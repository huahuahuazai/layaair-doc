#타임 애니메이션

###### *version :2.1.0beta   Update:2019-6-13*

재생 애니메이션이 끝났다. 애니메이션의 재생 속도 제어 및 재생 중단 및 재생 속도 설정을 위해 애니메이션 재생 속도를 0 으로 설정하면 된다. 계속 재생 속도는 1.


```typescript

//暂停动画
animator.speed = 0.0;

//播放动画
animator.speed = 1.0;
```


속도가 1 시보다 높을 때 애니메이션은 가속화 상태다.