2015108199 이민재

별똥별 데이터를 활용하여 별똥별 위치와 속도 예측


* kaggle 에서 제공하는 Fireballs 데이터를 이용하여 별똥별의 위치와 속도를 예측한다.
* PredictionUtil 라이브러리를 활용한다.
* 데이터 : https://www.kaggle.com/nasa/fireballs/data


1. 데이터 불러오기

cneos_fireball_data.csv 를 pycharm으로 불러온다.

#from prediction_util import PredictionUtil

gildong = PredictionUtil()
gildong.read('cneos_fireball_data.csv')
gildong.show_unique_column()
