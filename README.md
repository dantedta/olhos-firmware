# olhos-firmware
Firmware dos olhos (2x GC9A01 + ESP32-S3). A placa lê o `versao.json` ao acertar a hora (boot e 4h) e,
se a versão for maior que a dela, baixa o .bin, confere tamanho e SHA-256 e se atualiza sozinha.
Versão atual: **2026112204** — setinha de atualizacao pendente, instala as 4h ou pelo menu, pagina de ajuda
