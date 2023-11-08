# python

mahsulotlar = { # Do'kondagi mahsulotlar
    'olma':10000,
    'anjir':25000,
    'anor':20000,
    'uzum':40000,
    'shaftoli':30000 #vh...
    }
bozorlik = ['anor','uzum','non','baliq']

for m in mahsulotlar:
    if m in bozorlik:
        print(f"{m.title()} {mahsulotlar[m]} so'm")
    else:
        print(f"Iltimos, do'koningizga {m} ham olib keling")
