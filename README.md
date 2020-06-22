#relatedAnimation\
Javascript practice, example coied from habr.com a author Anton Shevchuk\
Russian translate\
Line 0: после загрузки страницы (DOM is ready)\
Line 1: привязываемся к событию click для элемента \<a class="run"\>\
Line 2: манипулируем элементом \<div id="box"\> - уменьшаем его прозрачность до\
0.1, наращиваем позицию left еще на 400px, со скоростью 1200 (milliseconds)\
Line 3: затем медленно изменяем следующие параметры: opacity=0.4, top=160px,\
height=20, width=20; скорость анимации указывается вторым параметром: "slow",\
"normal", "fast" или в миллисекундах\
Line 4: затем opacity=1, left=0, height=100, width=100, скорость - "slow"\
Line 5: затем opacity=1, left=0, height=100, width=100, скорость - "slow"\
Line 6: затем top=0, скорость - "fast"\
Line 7: затем slideUp (с дефолтной скоростью анимации - "normal")\
Line 8: затем slideDown, скорость - "slow"\
Line 9: возвращаем false для того чтобы браузер не перешел по ссылке\
English translate\
Line 0: after download page (DOM is ready)\
Line 1: attached to the click event for element \<a class="run"\>\
Line 2: manipulate the element \<div id="box"\> - reduce its transparency to\
0.1, increase the left position by another 400px, with speed 1200 (milliseconds)\
Line 3: then slowly change the following parameters: opacity=0.4, top=160px,\
height=20, width=20; animation speed is indicated by the second parameter: "slow",\
"normal", "fast" or in milliseconds\
Line 4: then opacity=1, left=0, height=100, width=100, speed - "slow"\
Line 5: then opacity=1, left=0, height=100, width=100, speed - "slow"\
Line 6: then top=0, speed - "fast"\
Line 7: then slideUp (default animation speed - "normal")\
Line 8: then slideDown, speed - "slow"\
Line 9: return false so that the browser does not follow the link

