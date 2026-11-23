# olhos-firmware
Firmware dos olhos (2x GC9A01 + ESP32-S3). A placa lê o `versao.json` ao acertar a hora (boot e 4h) e,
se a versão for maior que a dela, baixa o .bin, confere tamanho e SHA-256 e se atualiza sozinha.
Versão atual: **2026112307** — baixa com a tela apagada sem reiniciar; instala no proximo reinicio ou as 4h
