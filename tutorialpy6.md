# EXCEPTION
try:
    level = input("level kamu : ")
    level = int(level)
    level = level / 0
    print(level)
except ZeroDivisionError:
    print("Error tidak bisa dibagi 0")
![image](https://user-images.githubusercontent.com/115380709/196034008-53519bc2-bc2d-4a93-9e43-186a51c346e7.png)

# GENERAL EXCEPTION
try:
    level = input("Level kamu : ")
    level = int(level)
    level = level / 0
    print(level)
except:
    print("Terjadi kesalahan")
![image](https://user-images.githubusercontent.com/115380709/196034060-8c3f820c-c288-4013-bd65-91f6f1d01244.png)

# MEMBACA FILE
users = open("users.txt", "r")

array = users.readlines()

index = 1
for user in array:
    print(f"{index} - {user}")
    index += 1
    
users.close()
![image](https://user-images.githubusercontent.com/115380709/196034099-1a15d0f7-a5d2-4cfe-b527-a8b830820939.png)

# MENULIS FILE
users = open("users.txt", "a")

users.write("Link - link")

users.close() 
![image](https://user-images.githubusercontent.com/115380709/196034135-61126aad-3bc9-4b78-b486-045d1049e411.png)
