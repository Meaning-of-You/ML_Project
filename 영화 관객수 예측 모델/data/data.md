# [문화] 영화 관객수 예측 모델 개발

>  DACON 데이터 활용

링크: https://dacon.io/competitions/open/235536/overview/description



### [Files]

##### movies_train.csv

2010년대 한국에서 개봉한 한국영화 600개에 대한 감독, 이름, 상영등급, 관객수 등의 정보가 담긴 데이터

##### movies_test.csv

관객수를 제외하고 movies_train과 동일

##### submission.csv

제출 파일의 형식



### [Data fields]

##### movies_train.csv

2010년대 한국에서 개봉한 한국영화 600개에 대한 감독, 이름, 상영등급, 관객수 등의 정보가 담긴 데이터

- `title` : 영화의 제목
- `distributor` : 배급사
- `genre` : 장르
- `release_time` : 개봉일
- `time` : 상영시간(분)
- `screening_rat` : 상영등급
- `director` : 감독이름
- `dir_prev_bfnum` : 해당 감독이 이 영화를 만들기 전 제작에 참여한 영화에서의 평균 관객수(단 관객수가 알려지지 않은 영화 제외)
- `dir_prev_num` : 해당 감독이 이 영화를 만들기 전 제작에 참여한 영화의 개수(단 관객수가 알려지지 않은 영화 제외)
- `num_staff` : 스텝수
- `num_actor` : 주연배우수
- `box_off_num` : 관객수



##### submission.csv

제출 파일의 형식 

