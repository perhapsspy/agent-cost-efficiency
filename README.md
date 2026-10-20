# Agent Cost Efficiency

[한국어](README.md) | [English](README.en.md)

필요한 검증과 결과 품질을 유지하며 에이전트 작업의 불필요한 토큰·시간·도구 실행 비용을 줄이는 스킬입니다. 필요한 근거를 좁게 읽고 재사용하며, 실행·관측·위임의 범위를 정하고 다음 단계에 필요한 상태를 남깁니다.

## 빠른 시작

```bash
npx skills add perhapsspy/agent-cost-efficiency
```

또는 `skills/agent-cost-efficiency` 폴더를 사용하는 에이전트의 스킬 디렉터리에 복사합니다.

평소처럼 작업을 요청하면 명확한 초과 비용 위험이 있을 때 참여합니다. 직접 요청할 수도 있습니다.

```text
agent-cost-efficiency 스킬로 이 긴 조사의 읽기·출력·재시도 비용을 줄이면서 필요한 검증은 끝내줘.
```

## 이런 때 사용

- 넓은 저장소 탐색이나 큰 diff·로그·테스트 출력을 다룰 때
- 출력이 작아도 실행·재시도 비용이 커서 이전 결과로 다음 실행이나 관측을 선택해야 할 때
- 브라우저·UI 확인이나 진행 관측이 반복될 때
- 위임 비용과 중복 작업을 제한해야 할 때
- 긴 작업의 단계가 바뀌어 재개 가능한 상태를 남겨야 할 때
- 상시 읽는 지침이나 항상 제공되는 도구·스킬을 늘리기 전에 반복 비용을 판단할 때

작은 수정, 직접 답변과 일반적인 테스트 실행은 기존 작업 방식으로 처리합니다.

## 더 보기

- 스킬 상세 규칙: [English](skills/agent-cost-efficiency/SKILL.md) | [한국어](skills/agent-cost-efficiency/SKILL.ko.md)
- 개편과 유지 기준: [스킬 방향](docs/skill-direction.md)
- 비용 위험 판단: [작업 비용 신호](docs/reference/observed-token-patterns.md)

## 지원

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/perhapsspy)

## 라이선스

[MIT](LICENSE)
