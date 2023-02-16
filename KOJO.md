# 새 구상 작성할때 참고

## 설명

각 이벤트에 대해 `onEvent_m`과 `onEvent_e`꼴의 두 리스너를 작성해 주어야 한다.
각각 해당 이벤트에 대한 마스터의 반응과 실행자(enemy)의 반응을 의미함.
이것은 ERB/KOJO에 각각 MASTER, ENEMY/LISTENERS에 저장되어 있으므로 활용하여 작성하면 된다.
추가로 ENEMY/TEMPLATE에 해당 이벤트에 대한 기본 템플릿 작성도 잊지 말것

### 체크리스트

- [ ] ERB/KOJO/MASTER/ON~.ERB 작성
- [ ] ERB/KOJO/ENEMY/LISTENERS/ON~.ERB 작성
- [ ] ERB/KOJO/ENEMY/TEMPLATE/ON~.ERB 작성
