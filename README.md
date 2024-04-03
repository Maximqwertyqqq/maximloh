





marks = list()
t1 = 0
t2 = 0
t3 = 0
mark = int(input('Введи балл (0 - остановить ввод):'))
while mark != 0:
    if mark == 5:
        t1+=1
    if mark == 4:
        t2+=1
    if mark == 3:
        t3+=1
    marks.append(mark)
    mark = int(input('Введи балл (0 - остановить ввод):'))
t = (t1 + t2 + t3)/len(marks)*100
print('Список оценок:', marks)
print('Успеваемость:', t)
