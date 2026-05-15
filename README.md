# labolatorium 11

# Polcenia
w folderze utworzyłem kolejne katalogi  mkdir logs_web1, logs_web2, logs_web3
<img width="634" height="165" alt="image" src="https://github.com/user-attachments/assets/b47a0133-2227-4e10-a82a-55e9a05f65b7" />

utworzyłem sieć mostkową poleceniem: docker network create --driver bridge lab11net
<img width="591" height="39" alt="image" src="https://github.com/user-attachments/assets/ca1b3975-efcb-4906-8273-b1d6463932de" />

uruchomiłem konterner web1, web2 oraz web3
<img width="1356" height="129" alt="image" src="https://github.com/user-attachments/assets/9298a34d-37b9-47f6-978b-a1fcf8185625" />
# Sprawdzam czy stony działają
link do strony http://localhost:8081/
<img width="891" height="220" alt="image" src="https://github.com/user-attachments/assets/3299d7c5-492e-4519-9677-6284ab94b859" />

link do strony http://localhost:8082/
<img width="883" height="233" alt="image" src="https://github.com/user-attachments/assets/9f3caac7-f027-4a4e-879c-beffd690dcd6" />

link do strony http://localhost:8083/
<img width="933" height="234" alt="image" src="https://github.com/user-attachments/assets/dca2a69a-b59a-40d0-a5c1-54622862a9c8" />

# Sprawdzenie
sprawdzamy jakie pliki są w folderze logs_web1 ls $PWD\logs_web1  a potem sprawdzamy zawartość cat $PWD\logs_web1\access.log
<img width="1365" height="266" alt="image" src="https://github.com/user-attachments/assets/a80e6c71-2914-4bcb-910b-7e88e1f6034f" />
sprawdzamy tez dla folderu log_web2
<img width="1354" height="280" alt="image" src="https://github.com/user-attachments/assets/9238513a-3cd5-4046-a65a-00a677078125" />
sprawdzamy tez dla folderu log_web3
<img width="1344" height="290" alt="image" src="https://github.com/user-attachments/assets/12b8d4e3-153f-4720-bed3-85e2804e344a" />
