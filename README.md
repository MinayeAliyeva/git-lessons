GIT /GITHUB /GITLUCK
Git- vcs (version control system) , yani bizim calisma alanimizda(working directory) etdiyimiz deyisiklikleri ekleme (git add) , ardindan git commit ile (staging area) gonderirik.
3 areas var => 1 Working directory(iş direktoriyasi) ".git uzantisi olan folderdi"- Biz gore Bilirik bu areani , 2 Staging Area .git folderinin daxilinde olur, 3 Repository .git Folderinde olur bu bizim local repositoridi

git init etdikde her fayil elave olunur Working directory-e , git add etdikde Staging Area , git commit etdikde Local Repository e
Bunlarin hamisini bize git saglayir (versiyalar arasi kecidi) etdiyimiz deyisiklikleri akdarmamiza yardimci olan bir aracdir.
Github,Gitluck,Gitlub- Tamamen depo kimi baxa bilerik.Bunlar uzaqdaki serverimiz online olarak calisir. ancaq kendi calisma alanimiz offline.
Comutlar
clear -ekrani temizler
pwd-hangi dosya yolundaysanz onu gosderir.
cd .. - oldugumuz kloserden bir ust klosere kecidi saglar.
cd klosor adi - bu klosere kecid yapar.
mkdir - make direction (bir dosya ylu olusdur).
touch index.html-file olusturur.
ls-oldugumuz yerdeki dosyalari (folderleri) gosterir.
git init-bizim icinde bulundugumuz klasorde .git isimli gizli klasor olusturur bu klasor yardimiyla biz orda comitler yapa biliyoruz pullar,pushlar farkliliklari gore biliyoruz . Projenin baslangicinde basta 1 defa git initi yazmis oluyoruz ve gitle ilgili butun ozellikleri kullana biliyoruz.
ls -a - bulundugun klasorde butun dosyalari gizli olan ya olmayan hepsini gosderir.

git status-staging areaya gondermediyiniz deyisiklikleri gosderir. (git add etmezden evvelki degisiklikler)
...