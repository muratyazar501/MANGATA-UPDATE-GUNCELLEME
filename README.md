# MANGATA-UPDATE-GUNCELLEME

![image](https://github.com/muratyazar501/MANGATA-UPDATE-GUNCELLEME/assets/136369047/0734ac15-4038-4a13-9f68-4888c29eb916)

### Linkler

https://github.com/Volkan081

https://github.com/muratyazar501

https://twitter.com/BerraVolkan




```
cd avs-operator-setup
```
```
docker compose down
```
👉NOT: .env dosyasını bilgisayara yedekle ve 08 nolu kodda yedeklediğiniğiz bilgilerinizi giriniz (bilgileri kullanacağız dosyayı değil dosya yolu : /root/avs-operator-setup/.env)
```
mv /root/avs-operator-setup/.env /root/.env
```
```
git reset --hard
```
```
git fetch
```

docker compose pull
```
Not: .env dosyasını bilgisayarda olan bilgileri girerek kaydet(env dosyası değişmiş)
```
chmod +x run.sh
```


08 nolu kod:bu kodda yedek aldığınız env dosyası bilgileriniz girilecek(wallet ismini yazmayı ve şirfrenizi girmeyi unutmayın)
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
