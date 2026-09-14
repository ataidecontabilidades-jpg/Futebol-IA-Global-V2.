# Futebol IA Global — Android V2

Projeto Android Studio da versão 2.0.

## O que há aqui
- Nome: Futebol IA Global
- Ícone do aplicativo
- Tela web integrada no APK
- JavaScript habilitado
- Acesso à internet para consumir o backend
- Frontend V2 com status de dados reais/demonstração

## Backend
O APK não contém o token da Sportmonks. Rode o backend em um computador/servidor e configure a URL da API.

No emulador Android, `http://10.0.2.2:8000/api` aponta para o computador host.

No celular físico, troque para o IP do computador, por exemplo `http://192.168.0.10:8000/api`. Para produção, use HTTPS.

## Gerar APK
Abra esta pasta no Android Studio e use:
Build > Generate App Bundles or APKs > Generate APKs.

O arquivo será gerado em `app/build/outputs/apk/debug/`.
