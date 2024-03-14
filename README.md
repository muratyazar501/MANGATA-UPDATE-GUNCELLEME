# MANGATA-UPDATE-GUNCELLEME


```
cd avs-operator-setup
```
```
docker compose down
```
👉NOT: .env dosyasını bilgisayara yedekle (bilgileri kullanacağız dosyayı değil dosya yolu : /root/avs-operator-setup/.env)
```
mv /root/avs-operator-setup/.env /root/.env
```
```
git reset --hard
```
```
git fetch
```
```
git checkout tags/v0.2 -b v0.2
```
```
docker compose pull
```
Not: .env dosyasını bilgisayarda olan bilgileri girerek kaydet(env dosyası değişmiş)
```
chmod +x run.sh
```
```
nano .env
```
```
./run.sh opt-in
```
👉Not: eğer hata alırsanız  sebebi minimum 1 eth stake etmediğinizden zaten yazıorda

![image](https://github.com/Core-Node-Team/Testnet-TR/assets/91562185/c1367294-dbda-4eae-938c-eeb0182b0514)

```
docker compose up -d
```
```
docker logs -f --tail 100 avs-finalizer-node
```
