# PERULANGAN FOR
for item in range(1, 12, 2):
    print(item)
    ![image](https://user-images.githubusercontent.com/115380709/196021964-20971299-2d77-4a4f-aa7a-0702d0da3917.png)

# LIST
names = ["Maulana", "Helmi", "akbar", "reynaldo", "romero"]

for name in names:
    print(f"Nama : {name}")
![image](https://user-images.githubusercontent.com/115380709/196021993-c912b628-d749-46c1-adb6-31176dc2485e.png)

# LIST METHOD
numbers = [5, 6, 7, 8, 1]
print(numbers)

numbers.append(99)
print(numbers)

numbers.insert(2, 100)
print(numbers)

numbers.pop(5)
print(numbers)

numbers.remove(8)
print(numbers)

numbers.sort()
print(numbers)
![image](https://user-images.githubusercontent.com/115380709/196022029-104bd10b-f978-47e4-b331-b55bb6ae764b.png)

# MENJUMLAHKAN LIST
numbers = [5, 6, 7, 8, 1]

init_number = 0

for number in numbers:
    init_number = init_number + number
    
    print(init_number)
![image](https://user-images.githubusercontent.com/115380709/196022059-4d4ec61a-f255-44ee-9fa3-1021573c22d1.png)

# MENCARI ANGKA MAX
numbers = [5, 6, 7, 8, 1]

max_number = numbers[0]

for number in numbers:
    if number > max_number:
        max_number = number
        
print(max_number)
![image](https://user-images.githubusercontent.com/115380709/196022084-b15b06d6-482b-4aaa-9596-69a4623a326c.png)

# TUPLE
numbers = (5, 3, 1, 2, 4)
print(numbers[2])
![image](https://user-images.githubusercontent.com/115380709/196022110-7eff6e67-0f22-400b-81e6-cc8060ffb15c.png)

# UNPACK
numbers = (1, 2, 3)

# x = numbers [0]
# x = numbers [1]
# x = numbers [2]

x, *a = numbers

print("")
print(x)
print(a)
![image](https://user-images.githubusercontent.com/115380709/196022129-ba256afd-e7d8-4a20-afc9-db6ce975f199.png)

# DICTIONARY
user = {
    "name": "Maulana Helmi Akbar",
    "age": 22,
    "is_admin": True
}

user["username"] = "Maulana_helmi"
user["name"] = "el akbar."

temp = user.get("name")

print("")
print(temp)
![image](https://user-images.githubusercontent.com/115380709/196022164-854d65c7-7e66-40ba-b0a5-ded315fd88b0.png)



