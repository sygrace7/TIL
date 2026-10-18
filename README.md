#### 토큰화(Tokenization)

1. 단어 토큰화(Word Tokenization)
WordPunctTokenizer: 구두점을 별도로 분류,  Don't를 Don과 '와 t로 분리하고 Jone's를 Jone과 '와 s로 분리
케라스의 text_to_word_sequence: 기본적으로 모든 알파벳을 소문자로 바꾸면서 마침표나 컴마, 느낌표 등의 구두점을 제거(하지만 don't나 jone's와 같은 경우 아포스트로피는 보존)

2. 문장 토큰화(Sentence Tokenization)
NLTK: 단순히 마침표를 구분자로 하여 문장을 구분하지 않았기 때문에, Ph.D.를 문장 내의 단어로 인식 / 한국어 가능
KSS(Korean Sentence Splitter): 

#어절 토큰화는 한국어 NLP에서 지양

한국어 토큰화에서는 형태소(morpheme) 란 개념을 반드시 고려


