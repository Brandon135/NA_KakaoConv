# NA_KakaoConv
Analizing KakaoTalk txt 
1. 해군사관학교 부적절한 언어 사용 식별 > 부적절한 언어사용을 줄이기 위해 어떠한 상황에서 부적절한 언어 사용이 발생하고 이를 감소할수있는 과정 예측 필요
2. 부적절한 언어 사용이 발생하는 과정 분석 > 1:1, 다중대화 상황
3. 부적절한 언어 사용이 발생하는 시간대 분석 > 여러 단체 카카오톡망에서 사용되는 무작위 내용중 단어의 줄임말이나 욕설이 사용되는 빈도 분석


분석방법
1. 카카오톡 txt -> csv
2. csv 파일 날짜, 시간, 이름, 대화내용 대입
대화내용 : 일반 대화
1. 반복되는 대화 제외
2. 공지, 인계사항, 장문 제외

-부적절한 언어 사용이 발생하는 과정 분석
1. 대화의 시작점 찾기
2. 대화의 전개 :  1:1, 다중대화 상황


분석 바탕으로 어느 시기에 사용되는지 알수있음.

K-Core
Gensim

인공지능 사용

n월-> []단어 사용 및 부적절 단어 빈도 증가 %, 가장 많은 대화 주체, 등등 여러 데이터 추출 가능

근데 만약 한가지만 추출해야한다면?


https://m.blog.naver.com/ttozysoocute/221905774970
자연어처리 

