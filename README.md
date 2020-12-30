# scriptos
OS script
Я написав bash-script для 1 варіанту:
#!/bin/bash
for file in ./*.txt
do
cp $file ./$1
done
