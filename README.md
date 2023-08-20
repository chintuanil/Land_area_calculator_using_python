# Land_area_calculator_using_python
n=float(input("select your choice to know your land\n"
              "1 : acre to guntas \n"     
              "2 : acres to gajam \n"
               " 3: acres to sq.ft\n"
              " 4 : guntas to acres\n"
              "5 : guntas to gajam \n"
              "6 : guntas to sq.ft \n"
               "7: gajam or square yards to acres \n"
              "8 : gajam to guntas\n"
              "9 :gajam to sq.ft \n"
              "10: sq.ft to acres\n"
              "11:sq.ft to guntas \n"
              "12 : sq.ft to gajam \n"))

m = int(input("how many different places you have land "))
print("enter your land in different places one by one")


for l in range(0 ,m):
    if(n==1):
        total_area = 0
        print("calculate your land in acres to guntas")
        acre=float(input("enter your area in acres"))
        guntas=acre*40
        total_area1=total_area+guntas
        total_area=round(total_area1,4)
        print("your total area is" , total_area, " guntas")
    elif (n == 2):
        total_area = 0
        print("calculate your land in acres to gajam")
        acres = float(input("enter your area in acres "))
        gajam = acres * 4840
        total_area1 = total_area + gajam
        total_area = round(total_area1, 4)
        print("you total area is", total_area, "  square yards or gajam ")
    elif (n == 3):
        total_area = 0
        print("calculate your total land in acres to sqare feets")
        acres = float(input("enter you land in acre "))
        total_area1 = acres * 43560
        total_sqft = total_area + total_area1
        total_area = round(total_sqft, 4)
        print("your total area is", total_area, "sq.ft")

    elif(n == 4):
        total_area = 0
        print("calculate your land in guntas to acres")
        guntas = float(input("enter your area in guntas"))
        total_acre = guntas / 40
        total_area1=total_area+total_acre
        total_area=round(total_area1,4)
        print("your total area is",total_area ,"acres")
    elif (n == 5):
        total_area = 0
        print("calculate your land in guntas to gajam")
        guntas = float(input("enter your land in guntas"))
        gajam = guntas * 121
        total_area1 = total_area + gajam
        total_area = round(total_area1, 4)
        print("your total area is", total_area, " square quard or gajam")
    elif (n == 6):
        total_area = 0
        print("calculate your total guntas to sqare feet")
        guntas = float(input("enter you land in guntas "))
        total_sqft = guntas * 1089
        total_area1 = total_area + total_sqft
        total_area = round(total_area1, 4)
        print("your total area is", total_area, "sq.ft")

    elif(n==7):
        total_area = 0
        print("calculate your land gajam to acres")
        gajam=float(input("enter your land in gajam "))
        acres=gajam/4840
        total_area1=total_area+acres
        total_area=round(total_area1,4)
        print("your total area is ", total_area, "acres")

    elif(n==8):
        total_area = 0
        print("calculate your land in gajam to gunta")
        gajam=float(input("enter your land in gajam "))
        gunta=gajam/121
        total_area1=total_area+gunta
        total_area=round(total_area1,4)
        print("your total area is ", total_area , "gunta")
    elif (n == 9):
        total_area = 0
        print("calculate your total square yard or gajam  to sq.ft")
        gajam = float(input("enter you land in gajam"))
        total_sqft= gajam*9
        total_area1=total_area+total_sqft
        total_area = round(total_area1, 4)
        print("your total area is", total_area, "sq.ft")

    elif (n == 10):
        total_area = 0
        print("calculate your total land in  sqare feets to acres")
        sqft = float(input("enter you land in  sqare feets "))
        total_area1 = sqft/43560
        total_sqft = total_area + total_area1
        total_area = round(total_sqft, 4)
        print("your total area is", total_area, "acres")

    elif (n == 11):
        total_area = 0
        print("calculate your total  sqare feet to guntas ")
        guntas = float(input("enter you land in sq.ft "))
        total_sqft = guntas / 1089
        total_area1 = total_area + total_sqft
        total_area = round(total_area1, 4)
        print("your total area is", total_area, "guntas")

    elif (n == 12):
        total_area = 0
        print("calculate your total  sq.ft to sq.yards")
        gajam = float(input("enter you land in sq.feet"))
        total_sqft= gajam/9
        total_area1=total_area+total_sqft
        total_area = round(total_area1, 4)
        print("your total area is", total_area, "gajam")





