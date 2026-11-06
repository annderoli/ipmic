# 🎙️ IPMic

**Transforme um celular Android em uma câmera ou microfone IP para monitoramento remoto.**

O **IPMic** é um aplicativo Android, desenvolvido em **Kotlin**, para conexão remota de microfone — funcionando como as câmeras IP, mas com acesso ao microfone (e também à câmera). Com ele, um celular Android moderno pode ser transformado em uma **câmera ou microfone IP** para monitoramento à distância, ajudando na **segurança domiciliar** ou no acompanhamento de **familiares** (como crianças, idosos ou pessoas que precisam de cuidados).

> 💡 Aquele celular antigo parado na gaveta pode virar um dispositivo de monitoramento.

---

## 📌 Sobre o projeto

Câmeras IP são populares para segurança, mas nem sempre oferecem uma boa experiência de áudio — e exigem a compra de um equipamento dedicado. O IPMic propõe reaproveitar smartphones Android que já temos para:

- 🎧 **Ouvir o ambiente remotamente** em tempo real, como um microfone IP;
- 📹 **Transmitir vídeo** da câmera do celular, como uma câmera IP;
- 🏠 **Monitorar a casa** enquanto você está fora;
- 👨‍👩‍👧 **Acompanhar familiares** à distância (babá eletrônica, cuidado de idosos etc.).

## ✨ Funcionalidades (planejadas)

- [ ] Transmissão de áudio do microfone em tempo real
- [ ] Transmissão de vídeo da câmera em tempo real
- [ ] Modo **transmissor** (celular que fica no ambiente) e modo **receptor** (celular/navegador de quem monitora)
- [ ] Acesso pela rede local (Wi-Fi)
- [ ] Acesso remoto pela internet
- [ ] Autenticação com usuário/senha ou código de pareamento
- [ ] Execução em segundo plano com serviço em primeiro plano (Foreground Service) e notificação visível
- [ ] Detecção de som/ruído com alertas
- [ ] Compatibilidade com players e softwares que suportam RTSP/HTTP

## 🛠️ Tecnologias

- **Linguagem:** [Kotlin](https://kotlinlang.org/)
- **Plataforma:** Android
- **IDE:** Android Studio

## 📱 Requisitos

- Celular com Android moderno
- Permissões de **microfone** e **câmera**
- Conexão Wi-Fi (rede local) ou internet para acesso remoto

## 🚀 Como executar

```bash
# Clone o repositório
git clone https://github.com/annderoli/ipmic.git

# Abra a pasta do projeto no Android Studio
# e execute em um dispositivo ou emulador Android
```

## 🔐 Privacidade e uso responsável

O IPMic foi pensado para **segurança e cuidado**, não para vigilância às escondidas.

- Use o app apenas em ambientes e com pessoas que **saibam e concordem** com o monitoramento.
- Gravar ou escutar conversas de terceiros sem consentimento pode ser **ilegal** em muitos lugares, incluindo o Brasil.
- O Android exibe indicadores de uso de microfone e câmera, e o app deve manter uma **notificação visível** enquanto estiver transmitindo.

## 📄 Status

🚧 Projeto em desenvolvimento.

## 👤 Autor

Desenvolvido por **Anderson** — [@annderoli](https://github.com/annderoli)
