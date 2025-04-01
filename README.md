sudo -i

cat etc/resolv.conf

В etc/apt/sources.list закомментировать cd-rom, остальное раскомментировать

nslookup (для этого установить dns-utils)

sudo apt update

apt install whiptail

apt remove libsas/2-modules

etc/sources.list закомментировать

tar -xvf

cd mpro_app


rm pt_BAD


На сайте MP найти инструкцию для SIEM 26 (автоустановка для низконагруженных)

Поменять блок с MC в deploy_manifests/siem-aio.yml


sudo ./install-aio.sh --accept-eula
