# pythonpow
acos(x)
    Zwraca arcus cosinus argumentu x. 

asin(x)
    Zwraca arcus sinus argumentu x. 

atan(x)
    Zwraca arcus tangens argumentu x. 

atan2(y, x)
    Zwraca wartość atan(y / x). 

ceil(x)
    Zwraca najmniejszą liczbę całkowitą nie mniejszą od argumentu x w postaci liczby zmiennoprzecinkowej. 

cos(x)
    Zwraca cosinus argumentu x. 

cosh(x)
    Zwraca cosinus hiperboliczny argumentu x. 

degrees(x)
    Przekształca kąt x z radianów na stopnie. 

exp(x)
    Zwraca wartość e**x. 

fabs(x)
    Zwraca moduł (wartość bezwzględną) argumentu x. 

floor(x)
    Zwraca quotpodłogę (największą liczbę całkowitą nie większą od) argumentu x w postaci liczby zmiennoprzecinkowej. 

fmod(x, y)
    Zwraca fmod(x, y), tak, jak to zostało zdefiniowane w zgodnej z platformą bibliotece języka C. Należy zauważyć, że wyrażenie języka Python x % y nie musi zwrócić takiego samego rezultatu. 

frexp(x)
    Zwraca mantysę i cechę argumentu x jako parę (m, e). Wartość m jest liczbą zmiennoprzecinkową, natomiast wartość e jest liczbą całkowitą. Liczby te spełniają równanie: x == m * 2**e. Jeżeli argument x ma wartość zero, zwracana jest para (0.0, 0), w przeciwnym przypadku spełniona jest nierówność 0.5 <= abs(m) < 1. 

hypot(x, y)
    Zwraca wartość sqrt(x*x + y*y). Jest to długość przeciwprostokątnej w trójkącie prostokątnym o przyprostokątnych, których długości są równe x oraz y, lub odległość punktu (x, y) od środka układu współrzędnych. 

ldexp(x, i)
    Zwraca wartość x * (2**i). 

log(x[, podstawa_logarytmu])
    Zwraca logarytm o podstawie podstawa_logarytmu argumentu x. Jeżeli podstawa_logarytmu nie zostanie podana, zwracany jest logarytm naturalny argumentu x. Zmieniono w wersji 2.3: base argument added. 

log10(x)
    Zwraca logarytm o podstawie 10 argumentu x. 

modf(x)
    Zwraca część ułamkową i całkowitą argumentu x. Obydwie wartości mają znak liczby x. Wartość całkowita zwracana jest w postaci liczby zmiennoprzecinkowej. 

pow(x, y)
    Zwraca wartość x**y. 

radians(x)
    Przekształca kąt x ze stopni na radiany. 

sin(x)
    Zwraca sinus argumentu x. 

sinh(x)
    Zwraca sinus hiperboliczny argumentu x. 

sqrt(x)
    Zwraca pierwiastek kwadratowy argumentu x. 

tan(x)
    Zwraca tangens argumentu x. 

tanh(x)
    Zwraca tangens hiperboliczny argumentu x. 

Należy zauważyć, że funkcje frexp() i modf() używane są inaczej, niż ich odpowiedniki z języka C: pobierają one pojedynczy argument i zwracają parę wartości. W języku C zwracają drugą wartość za pośrednictwem wskaźnika przekazanego jako drugi argument funkcji (różnica wynika z faktu, iż w języku Python nie występuje pojęcie wskaźników na zmienne).

Moduł definiuje również dwie matematyczne stałe:

pi
    Stała pi. 

e
    Stała e. 
    
    
