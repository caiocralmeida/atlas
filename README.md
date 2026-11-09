# 🌍 Atlas · O Despertar das Civilizações

> Um jogo de estratégia 4X, sobrevivência e gestão de impérios baseado em turnos/tempo real, totalmente funcional e construído em JavaScript nativo, HTML5 Canvas e Web Audio API.

---

## 📌 Visão Geral

**Atlas** é uma experiência imersiva de evolução histórica dividida em três grandes eras civilizatórias — desde a precariedade de uma pequena tribo nômade até a exploração espacial. O jogador assume o controle de um líder e sua civilização, gerando mapas dinâmicos procedurais, coletando recursos, construindo infraestruturas, pesquisando tecnologias, gerenciando cidades e expandindo seu império perante outras nações controladas por IA.

---

## 🛠️ Tecnologias Utilizadas

* **JavaScript (ES6+)**: Lógica principal, inteligência artificial, física de mapas, gerador procedural baseado em ruído perlin/value noise e sistema de salvamento local (`localStorage`).
* **HTML5 Canvas**: Renderização gráfica otimizada do mundo, biomas, unidades e animações do jogo.
* **Web Audio API**: Motor de som sintetizado proceduralmente (sem dependência de arquivos de áudio externos), gerando efeitos sonoros, paisagens sonoras e trilha de piano/música ambiente dinâmicas em tempo real.
* **CSS3**: Layouts responsivos com suporte a escalas de interface e temas visuais inspirados em mapas cartográficos antigos.

---

## 🏛️ As Três Etapas da Campanha

1. **Sobrevivência**: Uma área selvagem isolada onde o foco é colher madeira, pedra e comida, sustentar a população inicial contra criaturas hostis e evoluir construções até erguer a *Prefeitura Central*.
2. **Império Planetário**: Exploração e colonização do planeta inteiro, contendo nações rivais, sistemas de expansão diplomática, comércio, guerras e pesquisas avançadas.
3. **Espaço**: Conquista interplanetária e estelar, gerenciando sistemas galácticos e povos alienígenas para consolidar a vitória cósmica definitiva.

---

## 🚀 Como Executar

Por ser uma aplicação web baseada em arquivos estáticos (HTML/JS), não é necessário instalar dependências complexas ou ambientes de compilação.

1. Baixe ou clone o repositório em sua máquina.
2. Certifique-se de que os arquivos principais (`index.html` e os submódulos de estágio) estão na mesma pasta.
3. Abra o arquivo `index.html` diretamente em qualquer navegador web moderno (Google Chrome, Firefox, Edge, Safari).

---

## 🎮 Controles e Atalhos

* **Botão Esquerdo do Mouse**: Atacar, coletar recursos, interagir com entidades, abrir construções ou selecionar unidades.
* **Botão Direito do Mouse**: Mover a unidade selecionada.
* **Arrastar o Mouse / Setas do Teclado**: Movimentar a câmera pelo mapa.
* **Roda do Mouse (Scroll)**: Ajustar o zoom.
* **Teclas de Atalho**:
  * `<C>`: Menu de criação/fabricação de itens.
  * `<B>`: Menu de construções.
  * `<I>`: Inventário e status pessoal.
  * `<G>`: Gestão de cidades.
  * `<T>`: Estatísticas gerais e de império.
  * `<Espaço>`: Pausar / Continuar jogo.
  * `<Tab>`: Ocultar/mostrar painéis inferiores.
  * `<Esc>`: Menu de pausa ou fechar painéis abertos.

---

## ⚙️ Funcionalidades Principais

* **Geração Procedural de Mapas**: Sementes personalizáveis para criar mundos únicos a cada nova partida, com diferentes biomas (florestas, desertos, montanhas, pântanos, neves e rios).
* **Gestão Econômica Completa**: Cadeias produtivas estruturadas com redes de estradas, manutenções, consumo de alimentos, felicidade da população e energia elétrica nas eras industriais.
* **Árvore Tecnológica e Cultural**: Pesquisa de inovações científicas, doutrinas culturais e caminhos de fé que modificam os bônus do império.
* **Diplomacia Inteligente**: Pactos de não-agressão, acordos comerciais, alianças e declarações de guerra com IAs reativas.
* **Sistema de Salvamento Automático e Manual**: Proteção contra perda de progresso gravada diretamente no armazenamento do navegador (`localStorage`).
