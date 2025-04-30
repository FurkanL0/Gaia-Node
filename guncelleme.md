# Gaia Node Güncelleme ; 

![1500x500](https://github.com/user-attachments/assets/0eca5de0-8355-4e8d-b2cc-9feb377e0af0)

## Yedek Alma ; 

![image](https://github.com/user-attachments/assets/759130a1-740a-4328-a723-4a222c1b5230)

#### Güncellemeden önce nolur nolmaz yedek alınması gereken bilgiler ; 

- nodeid.json

- deviceid.txt

- Keystore file ( Örnek ;  0278996e-5dad-4xy9-b3xu7-be3xuxxxaac94)

- Dilerseniz SFTP ile ( Termius ) - dilersenizde Mobaxterm üzerinden bu dosyaların yedeklerini pc'nize indirin.

## Güncelleme ; 

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash -s -- --upgrade
```

#### Durdurup Geri Başlatmaca ; 

```bash
gaianet stop
```

```bash
gaianet start
```
