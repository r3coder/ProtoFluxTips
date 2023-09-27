

# Indirect




Write 할 때, String


# Increment
## ValueIncrement\<T>

연결된 Variable의 값을 1 증가 시킵니다.

다른 데이터 타입을 Variable에 연결해도 자동으로 맞는 노드로 변환됩니다.

- `bool`, `char`, `LightType` 등 숫자 값을 가지지 않는 데이터 타입: 아무 일도 일어나지 않습니다.
- `sbyte`, `int`, `float` 등 숫자 값을 가지는 단일 데이터 타입: 값이 1 만큼 증가합니다.
- `float2x2`, `float3x3` 등 숫자 값을 가지는 행렬 형태의 데이터: 주 대각 성분의 값만 1 증가합니다.
- 