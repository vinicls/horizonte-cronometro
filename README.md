# Cronômetro — Horizonte Jiu Jitsu

Cronômetro oficial da academia **Horizonte Jiu Jitsu**, desenvolvido para uso em aula, competições e treinos. Roda diretamente no navegador, sem instalação, e pode ser fixado na tela inicial do smartphone e tablet como um aplicativo.

---

## Funcionalidades

- **Presets rápidos** por categoria (Infantil, Juvenil, Adulto, Master, Treino e outros)
- **Configuração manual** de tempo de luta, intervalo, número de rounds e aviso final
- **Aviso de início** — contagem regressiva de 5s antes do primeiro round (ativável/desativável)
- **Aviso de prontidão** — últimos 10s do intervalo com sinal sonoro e visual (ativável/desativável)
- **Indicadores visuais** de rounds e intervalos com bolinhas coloridas animadas
- **Barra de progresso** contínua durante o intervalo, com mudança de cor suave
- **Sons distintos** para início de round, fim de round e contagem regressiva
- **Modo escuro** adaptativo
- **Relógio e data** em tempo real
- **Logomarca** da academia com efeito de brilho periódico
- **Banner de instalação** automático para Android e iOS

---

## Como usar

### No navegador
Acesse diretamente pelo link:

```
https://seu-usuario.github.io/horizonte-cronometro
```

### Instalar como app no smartphone

**Android (Chrome):**
Um banner aparecerá automaticamente perguntando se deseja instalar. Toque em **Instalar**.

**iPhone / iPad (Safari):**
1. Abra o link no Safari
2. Toque no ícone de compartilhar ↑
3. Selecione **"Adicionar à Tela de Início"**
4. Toque em **Adicionar**

O app abre em tela cheia, sem barra do navegador, e funciona **offline** após o primeiro acesso.

---

## Arquivos do repositório

| Arquivo | Descrição |
|---|---|
| `index.html` | App completo — todo o código em um único arquivo |
| `logohbjj.png` | Logomarca da academia (referenciada pelo app) |
| `README.md` | Este arquivo |

---

## Uso em TV via Raspberry Pi

O app foi projetado para rodar em tela de **TV 32" (1920×1080px)** via Raspberry Pi com Chromium em modo quiosque. Nesse modo, a tela é dividida em duas colunas:

- **Coluna esquerda** — configurações, presets, relógio e logomarca
- **Coluna direita** — cronômetro em destaque

Ao iniciar o treino, a coluna de configurações some e o cronômetro ocupa toda a tela.

---

## Presets disponíveis

| Preset | Luta | Intervalo | Rounds |
|---|---|---|---|
| Teste | 1 min | 10s | 2 |
| Infantil | 2 min | 1:00 | 3 |
| Juvenil | 4 min | 1:00 | 3 |
| Treino | 5 min | 30s | 5 |
| Adulto | 5 min | 1:00 | 3 |
| Master | 5 min | 1:30 | 3 |

---

## Compatibilidade

| Dispositivo | Suporte |
|---|---|
| TV / Desktop (≥ 1200px) | ✅ Layout duas colunas |
| Tablet (600–1199px) | ✅ Layout coluna única |
| Smartphone (< 600px) | ✅ Layout compacto com configurações expansíveis |
| iOS Safari | ✅ Instalável via "Adicionar à Tela de Início" |
| Android Chrome | ✅ Instalável via banner automático |
| Chromium / Raspberry Pi | ✅ Modo quiosque TV |

---

## Versão

**v2.3** — Prof. Alexandre Wanderley · Horizonte Jiu Jitsu

---

Desenvolvido por **Vinícius de Carvalho Leão Simões** para HORIZONTE JIU JITSU.  
JOÃO PESSOA-PB, BRASIL. 14/04/2026.
