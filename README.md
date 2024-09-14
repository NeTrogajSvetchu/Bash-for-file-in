# Bash для красивого вывода количества строк в файлах

find . -name "*.txt"

grep -Hc ".*" *.txt

for file in ./*.txt ./1t/*.txt ./2t/*.txt; do echo "$file - $(wc -l < "$file") lines"; done
