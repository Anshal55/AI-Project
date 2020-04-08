
news= input("Enter the news:")
list = ["happy","win","benefit","importance","boon"]
flag = False
for x in list:
    for y in news.split():
        if x ==  y:
            flag = True
            break
if flag:
    print("flag is good")
    
l1 = ["sad","loose","crisis","increased"]
flag = False
for x in l1:
    for y in news.split():
        if x ==  y:
            flag = True
            break
if flag:
    print("flag is bad")

l2 = ["allusive","apathetic","baffled","candid","ceremonial"]
flag = False
for x in l2:
    for y in news.split():
        if x ==  y:
            flag = True
            break
if flag:
    print("flag is neutral")

