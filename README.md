# 🐮🌟 Vaca Estelar

![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?logo=openjdk&logoColor=white) ![Java2D](https://img.shields.io/badge/Java2D-Animação-8B5CF6)

Projeto gráfico em **Java e Java2D** que representa uma vaca formada por estrelas, com animação, câmera ajustável e efeito de profundidade. Inclui uma **adaptação interativa para navegadores** com Canvas e JavaScript, preservando a aplicação Java original.

## 🌌 Demonstração 3D no navegador

**[▶ Explorar a Vaca Estelar em 3D](https://luanmarcioalvarenga-devcp.github.io/vaca-estelar/)**

> A demonstração ficará acessível nesse endereço depois que o GitHub Pages for ativado nas configurações do repositório. Enquanto isso, o código está em [`index.html`](./index.html).

A versão web permite arrastar para girar, aplicar zoom, ajustar o ritmo, pausar e mostrar/ocultar linhas de constelação.

## 🎮 Controles
| Controle | Ação |
|---|---|
| Arrastar mouse | Girar câmera |
| Roda do mouse | Zoom |
| Espaço | Pausar/continuar |
| Setas ↑ e ↓ | Ajustar velocidade |
| L | Alternar linhas de constelação |
| R | Restaurar visualização |
| Esc | Fechar |

## ▶️ Executar
Requer **JDK 17 ou superior** e ambiente gráfico. No Windows, execute `executar.bat`.

## 🧩 Organização do código
- `Main.java`: inicialização da janela
- `CowModel.java` e `Star.java`: geometria e modelo
- `Dance.java`: movimentos
- `UniversePanel.java`: desenho, câmera e interações

## 🧠 Conceitos praticados
Orientação a objetos, modelagem geométrica, animação, perspectiva e tratamento de eventos.

**Código-fonte Java e demonstração web publicados.**

[← Voltar ao portfólio](https://github.com/luanmarcioalvarenga-DevCp)
