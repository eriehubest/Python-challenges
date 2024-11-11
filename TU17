a = input("please input your data for check digit: ")
        list = []
        k = 0

        def pos(num):
            newnum = len(list) - list.index(num)
            return newnum

        for i in a:
            list.append(int(i))
        for i in list:
            if pos(i) != 1:
                k += i*pos(i)
            else:
                f = i
        
        if f == 11-k%11:
            print("modulos 11 check tells correct")
        else:
            print("error detected")
