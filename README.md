# NLP_Naver-New-Analysis

### 다음 뉴스 기사 분석  
1. 다음 뉴스를 크롤링하여 데이터셋 구축
  * 정치, 경제, 국제, 문화, IT
2. 한국어 불용어 및 정규표현식을 활용하여 텍스트에 대한 전반적인 전처리 진행
3. TF-IDF를 통한 token간 유사도 파악 및 Word Clouding 도식화
  * 크롤링한 시점의 핫 토픽을 한눈에 파악 가능
4. TF-IDF의 TDM으로 감성분석 진행(Tensorflow)
5. 주제분석(LDA)을 통한 주제 별 해당 기간 핫토픽 파악

< 예시 >  
<img width="410" alt="image" src="https://user-images.githubusercontent.com/87609200/215308964-6669ab27-d065-4f64-b315-cdfa3417d39b.png">  

<img width="314" alt="image" src="https://user-images.githubusercontent.com/87609200/215308967-c5fa15e9-1393-4de5-b349-fa1e62e4ef44.png">  

### 느낀점  
* 뉴스 기사를 다 읽지 않아도 해당 시점의 주제별 주요 토픽을 데이터를 통해 알 수 있었음
  * 특히 `Word Clouding`으로 핫 토픽 파악이 가장 쉬웠으며, 제3자에게 PR을 할 경우에도 해당 자료를 보여주며 커뮤니케이션하기 수월하였음
* 주제분석(LDA)를 진행하며 임의로 설정된 토픽 수로 중요 token을 파악하며 더 많은 데이터가 보장된다면 더욱 유의미한 insight를 도출할 수 있겠다는 가능성을 
