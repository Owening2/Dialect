# Dialect-translator


##사전 생성

###사투리사전 (단어/인덱스)
###변수명: dialect_to_index
###형식 : dict 
###ex) {“사투리 단어” : 인덱스}
###사투리사전(인덱스/단어)
###변수명 : index_to_dialect
###형식 : dict 
###ex) {인덱스 : “사투리 단어”}
###표준어사전 (단어/인덱스)
###변수명: standard_to_index
###형식 :dict 
###ex)  {“표준어 단어” : 인덱스}
###표준어사전(인덱스/단어)
###변수명 : index_to_standard
###형식 : dict 
###ex) {인덱스 : “표준어 단어”}

##사투리, 표준어 사전 생성 함수
  ###make_dict(raw_data)
##사투리 표준어 쌍 생성 함수 
  ###make_pair(raw_data)
