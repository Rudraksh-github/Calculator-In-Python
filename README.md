from tkinker import *

root = Tk()
root.geometry("644x900")
root.title("Calculater by Rudraksh-githb")
root.wm iconbitmap("1.ico")

scvalue = StringVar()
scvalue.set("")
screen = Entry(root, textvar=scvalue, font="lucida 40 bold"
screen.pack(fill =X, ipadx=8, pady=10, padx-10

f = Frame (root, bg="grey)
b = Buttion(f, text="9" , padx=28, pady=22,
b.pack()
f.pack()

root.mainloop()
