# python-first-script
Script dasar python


message = 'Hello Dilan'
ngaran = 'IIK SUDARHANA'
umur = 3
berat_badan = 50.5

print(message)
print(ngaran)
print(umur)
print(berat_badan)

# if else

if umur <= 17:
    print("Masih Bocah, Harus 18+")
else:
    print("GG, Dah tua ;v")

if berat_badan >= 50:
    print("Berat Badan Normal")
elif berat_badan <50:
    print("Kurang Berat Badan")
else:
    print("Makan woooyy !!! Jangan banyak gadang")

#

# looping, pembacaan = angka terakhir dikurangi angka awal 2-0 = 2, jadi pengulangan sebanyak 2x

for i in range(0, 2):
    print(umur)

# looping, perulangan lebih dari 0x sampe batas yang ditentukan. batas yang di tentukan adalah '% umur'
# jadi tergantung pengisian umurnya.

while umur > 0:
    print("Usia Saat Ini %s" % umur)
    print("Yeaaahhh Hidup")
    umur = umur - 1

# list atau array

nama_buah=["semangka", "jeruk", "anggur", "melon"]
print(nama_buah)
# penambahan array pake .append
nama_buah.append("pisang")
nama_buah.append("ceri")
print(nama_buah)

# dn = perulangan dengan penampilan ke bawah

for dn in  nama_buah:
    print("Nama buah %s, Ada juga %s wkwkwkw" % (dn, ngaran))

#contoh dictonary

human = {}
human['nama'] = " Bowo"
human['jekel'] = "Laki laki"
human['status'] = "Bujangan"
print(human)
human['nama'] = "Bowo tik tok"
print(human)
human['alamat'] = "JakMania"
print(human)

# json

import json
print(json.dumps(human))
