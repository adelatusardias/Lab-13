# Lab-13
Rekrusif
def total_prima(n):
    numr=n*100
    num=[]
    res=[]
    for l in range(1,numr):
        for q in range(2,l):
            if(l%q==0):
                break
        else:
            num.append(l)
    for i in range(1,hasil+1):
        res.append(num[i])
    f=sum(res)
    print(f)
hasil=10
total_prima(hasil)
