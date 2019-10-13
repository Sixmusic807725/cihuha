#coding=utf-8
import os, sys

def menu():
	print ("""
    ╔═════════════════╗
    ║         Sixmusic807725         ║
    ╚═════════════════╝
1.Trojans Win32
2.Penangkal Virus
3.membuat virtex
0.exit
""")

menu()
pilih = raw_input("[©]nomor : ")
if pilihan =="":
	print "pilihan tidak ada"
	exit()
if pilih =="1":
	os.system("clear")
	print ("menginstall....")
	os.system("apt update && apt upgrade")
	os.system("pkg install git toilet")
	os.system("pkg install python")
	os.system("pkg install python2")
	os.system("git clone https://github.com/banghyuu/ddosWD")
	os.system("sh ddosWD/Ddos.sh")

if pilih =="2":
	os.system("clear")
	print ("menginstall....")
	os.system("pkg install git python2")
	os.system("git clone https://github.com/JustAHackers/penangkal")
	os.system("bash setup")

if pilih =="3":
	os.system("clear")
	print ("menginstall....")
	os.system("apt update && apt upgrade")
	os.system("apt install git")
	os.system("apt install curl")
	os.system("apt install figlet")
	os.system("apt install ruby")
	os.system("gem install lolcat")
	os.system("git clone https://github.com/muhammadfathul/VIRTEX")
	os.system("sh VIRTEX/virtex.sh") 

if pilih =="0":
	print ("terimakasih telah menggunakan tools ini")
	exit()

























