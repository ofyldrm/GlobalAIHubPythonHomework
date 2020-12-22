# python-odevlerim
vize1 = input("1. Vize:") 
arasınav = input("arasınav") 
Final = input("Final:") 
sonuc = int(vize1)*(2/10) + int(arasınav)*(3/10) + int(Final)*(5/10) 
if(sonuc>=90): 
print("AA")  
elif(70>sonuc>=90): 
print("BB") 
elif(50>sonuc>=70): 
print("CC") 
elif(30>sonuc>=50): 
print("DD") 
elif(sonuc>=30): 
print("FF")
