# 3rd-grade-lab-prof.-H.R.Ahn-
#LSTM #mimic3 #medical_data #health_care_data #의료데이터 #건강데이터 #ML #machine-learning #머신러닝 #data_processing
```
~072_, 데이터 이해, 전처리, lstm 이해
  0629 - putty 첫 사용, 다시 만난 win scp
  0720 - 교수님 피드백, 더 빠른 알고리즘 추천, dic_sub, dic_item 생성, dic_sub_charttime2idx 생성 시도.
  0722 - dic_sub_charttime2idx value 설정 오류
  0723 - dic_sub_charttime2idx 정상 생성, time_idx - idx가 계속 0이 나올 수가 있나? index인데..? -> 나올 수 있을지도..?
         에러 방지를 위해서는 출력시 최대한 print를 쓰는게 좋다.
  ... 파일이 날라갔다. 복구는 불가능하다고 하셨다. - 무슨 math어쩌고가 뜨더니 파일이 복구됐다. 전에는 복구가 안됐어서 반포기상태였는데 다행이다. 앞으론 학교에서 깃헙에까지 백업하고 와야지.
  0724 - 최종 3차원 array 생성 코드에 문제 있나 확인. 문제 없음. 실행 됐고 array 생성 완료. (time_idx - idx가 계속 0이 나올 수 있는거였음. itemid 고려하면 가능)
         최종 array 파일로 저장. => npy, pickle 두 가지 버전으로 저장 가능.
  0727 - lstm 실행해봄, 정확도 최고 63%나옴. overfitting 심했음.
         교수님 피드백, 코드 뒤엎으라고 하심.
         machine learning 및 rnn 설명 또 들음.
         Jeongmin Lee (leej35) 이 분 논문이 우리가 하려는 거랑 제일 비슷했음.
```
0727 피드백
![KakaoTalk_20210727_155706173](https://user-images.githubusercontent.com/56033779/127132809-133d3eb0-1c60-4ae0-b512-22e9b4188a25.jpg)
