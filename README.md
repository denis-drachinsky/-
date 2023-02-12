
while True:
    s1 = input("Введите первый знак (+,-,*,/): ")
    s2 = input("Введите второй знак (+,-,*,/): ")
    if s1 and s2 in ('+', '-', '*', '/'):
            a = float(input("a="))
            b = float(input("b="))
            c = float(input("c="))
            if s1 == '+':
                if s2 == '+':
                    print("%.2f" % (a+b+c))
                elif s2 == '-':
                    print("%.2f" % (a+b-c))
                elif s2 == '*':
                    print("%.2f" % (a+b*c))
                elif s2 == '/':
                    if c != 0:
                        print("%.2f" % (a+b/c))
                    else:
                        print("Devision by zero")
            if s1 == '-':
                if s2 == '+':
                    print("%.2f" % (a-b+c))
                elif s2 == '-':
                    print("%.2f" % (a-b-c))
                elif s2 == '*':
                    print("%.2f" % (a-b*c))
                elif s2 == '/':
                    if c != 0:
                        print("%.2f" % (a-b/c))
                    else:
                        print("Devision by zero")
            if s1 == '*':
                if s2 == '+':
                    print("%.2f" % (a*b+c))
                elif s2 == '-':
                    print("%.2f" % (a*b-c))
                elif s2 == '*':
                    print("%.2f" % (a*b*c))
                elif s2 == '/':
                    if c != 0:
                        print("%.2f" % (a*b/c))
                    else:
                        print("Devision by zero")
            if s1 == '/':
                if s2 == '+':
                    print("%.2f" % (a/b+c))
                elif s2 == '-':
                    print("%.2f" % (a/b-c))
                elif s2 == '*':
                    print("%.2f" % (a/b*c))
                elif s2 == '/':
                    if c != 0:
                        print("%.2f" % (a/b/c))
                    else:
                        print("Devision by zero")
    else:
        print("Wrong operator")
