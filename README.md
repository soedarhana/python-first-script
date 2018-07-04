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


for i in range(0, 2):
    print(umur)


while umur > 0:
    print("Usia Saat Ini %s" % umur)
    print("Yeaaahhh Hidup")
    umur = umur - 1


nama_buah=["semangka", "jeruk", "anggur", "melon"]
print(nama_buah)
nama_buah.append("pisang")
nama_buah.append("ceri")
print(nama_buah)

for dn in  nama_buah:
    print("Nama buah %s, Ada juga %s wkwkwkw" % (dn, ngaran))

human = {}
human['nama'] = " Bowo"
human['jekel'] = "Laki laki"
human['status'] = "Bujangan"
print(human)
human['nama'] = "Bowo tik tok"
print(human)
human['alamat'] = "JakMania"
print(human)

import json
print(json.dumps(human))
