# NexacroSQLStudy
### Java, SQL, Nexacro


<br>




## 목적
SQL 쿼리 숙련도 향상을 위해 ChatGPT를 활용하여 테이블 학습을 수행하고, 요구사항을 요청해 전문성을 키우는것.

<br><br>
### 2023.12.08 ~ 2023.12.08
### 12. 요구사항: "모든 고객의 주문 상품 평균 금액보다 더 큰 금액의 고객 주문 상품 정보 조회"

```
1. 기능:
사용자는 각 고객의 주문 상품 평균 금액보다 더 큰 금액의 주문 상품명, 주문번호, 주문 상품 금액, 고객명, 및 고객 도시명을 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
"조회" 버튼: 모든 고객의 주문 상품 평균 금액보다 더 큰 금액의 고객 주문 상품 정보를 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 모든 고객의 주문 상품 평균 금액보다 더 큰 금액의 고객 주문 상품 정보를 표시

3. 동작:
사용자가 고객명을 입력하고 "조회" 버튼을 클릭하면, 시스템은 모든 고객의 주문 상품 평균 금액보다 더 큰 금액의 고객 주문 상품 정보를 조회하여 결과를 표시합니다.
결과는 모든 주문에 대한 정보여야 합니다.
결과에는 주문 상품명, 주문번호, 주문 상품 금액, 고객명, 및 고객 도시명이 포함되어야 합니다.
```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/e21e9454-2c65-4463-a283-e47459ca4d86)

![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/31682349-4891-4aab-b4b0-3e3e67ae07c9)


<br><br>
### 2023.12.08 ~ 2023.12.08
### 12. 요구사항: "N번 이상 주문한 고객의 고객 아이디, 고객명, 고객 거주 도시 조회"

```
1. 기능:
사용자는 N번 이상 주문한 고객의 고객 아이디, 고객명, 고객 거주 도시를 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
고객 조회" 버튼: N번 이상 주문한 고객의 고객 아이디, 고객명, 고객 거주 도시를 조회하는데 사용
결과를 표시할 그리드 또는 리스트: N번 이상 주문한 고객의 고객 아이디, 고객명, 고객 거주 도시를 표시

3. 동작:
사용자가 "고객 조회" 버튼을 클릭하면, 시스템은 N번 이상 주문한 고객의 고객 아이디, 고객명, 고객 거주 도시를 조회하여 결과를 표시합니다.
결과는 주문 횟수가 N번 이상인 고객들에 대한 정보여야 합니다.
결과에는 각 고객의 고객 아이디, 고객명, 고객 거주 도시가 포함되어야 합니다.
```


![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/524c48c7-d393-4ec9-8955-1fdbd8ecc939)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/0b23c075-9f40-4b97-82e1-9f1b7094a46c)


<br><br>

### 2023.12.08 ~ 2023.12.08
### 11. 요구사항: "특정 고객의 처음 구매일자, 최신 구매일자, 및 구매 간격 조회"

```
1. 기능:
사용자는 특정 고객의 처음 구매일자, 최신 구매일자, 및 두 날짜 간격을 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
구매 일자 조회" 버튼: 선택된 고객의 처음 구매일자, 최신 구매일자, 및 두 날짜 간격을 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 선택된 고객의 처음 구매일자, 최신 구매일자, 및 두 날짜 간격을 표시

3. 동작:
사용자가 고객 목록에서 특정 고객을 선택하고 "구매 일자 조회" 버튼을 클릭하면, 시스템은 선택된 고객의 처음 구매일자, 최신 구매일자, 및 두 날짜 간격을 조회하여 결과를 표시합니다.
결과에는 해당 고객의 처음 구매일자, 최신 구매일자, 및 두 날짜 간격이 포함되어야 합니다.
두 날짜 간격은 일수로 나타내어야 합니다.

```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/38781d7c-5ab5-42a2-ba5a-f1b81fb6c514)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/9fab1a83-3bf3-4b24-b1b5-afa73ff28db9)


<br><br>

### 2023.12.07 ~ 2023.12.07
### 10. 요구사항: "고객이 특정 연도에 주문한 주문 정보 조회"

```
1. 기능:
사용자는 특정 고객이 특정 연도에 주문한 주문 정보를 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
고객 입력 필드: 사용자가 조회할 고객을 입력하는데 사용
연도 입력 필드: 사용자가 조회할 연도를 입력하는데 사용
"고객 주문 조회" 버튼: 선택된 고객이 특정 연도에 주문한 주문 정보를 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 선택된 고객이 특정 연도에 주문한 주문 정보를 표시

3. 동작:
사용자가 고객을 입력하고 조회하고자 하는 연도를 입력하고 "고객 주문 조회" 버튼을 클릭하면,
시스템은 선택된 고객이 입력한 연도에 주문한 주문 정보를 조회하여 결과를 표시합니다.
결과에는 주문 번호, 주문일, 배송일, 주소 등이 포함되어야 합니다.

```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/ec48e8e5-8d27-46ee-8250-d816898e0dd8)

