# PERCABANGAN IF
is_day = False
is_night = False

if is_day:
    print("selamat siang")
elif is_night:
    print("selamat malam")
else: 
    print("selamat suka-suka")
    
print("selamat menikmati harimu")
![image](https://user-images.githubusercontent.com/115380709/196018766-8ab228dc-4ad3-4987-b2a6-e10d3f0d441f.png)

# OPERATOR PERBANDINGAN
grade = 5

if grade >= 8:
    print("Nilai kamu A")
elif grade >= 7:
    print("Nilai kamu B")
elif grade >= 6:
    print("Nilai kamu C")
else:
    print("silahkan belajar lagi dengan baik")
![image](https://user-images.githubusercontent.com/115380709/196018799-b1d81498-b5f1-4c54-8c25-a0e0e45fc5a2.png)

# OPERATOR LOGIKA
name = "Maulana Helmi Akbar"
by_pass_validation = False

if len(name) > 3 and by_pass_validation :
    print("welcome")
else:
    print("nama terlalu pendek")
![image](https://user-images.githubusercontent.com/115380709/196018829-857075f8-3f35-4756-b7fe-410dc5af03b5.png)

# PERULANGAN WHILE
index = 1

while index <= 5:
    print("*" * index)
    index += 1
    
    print("finish")
![image](https://user-images.githubusercontent.com/115380709/196018867-5f8b9c17-7089-4dfd-930b-a816f990fb07.png)

# GAME TEBAK ANGKA
trying = 0 
secret_number = 7
limit = 3

while trying < limit:
    guess_number = input("Masukkan angka (1-9) : ")
    guess_number = int(guess_number)
    
    if guess_number == secret_number:
        print("Selamat, Anda Menang")
        break
    
    trying += 1
![image](https://user-images.githubusercontent.com/115380709/196018887-3475f22e-14f0-4c59-a71f-7a99d146c50a.png)

# APLIKASI KALKULATOR
# (+ - / exit)
command = ""

while command != "exit":
    command = input("perintah : ")
    
    if command == "exit":
        break
    
    if command != "+" and command != "*" and Command != "/":
        print("printah tidak dikenali")
        continue
    
    a = int(input("Angka pertama : "))
    b = int(input("Angka kedua : "))
    
    if command == "+":
        result = a + b
    elif command == "-":
        result = a - b
    elif command == "*":
        result = a * b
    elif command == "/":
        result = a / b
        
    print(f"Hasil : {result}")
    
print("Terimakasih sudah menggunakan aplikasi ini")
![image](https://user-images.githubusercontent.com/115380709/196019114-10c21920-ede7-47ed-8245-856a48cad5f9.png)
![image](https://user-images.githubusercontent.com/115380709/196018975-026870b9-e60e-49c3-9c34-61a1f188d3d6.png)
