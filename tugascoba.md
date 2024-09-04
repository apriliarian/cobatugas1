# coba
## coba coba tugas nomor 3
git add merupakan perintah ini digunakan untuk menambahkan perubahan (file yang diubah, ditambah,ataupun di hapus) pada VS  Code agar terhung dengan file yang ada di GitHub.


git config digunakan untuk mengatur identitas pengguna . Saat melakukan commit, Git perlu mengetahui siapa yang membuat perubahan. Identitas ini akan dicatat di setiap commit. ketika melakukan git config kita harus menambahkan email yang kita pakai pada GitHub.
git config --global user.email "nama@mail.ugm.ac.id"
--global: Mengatur untuk semua repositori di komputer yang sama.
![Screenshot 2024-09-04 093044](https://github.com/user-attachments/assets/f58576f3-ff5a-49e9-aae4-6343d9744991)

git commit menyimpan setiap perubahan yang dilakukan disimpan secara permanen ke dalam repositori lokal.
"-m" digunakan untuk menambahkan pesan singkat yang menjelaskan apa yang telah diubah.
misalnya :
    git commit -m "penambahan tugas"
![Screenshot 2024-09-04 093050](https://github.com/user-attachments/assets/c3fd37b8-1689-4d01-ba5b-f0469cf25fa3)

git fetch untuk mengambil pembaruan terbaru dari repositori GitHub tanpa menggabungkannya secara langsung dengan repositori lokal. Ini berarti bahwa git fetch hanya mengambil informasi tentang perubahan yang ada di repositori GitHub tanpa mengubah cabang yang sedang dikerjakan di respositori lokal.
![Screenshot 2024-09-04 095443](https://github.com/user-attachments/assets/2e11b967-03cc-4f00-93fe-ca7ad46055bb)

git pull digunakan untuk mengambil (pull) perubahan terbaru dari repositori GitHub dan langsung menggabungkannya dengan repositori VS Code.
![Screenshot 2024-09-04 094740](https://github.com/user-attachments/assets/d66644c0-5f60-42c7-b2e8-a000cf1b5c77)

Apabila melakukan perubahan di GitHub dan VSCode setelah "git commi-m " " maka harus menggunakan git pull atau git fetch agar perubahan yang dilakukan keduanya sinkron. 

![Screenshot 2024-09-04 094752](https://github.com/user-attachments/assets/e7f9367a-fd7d-415b-9c2e-7e8377e57a0f)


git push digunakan untuk mengirim perubahan dari repositori lokal GitHub. Setelah melakukan commit di repositori lokal (VS Code), git push akan mengunggah commit-commit tersebut ke server GitHub agar perubahan yang dilakukan tersimpan di repositori online dan bisa diakses oleh orang lain atau kolaborator.
![Screenshot 2024-09-04 093059](https://github.com/user-attachments/assets/91dd742c-12ae-4b05-8137-afbf42ad6ff9)