![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/716fdf32-1859-48d6-b701-62be9bb27379)


<br><br>

### 2023.12.07 ~ 2023.12.07
### 09. 요구사항: "부서별 소속 직원의 과거 급여 정보중 1983년 이후 데이터 조회"

```
1. 기능:
사용자는 각 부서에 소속된 직원들의 1983년 이후의 과거 급여 정보를 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
부서 목록 콤보박스 또는 드롭다운: 사용자가 조회할 특정 부서를 선택하는데 사용
"부서별 과거 급여 정보 조회" 버튼: 선택된 부서에 소속된 직원들의 1983년 이후 과거 급여 정보를 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 선택된 부서에 소속된 직원들의 1983년 이후 과거 급여 정보를 표시

3. 동작:
사용자가 부서 목록에서 특정 부서를 선택하고 "부서별 과거 급여 정보 조회" 버튼을 클릭하면, 시스템은 선택된 부서에 소속된 직원들의 1983년 이후의 과거 급여 정보를 조회하여 결과를 표시합니다.
결과에는 직원의 사번, 이름, 과거 급여 정보(날짜, 급여) 등이 포함되어야 합니다.
조회된 결과는 과거 급여가 낮은 순서대로 나열돼야 합니다.

```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/9bab8614-f7dd-4971-abd1-32287c4d1f35)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/62642ad0-faf0-488c-a5f6-2160b64aa3d8)


<br>
<br>

### 2023.12.07 ~ 2023.12.07
### 08. 요구사항: "직원 및 해당 직원을 관리하는 매니저의 이름 조회"

```
1. 기능:
사용자는 모든 직원들과 각 직원을 관리하는 매니저들의 이름을 함께 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
"직원 및 매니저 목록 조회" 버튼: 모든 직원들과 각 직원을 관리하는 매니저들의 이름을 함께 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 직원과 매니저의 이름을 함께 표시

3. 동작:
사용자가 "직원 및 매니저 목록 조회" 버튼을 클릭하면, 시스템은 모든 직원들과 각 직원을 관리하는 매니저들의 이름을 함께 조회하여 결과를 표시합니다.
결과에는 직원의 사번, 이름, 매니저의 이름 등이 포함되어야 합니다.

```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/b53ed048-c6fe-4f6d-9057-eba2f63f40ed)

![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/8486f68d-746a-4d17-bdc7-25ee6aa1c58f)



<br>
<br>

### 2023.12.07 ~ 2023.12.07
### 07. 요구사항: "승진한 직원 목록 조회"

```
1. 기능:
사용자는 N번 승진한 직원 목록을 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
승진 목록 조회" 버튼: N번 승진한 직원들의 목록을 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 최근 승진한 직원들의 목록을 표시

3. 동작:
사용자가  N번을 입력한 뒤 "승진 목록 조회" 버튼을 클릭하면, 시스템은 승진한 직원들의 목록을 조회하여 결과를 표시합니다.
결과에는 직원의 사번, 이름 등이 포함되어야 합니다.
```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/cb593bd8-1fe4-4a56-bc8a-ce7fffc74520)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/b88523f5-3b88-4036-a333-3bd509f84f5c)


<br>
<br>

### 2023.12.06 ~ 2023.12.06
### 06. 요구사항: " 부서의 퇴사자 목록 조회"

```
1. 기능:
사용자는 퇴사자 목록을 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
"퇴사자 목록 조회" 버튼: 퇴사자들의 목록을 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 퇴사자들의 목록을 표시

3. 동작:
"퇴사자 목록 조회" 버튼을 클릭하면, 시스템은 퇴사자들의 목록을 조회하여 결과를 표시합니다.
결과에는 퇴사 예정자의 사번, 이름, 퇴사, 현재 속한 부서 등이 포함되어야 합니다.
```


![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/0f284916-d956-4bd1-9da6-b836d48d55d3)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/812b6dc2-cc9a-41b1-b690-46caf713473b)


<br>
<br>


### 2023.12.06 ~ 2023.12.06
### 05. 요구사항: "모든 부서의 직원들 중 연봉 상위 N명 조회"

```
1. 기능:
사용자는 모든 부서에 속한 직원들 중에서 연봉 상위 N명을 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
각 부서의 상위 N명을 입력할 수 있는 텍스트 상자 또는 숫자 입력 필드
"조회" 버튼: 입력된 N명의 부서 목록을 조회하는 데 사용
결과를 표시할 그리드 또는 리스트: 연봉 상위 N명의 직원 목록을 표시

3. 동작:
상위 N명을 입력한 뒤 "연봉 상위 N명 조회" 버튼을 클릭하면, 시스템은 모든 부서의 직원들 중에서 연봉이 상위 N명인 직원들을 조회하여 결과를 표시합니다.
결과에는 직원의 부서, 이름, 현재 연봉 등이 포함되어야 합니다.
```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/4bad77ea-82ec-4ec7-a1b1-8963f10a1ac2)

