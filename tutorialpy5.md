# APLIKASI TERBILANG
numbers = input("Masukkan angka : ")

numbers_mapping = {
    "1": "satu",
    "2": "dua",
    "3": "tiga",
    "4": "empat",
    "5": "lima",
    "6": "enam",
    "7": "tujuh",
    "8": "delapan",
    "9": "sembilan",
}

output = ""

for n in numbers:
    terbilang = numbers_mapping.get(n, "Invalid")
    
    output = output + terbilang + " "
    
print(output)
![image](https://user-images.githubusercontent.com/115380709/196025410-f984751f-d936-4091-86bc-0466b61365be.png)

# EMOJI CONVERTER
message = input(">>> ")

emoji_mapping = {
    ":)":"😀"
    ":D":"😊"
    ":|":"😑" 
}

words = message.split(" ")

output = ""
for w in words:
    output = output + emoji_mapping.get(w, w) + " "
    
print(output)
![image](https://user-images.githubusercontent.com/115380709/196025458-6c48e1bd-6b09-4178-8539-64f0776aab35.png)

# FUNGSI
def halo_user():
    print("Halo user")
    print("Selamat belajar python")
    print("diluar fungsi")
    
print("Start")
halo_user()
print("finish") 
![image](https://user-images.githubusercontent.com/115380709/196025478-810085a3-769b-4574-9d24-a22acf3713ad.png)

# PARAMETER FUNGSI
def halo_user(name, level):
    print(f"Halo {name} - {level}")
    print("Selamat belajar python")
    
print("start")
halo_user("Maulana", 10)
print("===============")
halo_user("Zelda", 8)
print("Finish") 
![image](https://user-images.githubusercontent.com/115380709/196025500-270b61b8-4202-4e59-949e-8dda391f8544.png)

# KEYWORD ARGUMENT
def halo_user(name, level):
    print(f"Halo {name} - {level}")
    print("Selamat belajar python")
    
print("start")
halo_user("Maulana", 10)
print("finis")
![image](https://user-images.githubusercontent.com/115380709/196025527-7c572b9a-864c-4658-ac98-8dfac9807453.png)

# RETURN VALUE
def multiply(a, b):
    result = proses 
    result = result
    return result

# input
# proses
# output

result = multiply(2, 10)
print(result) #hasil yang diinginkan = 2 * 10 = 20
![image](https://user-images.githubusercontent.com/115380709/196025563-6767da98-9c4b-4345-b6a0-0e3d4528b4e7.png)
