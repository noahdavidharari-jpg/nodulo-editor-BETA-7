<div align="center">

# 🟠 NÓDULO

### Editor de vídeo profissional que roda no navegador — instalável como app, funciona offline.

Feito para celular (Android), num único projeto web. Sem instalar nada da loja, sem login, sem nuvem: seus vídeos ficam no seu aparelho.

</div>

---

## 📲 Como instalar (como app no celular)

O NÓDULO é um **PWA** (Progressive Web App). Isso quer dizer que ele se instala direto pelo navegador, vira um ícone na tela inicial e abre em tela cheia, igual a um app normal.

### No Android (Chrome)

1. Abra o link do app no **Chrome**:
   👉 **https://noahdavidharari-jpg.github.io/Nodulo/**
2. Espere carregar por completo na primeira vez.
3. Toque no menu **⋮** (canto superior direito) → **"Instalar app"** (ou *"Adicionar à tela inicial"*).
   - Em muitos aparelhos aparece sozinho um aviso **"Instalar NÓDULO"**.
4. Pronto! O ícone aparece na tela inicial. A partir daí ele **abre em tela cheia e funciona offline**.

### No iPhone (Safari)

1. Abra o link no **Safari**.
2. Toque no botão **Compartilhar** (quadrado com seta).
3. Escolha **"Adicionar à Tela de Início"**.

> 💡 Depois de instalado, dá pra usar **sem internet**. A conexão só é necessária na primeira vez (e para o *Export preciso*, que baixa um componente leve uma única vez).

---

## ✨ O que o app faz

Um editor de vídeo completo, com timeline de várias trilhas, pensado para o celular.

### Edição
- **Timeline multitrilha** com arrastar, cortar, dividir e duplicar clipes.
- **Transformar** com gestos (mover, escalar, girar) e guias de alinhamento.
- **Velocidade** com rampa, câmera lenta e reverso.
- **Keyframes** em quase tudo, com curvas de suavização.

### Visual
- **Ajustes de luz e cor**: brilho, contraste, exposição, temperatura, saturação, matiz, e mais — todos animáveis.
- **+45 filtros de cor (LUTs)** de um toque e **curvas de cor RGB** (color grading) com dezenas de presets.
- **+140 distorções** (redemoinho, torção, ondas, glitch, etc.), com **direção e animação** controláveis e keyframáveis.
- **+110 efeitos FX/overlay** em categorias (Luz, Máscara, Partículas, Atmosfera, Retrô), com intensidade, opacidade, velocidade e direção.
- **Chroma key** (fundo verde), **máscaras** (vários formatos), **pilha de efeitos** e **3D fake**.
- **40 formas** geométricas, **texto animado** e **legendas automáticas**.
- **Espelhamento e reflexo** de qualquer elemento (formas, emojis, texto, mídia).

### Áudio
- Trilhas de áudio, forma de onda, detecção de batida e ganho por clipe.

### Exportar
- **Renderizar agora** — rápido, funciona offline.
- **🎯 Export preciso (HD, MP4)** — monta o vídeo quadro a quadro com **duração exata** usando o acelerador de vídeo do celular (WebCodecs).

### Pessoal
- **Perfis locais** (vários editores no mesmo aparelho) e **modelos prontos** para começar rápido.
- **Tema claro e escuro**.

---

## 🔒 Privacidade

O NÓDULO **não coleta nada**. Não há login, servidor ou nuvem. Todos os seus projetos, mídias e configurações ficam **salvos apenas no seu navegador/aparelho** (armazenamento local). Se você limpar os dados do navegador, eles são apagados.

---

## 🛠️ Como funciona por dentro

- É um **app web** que roda inteiramente no navegador, sem servidor.
- Usa as APIs nativas do navegador para imagem, áudio e vídeo (Canvas, Web Audio, WebCodecs).
- O **service worker** (`sw.js`) guarda o app para funcionar **offline** e busca sempre a versão mais recente quando há internet.
- O `manifest.webmanifest` define o nome, os ícones e o modo tela cheia do app instalado.

### Arquivos do projeto
```
index.html            → o editor inteiro
manifest.webmanifest  → nome, ícones e cor do app
sw.js                 → modo offline (service worker)
icon-192.png          → ícone do app
icon-512.png          → ícone do app (alta resolução)
```

---

## 🔄 Atualizações

O app se atualiza sozinho: quando uma versão nova é publicada, ela chega automaticamente na próxima vez que você abrir com internet. Não precisa reinstalar.

---

## 🌐 Compatibilidade

- **Melhor experiência:** Chrome no Android (ou o PWA instalado).
- Funciona em navegadores modernos. O *Export preciso* precisa de um navegador com **WebCodecs** (o Chrome do Android tem); se faltar, o app avisa e você usa o **Renderizar agora**, que funciona em qualquer lugar.

---

<div align="center">

Feito com dedicação por **Noah**. 🧡

</div>