![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/a67886e4-6066-4db6-9652-d0362890dd7a)


<br>
<br>

### 2023.12.06 ~ 2023.12.06
### 04. 요구사항: "부서별 연도별 평균 급여 및 인원 통계 조회"

```
1. 기능:
사용자는 각 부서별로 부서 내 직원들의 연도별 평균 급여와 해당 부서의 연도별 총 인원수를 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
최소 연도와 최대 연도를 입력할 수 있는 텍스트 상자 또는 숫자 입력 필드
"조회" 버튼: 입력된 최소 평균 연도와 최대 평균 연도 범위 내에 속하는 부서 목록을 조회하는 데 사용
결과를 표시할 그리드 또는 리스트: 조회된 부서들의 목록을 표시
3. 동작:
사용자가 최소 연도와 최대 연도를 입력하고 "조회" 버튼을 클릭하면, 시스템은 해당 급여 범위 내에 속하는 부서 목록을 조회하여 결과를 표시합니다.

```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/07963f22-8b9c-4431-b063-22a9fe3d07a6)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/d4fb1b22-f6ad-4c82-8340-2f60b82cadae)


<br>
<br>



### 2023.12.06 ~ 2023.12.06
### 03. 요구사항: "특정 급여 범위 내의 직원 목록 조회"

```
1. 기능:
사용자는 특정 급여 범위 내에 속하는 직원들의 목록을 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
최소 급여와 최대 급여를 입력할 수 있는 텍스트 상자 또는 숫자 입력 필드
"조회" 버튼: 입력된 최소 급여와 최대 급여 범위 내에 속하는 직원 목록을 조회하는데 사용
결과를 표시할 그리드 또는 리스트: 조회된 직원들의 목록을 표시

3. 동작:
사용자가 최소 급여와 최대 급여를 입력하고 "조회" 버튼을 클릭하면, 시스템은 해당 급여 범위 내에 속하는 직원들의 목록을 조회하여 결과를 표시합니다.
결과에는 직원의 사번, 이름, 현재 속한 부서이름, 현재 급여 등이 포함되어야 합니다.
조회된 목록은 급여가 낮은 순서부터 높은 순서로 정렬되어 표시돼야 합니다.
```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/bf342bf0-50e6-4968-a8f1-7054efad3f84)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/7eece70b-b626-48ec-828e-5d1ea30d6f6f)


<br>
<br>

### 2023.12.06 ~ 2023.12.06
### 02. 요구사항: "직원의 최근 부서 근무 이력 조회"

```
1. 기능:
사용자는 특정 직원의 최근 부서 근무 이력을 조회할 수 있는 기능을 사용할 수 있어야 합니다.

2. 화면 요소:
직원 목록 콤보박스 또는 드롭다운: 사용자가 조회할 특정 직원을 선택하는데 사용
"근무 이력 조회" 버튼: 선택된 직원의 최근 부서 근무 이력을 조회하는데 사용

3. 동작:
사용자가 직원 목록에서 특정 직원을 선택하고 "근무 이력 조회" 버튼을 클릭하면, 시스템은 선택된 직원의 최근 부서 근무 이력을 조회하여 결과를 표시합니다.
최근 부서 근무 이력은 입사일로부터 현재까지의 기간 동안의 부서 이력 중에서 가장 최근의 것을 나타냅니다
```

![요구사항](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/64b32d5a-81e5-456e-9a5f-a274143fa128)


![쿼리](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/5dbd8e0d-3359-4cdb-9df7-23d4dad4e79e)

<br>
<br>

### 2023.12.06 ~ 2023.12.06
### 01. 요구사항: "부서별 평균 급여 조회"
```
1. 기능:
사용자는 각 부서별로 평균 급여를 조회할 수 있어야 합니다.
조회 시에는 부서 목록을 선택하고, 선택한 부서의 평균 급여가 표시되어야 합니다.

2. 화면 요소:
부서 목록 콤보박스 또는 드롭다운: 조회할 부서를 선택하는데 사용
선택된 부서의 평균 급여를 표시하는 레이블 또는 텍스트 필드

3. 동작:
사용자가 부서 목록에서 특정 부서를 선택하면, 선택된 부서의 평균 급여가 화면에 표시됩니다.
```

![1](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/4e5917e7-4444-408e-b91a-89134184aedb)


![2](https://github.com/fxzz/NexacroSQLStudy/assets/3148006/41691c59-06b5-4e5d-bd81-c562a602bd38)



<br>
<br>


