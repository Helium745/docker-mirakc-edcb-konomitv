# docker-mirakc-edcb-konomitv

[オリジナル版りどみ](Readme-orig.md)

Mirakc + EDCB(Linux) + KonomiTV on Docker

少々気が早いような気もしますが、EDCBと連携できる未来を想定して作っておきます。

## 導入
```
git clone --recursive https://github.com/Helium745/docker-mirakc-edcb-konomitv.git
pushd ./docker-mirakc-edcb-konomitv
pushd ./konomitv
cp docker-compose.example.yaml docker-compose.yaml
cp config.example.yaml config.yaml
popd
```

`./konomitv/config.yaml`と`./konomitv/docker-compose.yaml`に目を通してください。

あとは[Setup.md](Setup.md)を読んでください。