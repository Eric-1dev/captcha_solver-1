
RU  

https://fssp.gov.ru/iss/ip/ captcha датасет (test,train), порядка ~40000 картинок. Используется для обучения нейросети по разгадыванию капчи https://fssp.gov.ru/iss/ip/  

Автоматическое решение данной капчи находится в соседнем репрозитории. (было собрано с https://fssp.gov.ru/iss/ip/ c wav )  


Решатель капчи fssp.gov.ru , для примера  

import requests  
import base64  
solve/solve_fssp.py  
скачивает с fssp.gov.ru , сохраняет 1 капчу, и решает ее.  
Capthca = 7с5г2    




EN  

fssp.gov.ru captcha dataset, aproximetly ~40000 (test,train) recognized pictures. Used for training neural network.  
The automatic solution of this captcha is located in a nearby repository. (collected from https://fssp.gov.ru/iss/ip/ )  


For example:  

import requests  
import base64  
solve/solve_fssp.py  
Download and save 1 captcha from fssp.gov.ru and solve it.  
Capthca = 7с5г2  