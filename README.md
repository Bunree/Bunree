a = {'чайка': '1', 'ворона': '2', 'голубь': '3', 'ласточка': '4', 'калибрия': '5', 'павлин': '6', 'синица': '7', 'снегирь': '8', 'страус': '9', 'воробей': '10'}


import cv2
r = input('введите название птицы ')

if a[r] == '2':
    img = cv2.imread('image/crow.jpg')
    cv2.imshow('bird', img)
    cv2.waitKey(0)
elif a[r] == '1':
    img = cv2.imread('image/chuika.jpg')
    cv2.imshow('птица', img)
    сv2.waitKey(0)
elif a[r] == '3':
    img = cv2.imread('image/golyb.jpg')
    cv2.imshow('птица', img)
    cv2.waitKey(0)
