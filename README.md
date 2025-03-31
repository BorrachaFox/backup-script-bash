# Backup Script in Bash

Este repositório contém um script em Bash para realizar backups de arquivos modificados nas últimas 24 horas dentro de um diretório específico.

## 📌 Funcionalidades
- Verifica se os diretórios de origem e destino são válidos.
- Filtra arquivos modificados nas últimas 24 horas.
- Compacta os arquivos selecionados em um `.tar.gz`.
- Move o arquivo compactado para o diretório de destino.

## 📂 Estrutura
- `backup.sh`: Script principal responsável pela execução do backup.

## 🚀 Como Usar
### 1️⃣ Tornando o script executável
```bash
chmod +x backup.sh
```
### 2️⃣ Executando o script
```bash
./backup.sh <diretório_origem> <diretório_destino>
```
Exemplo:
```bash
./backup.sh /home/user/documents /home/user/backups
```

## ⚠️ Requisitos
- Sistema operacional baseado em Unix/Linux
- Bash Shell instalado

## 📜 Licença
Este projeto é de código aberto e está disponível sob a licença MIT.
