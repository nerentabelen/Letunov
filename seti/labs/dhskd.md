
# 1. Создание всех директорий (включая вложенные)
mkdir -p kotohin/{Lab2,lab_24,Lab3/{A1,A2/{B1,B2/B3},Info/{Hobby,Personal,University}},Lab4,Lab4_kotokhin,Laba4_kotokhin}

# 2. Создание обычных текстовых файлов
touch kotohin/Lab3/A1/all.txt
touch kotohin/Lab3/A2/Lab_3.txt
touch kotohin/Lab3/all.txt
touch kotohin/Lab3/Info/Hobby/hobby.txt
touch kotohin/Lab3/Info/Personal/{DateB.txt,Name.txt,School.txt}
touch kotohin/Lab3/Info/University/{Mark.txt,Name.txt}

# 3. Создание файлов в lab_24 и выдача им прав на исполнение (чтобы цвет стал зеленым)
touch kotohin/lab_24/{file1.txt,file2.txt,file_combined.txt}
chmod +x kotohin/lab_24/{file1.txt,file2.txt,file_combined.tx
t}
