215150309111002 Dimas Fariz N
nilai = int(input('masukkan nilai: '))

if nilai >= 80:
    grade = 'A'

elif nilai >= 79:
    grade = 'B+'

elif nilai >= 69:
    grade = 'B'

elif nilai >= 60:
    grade = 'C+'

elif nilai >= 55:
    grade = 'C'

elif nilai >= 50:
    grade = 'D+'

elif nilai >= 44:
    grade = 'D'

else:
    grade = 'E'

print ('Grade = %s' % grade)
