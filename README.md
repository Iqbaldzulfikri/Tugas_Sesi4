Operator Aritmatika

jumlahApel = 12
jumlahTeman = 4

apelPerTeman = jumlahApel / jumlahTeman
print("setiap orang akan menerima apel sebanyak:",apelPerTeman)

tambahanApel = 8
totalApel = jumlahApel + tambahanApel

print("total apel budi sekarang adalah sebanyak:",totalApel)
setiap orang akan menerima apel sebanyak: 3.0
total apel budi sekarang adalah sebanyak:
20


Operator Perbandingan

siti = 160 
andi = 165

print(siti, "=",andi,siti==andi)
print(siti, "!=",andi,siti!=andi)
print(siti, "<",andi,siti<andi)
print(siti, ">",andi,siti>andi)

print("jadi yang paling tinggi adalah andi sebesar",andi,"cm")
160 = 165 False
160 != 165 True
160 < 165 True
160 > 165 False
jadi yang paling tinggi adalah andi sebesar 165 cm


Operator Logika

cuacaCerah = True
prSelesai = True

bisaBermain = cuacaCerah and prSelesai
print("apakah budi bisa bermain di luar",bisaBermain)
apakah budi bisa bermain di luar True


Operator Bitwise
num1 = 6
num2 = 3

hasilAnd = num1 & num2
print("angka biner dari AND adalah:",bin(hasilAnd))


hasilOr = num1 | num2
print("angka biner dari OR adalah:",bin(hasilOr))

hasilXor = num1 ^ num2
print("angka biner dari XOR adalah:",bin(hasilXor))
angka biner dari AND adalah: 0b10
angka biner dari OR adalah: 0b111
angka biner dari XOR adalah: 0b101


Operator Penugasan
uangAwal = 50000
print("uangAwal",uangAwal)
uangAwal += 20000
print("setelah di tambah 20000 =",uangAwal)
uangAwal -= 30000
print("dia membeli paket internet sebesar 30000 =",uangAwal)
uangAwal 50000
setelah di tambah 20000 = 70000
dia membeli paket internet sebesar 30000 = 40000


Operator Keanggotaan
name = "eka"
daftarPesertaLomba = ["andi","budi","citra","dewi"]
hasil = name in daftarPesertaLomba
print("apakah terdaftar?",hasil)

kalimat = "saya suka belajar bahasa pyhton"
kataYangDiCari = "pyhton"
hasil = kataYangDiCari in kalimat
print("apakah kata",kataYangDiCari,"ada di kalimat",hasil)
apakah terdaftar? False
apakah kata pyhton ada di kalimat True


Operator Identitas
x = 20
y = 20

hasil = x is y
print("apakah x dan y mengacu pada objek yang sama?",hasil)

a = "sayang"
b = "sayang"

hasil = a is b
print("apakah a dan b mengacu pada objek yang sama?",hasil)

list1 = ["12","13","14"]
list2 = ["12","13","14"]

hasil = list1 is list2
print("apakah list1 dan list2 mengacu pada objek yang sama?",hasil)
apakah x dan y mengacu pada objek yang sama? True
apakah a dan b mengacu pada objek yang sama? True
apakah list1 dan list2 mengacu pada objek yang sama? False


Operator Ternary
angka = 150
hasil = ("Tidak lebih besar dari 100", "Lebih besar dari 100")[angka > 100]
print(hasil)

angka2 = 50
hasil2 = ("Tidak lebih besar dari 100", "Lebih besar dari 100")[angka2 > 100]
print(hasil2)

nilai_ujian = int(input("isi nilai"))
status = ("Tidak Lulus", "Lulus")[nilai_ujian > 70]
print(status)

nilai_ujian2 = int(input("isi nilai"))
status2 = ("Tidak Lulus", "Lulus")[nilai_ujian2 > 70]
print(status2)
Lebih besar dari 100
Tidak lebih besar dari 100
Lulus
Tidak Lulus

angka = 150
hasil = "Lebih besar dari 100" if angka > 100 else "Tidak lebih besar dari 100"
print(hasil)

angka2 = 50
hasil2 = "Lebih besar dari 100" if angka2 > 100 else "Tidak lebih besar dari 100"
print(hasil2)

nilai_ujian = int(input("isi nilai"))
status = "Lulus" if nilai_ujian > 70 else "Tidak Lulus"
print(status)

nilai_ujian2 = int(input("isi nilai"))
status2 = "Lulus" if nilai_ujian2 > 70 else "Tidak Lulus"
print(status2)
Lebih besar dari 100
Tidak lebih besar dari 100
Tidak Lulus
Tidak Lulus
