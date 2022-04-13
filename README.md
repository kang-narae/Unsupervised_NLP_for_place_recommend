# Unsupervised_NLP_for_place_recommend


## routing


### 1. search_place_main  ->  search_place_result

search_place_main 페이지에서 search_keyword를 search_btn으로 받은 것을
1) <그대로 전송> search_place_result 페이지의 search_keyword로 보냅니다.
2) <함수 구동> search_keyword로 검색하여 유사한 여행지(title) 뽑은 것을 search_place_result 페이지의 specific_place_name에 보냅니다.


### 2. search_place_result  ->   place_content

search_place_result 페이지에서 specific_place_name을 누르면 해당 단어를 넣어
1) <그대로 전송> place_content 페이지의 specific_palce_name으로 보냅니다.
2) <함수 구동> specific_place_name 과 유사한 여행지(title) 뽑은 것을 place_content 페이지의  similar_place_name에 보냅니다.