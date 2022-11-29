# wap-to-take-key-and-value-from-the-user-and-create-a-dictionary-real-a-key-from-the-user-if-key-is-e
d1=input("data1:") d2=input("data2:") l1=d1.split(",") l2=d2.split(",") dict1=dict(zip(l1,l2)) key=input() if key in dict1:     dict1.pop(key) else:     print("key doesnot belongs to dict1")
