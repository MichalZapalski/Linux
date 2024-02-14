# Repository for linux related commands

source .bashrc / używa odpowiedniego basha

Sudo su - root / odpala użytkownika root

ls - pokazuje wszystko w danym folderze(czasami trzeba ponownie wejsc do lokalizacji)

ls -al / pokazuje więcej informacji niż standardowe ls

rm -rf = usuwa dany plik/folder/lokalizację

tree - wyświetla foldery oraz podfoldery w formie drzewka

Cat - /pozwala odczytać np. plik textowy

Less - n 

mkdir sampdir - tworzy directory

man socket(manual) - coś jak opcja help w powershellu

rsync - kopiuje z jednej maszyny na drugą / Rsync sourcefile destinationfile

ssh-copy-id -i ~/.ssh/id_rsa.pub nazwa_usera@IP_docelowej_maszyny / kopiowanie po ssh, najpierw generujemy klucz przy pomocy komendy ssh-keygen

pidof ping / daje process ID dla konkretnego polecenia

getfacl pliktest / daje informacje nt dostępów dla konkretnego pliku

setfacl -m u:kurs:rwx pliktest / nadaje odpowiednie uprawnienia do pliku(r-read ; w-write; x-execute)

find ./kurs -name pyton.txt / szuka pliku o podanej nazwie

sed -e 's/ala/basia/' elementarz.txt / zamienia wyrażenie ala na basia w pliku elementarz.txt

ps aux / wyświetla wszystkie procesy
