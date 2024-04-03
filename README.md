EDA 분석 결과
Company - Employee Distribution: 대부분의 회사에서 직원 수는 소수에 집중되어 있으며, 일부 회사에서 매우 높은 직원 수를 보여준다. 이는 특정 대기업이나 매우 큰 기업의 존재를 시사한다.

Recruitment - Education Level Distribution: 대다수의 채용 공고는 특정 교육 수준(4가 가장 높은 빈도)을 요구하는 것으로 보인다.

Recruitment - Qualifications Distribution: 대부분의 채용 공고는 비슷한 수준(1)의 자격 요건을 가지고 있다. 이는 특정 업계나 직무에서 일반적으로 요구되는 자격이 표준화되어 있을 수 있음을 나타낸다.

Resume - Hope Salary Distribution & Last Salary Distribution: 기대 급여(hope_salary)와 마지막 급여(last_salary) 모두 넓은 범위에 분포하고 있으며, 일부 극단적인 값(outliers)을 가지고 있다. 이는 개인별로 기대하는 급여가 매우 다양함을 보여준다.

Resume Education - University Score Distribution: 대학 점수(univ_score)는 주로 높은 점수대에 분포하고 있으며, 100점 만점 기준으로 대부분 60점 이상의 점수를 가지고 있다.

Resume Dataset Correlation: 졸업 연도(graduate_date)와 학위(degree) 간에는 약간의 양의 상관 관계가 있으며, 이는 학위가 높을수록 최근에 졸업한 경향이 있을 수 있음을 나타낸다. 기대 급여와 마지막 급여 간에는 중간 정도의 양의 상관 관계가 있어, 이전 급여가 높았던 사람이 더 높은 급여를 기대할 수 있음을 시사한다.

Recruitment Dataset Correlation: 지역 관련 변수(address_seq1, address_seq2, address_seq3)는 서로 상관 관계가 높은 것으로 나타난다. 이는 특정 지역이 특정 산업 또는 직업과 관련이 있을 수 있음을 의미할 수 있다.

Pair Plot of Numeric Columns in Resume Dataset: 이 플롯을 통해 수치형 변수들 간의 관계를 한눈에 볼 수 있다. 특히, 마지막 급여(last_salary)와 기대 급여(hope_salary) 간에는 명확한 선형 관계가 보인다.

Scatter Plot of Hope Salary vs. Last Salary: 이 산점도는 기대 급여와 마지막 급여 간의 관계를 더 명확하게 보여준다. 특히 마지막 급여가 높은 구간에서는 기대 급여도 비례하여 높아지는 경향을 보여준다.
