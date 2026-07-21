
This repo consist of the practice code from my CRT training
def login_required(func):
    def wrapper():
        print("checking the user login")
        func()
    return wrapper
@login_required  
def dashboard():
    print("welcome to dashboard")
dashboard()   

