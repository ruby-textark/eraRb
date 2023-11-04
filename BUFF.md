# 새 버프 작성할때 참고

## 설명

각 캐릭터의 TCVAR는 1001번부터 버프를 위해 할당되어 있다.
버프의 이름은 TCVAR에서 선언해주고, 버프 효과 처리는 ERB/QUEST/BATTLE/BUFFS에서 처리함.
`applyBuffTo()`, `clearBuff()`, `hasBuff()`를 활용하면 유용하다.

### 체크리스트

- [ ] ERB/QUEST/BATTLE/BUFFS/~.ERB 작성
