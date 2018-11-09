from math import sqrt
def rozwiaz_rownanie(a,b,c):
    delta = b**2 - 4*a*c
    pierw = sqrt(delta)
    print("Pierwiastek z delty:{}".format(pierw))
    if delta>0:
        x1=(-b-pierw)/(2*a)
        x2=(-b+pierw)/(2*a)
        print("Rozwiazanie:x1={},x2={}".format(x1,x2))
    elif delta==0:
        x1=-b/(2*a)
        print("Jedno rozwiazanie:x1={}".format(x1))
    else:
        print("Delta ujemna, brak rozwiazania")
        
a=float(input("Podaj a:"))
b=float(input("Podaj b:"))
c=float(input("Podaj c:"))

rozwiaz_rownanie(a,b,c)
