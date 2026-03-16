# 🌐 Miniguia de Estudos: Explorando Three.js com NotebookLM

Este repositório foi desenvolvido como parte de um desafio de projeto na **DIO**, focado em utilizar a Inteligência Artificial (NotebookLM) para criar um fluxo de aprendizagem ativa sobre **Three.js**.

---

## 🎯 Contexto e Objetivos
O objetivo deste caderno temático é desmistificar o desenvolvimento de gráficos 3D na web. 
* **Tema:** Fundamentos de Three.js.
* **Foco:** Entender o ciclo de vida de uma cena (Scene Graph), tipos de câmeras, materiais e iluminação.
* **Objetivo:** Criar um roteiro de estudos sólido para transitar do JavaScript puro para a renderização 3D.

---

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM, selecionei as seguintes fontes oficiais e técnicas:
1. **Three.js Manual:** Documentação oficial (seção "Creating a Scene").
2. **Discover Three.js:** Guia conceitual sobre sistemas de coordenadas e iluminação.
3. **Three.js Examples:** Snippets de código reais para análise de sintaxe.

---

## 🧠 Engenharia de Prompts

Nesta seção, documento a evolução do raciocínio aplicado para extrair o melhor da IA, utilizando técnicas de *Prompt Engineering*.

### Comparação de Resultados
| 1- Técnica Aplicada | 2- Prompt Utilizado | 3- Resultado Obtido |
|1-**sem nenhuma técnica aplicada**|
|2- **Prompt Inicial** | "Por onde eu devo começar meus estudos no Three.js? Qual as melhores ferramentas?" | Resposta genérica e sem estrutura definida. |
| 3- **Reesultado Obtido** | Logotipo do NotebookLM
Threes.js
Fontes
Conversa
Estúdio
🧊
Threes.js
14 fontes
Os recursos apresentados focam no three.js, uma biblioteca de JavaScript amplamente utilizada para desenvolver gráficos 3D e experiências de realidade virtual ou aumentada diretamente no navegador. O guia Discover three.js oferece uma introdução pedagógica e detalhada, ideal para iniciantes que desejam criar aplicações profissionais de alto desempenho sem a necessidade de hardware robusto. Complementarmente, a plataforma NiksCourses disponibiliza treinamentos voltados ao desenvolvimento de jogos e tecnologias WebXR, utilizando exemplos práticos e integração com ferramentas como o Unity. A documentação técnica oficial e o repositório do GitHub detalham a vasta infraestrutura da biblioteca, incluindo sistemas de animação, iluminação, materiais e geometrias. Juntos, esses materiais compõem um ecossistema completo para o aprendizado e a implementação de conteúdos visuais complexos e interativos na web.

Hoje • 18:37
Por onde eu devo começar meus estudos no Three.js? Qual as melhores ferramentas?

Para começar seus estudos no Three.js de forma estruturada e eficiente, o ideal é focar nos fundamentos antes de avançar para técnicas complexas. Com base nas fontes, aqui está o caminho recomendado e as ferramentas essenciais:
Por onde começar os estudos
Conceitos Fundamentais: Antes de qualquer código complexo, entenda os quatro pilares que compõem uma cena Three.js: a Cena (Scene) (o contêiner), a Câmera (o ponto de vista), o Renderizador (Renderer) (o que desenha a cena) e os Objetos (Malhas/Meshes), que são formados por Geometria e Material
.
Recursos Gratuitos de Qualidade:
"Discover three.js": É considerado o "manual que faltava", oferecendo uma série de tutoriais gratuitos que cobrem desde o "Hello Cube" até iluminação e animação
.
Tutoriais no YouTube: Canais como Chris Courses (bom para setup com Vite) e Wael Yasmina (focado em simplificar WebGL) são excelentes para iniciantes
.
Cursos Completos (Pagos):
"Three.js Journey" (Bruno Simon): Frequentemente citado como o melhor recurso de aprendizado disponível, cobrindo do zero absoluto até níveis muito avançados
.
Three.js Bootcamp (Zero To Mastery): Uma alternativa prática de 20 horas que foca em construir um portfólio 3D
.
Melhores Ferramentas
Para um fluxo de trabalho profissional, as seguintes ferramentas são recomendadas:
Ambiente de Desenvolvimento: Utilize o Vite para configurar seus projetos. Ele é rápido, moderno e amplamente utilizado na comunidade para gerenciar o Three.js
.
Depuração e Ajustes em Tempo Real:
lil-gui ou Tweakpane: Permitem criar painéis de controle para ajustar cores, posições e intensidades de luz enquanto o código roda
.
stats-gl: Essencial para monitorar o desempenho, mostrando FPS e métricas de CPU/GPU
.
Spector.js: Uma extensão de navegador que permite capturar quadros e entender exatamente o que o computador está desenhando
.
Otimização de Assets:
gltf-transform: Uma ferramenta de linha de comando poderosa para comprimir e otimizar modelos 3D antes de carregá-los no navegador
.
Draco e KTX2: Bibliotecas de compressão para reduzir drasticamente o tamanho de geometrias e texturas, garantindo que sua página carregue rápido
.
Dica para o futuro (2026)
As fontes destacam que o WebGPURenderer é o novo padrão para alta performance, e aprender a nova linguagem de shaders da biblioteca, a TSL (Three Shader Language), é fundamental para quem deseja estar na vanguarda do desenvolvimento 3D na web
 |
 
<----------- com as técnicas de engenharia de prompt ------------------>

| **Prompt Otimizado** | "Contexto: Você é um tutor especialista em computação gráfica e Three.js, focado em ensinar iniciantes que já possuem base em JavaScript.
​Instrução Principal: Com base estritamente nas fontes fornecidas, elabore um roteiro de estudos lógico para eu dominar o Three.js do zero.
​Cadeia de Pensamento (Step-by-Step):
​Identifique os 5 conceitos fundamentais sem os quais nada funciona.
​Liste as ferramentas de desenvolvimento (ecosistema) recomendadas nos textos.
​Explique a ordem correta de aprendizado (ex: o que vem antes, Geometria ou Iluminação?).
​Restrições e Formato de Saída: > - Não utilize conhecimentos externos, foque no que está nos PDFs/Links.
​Apresente o roteiro em formato de tabela com as colunas: "Tópico", "Por que é importante" e "O que praticar".
​Ao final, crie um glossário com 5 termos técnicos essenciais encontrados nas fontes." | Resposta técnica, organizada em tabela e com glossário preciso. |

| 3- **Resultados** |  Logotipo do NotebookLM
Threes.js
Fontes
Conversa
Estúdio
🧊
Threes.js
14 fontes
Os recursos apresentados oferecem um guia abrangente sobre o Three.js, destacando a transição tecnológica para o renderizador WebGPU e o uso da nova linguagem de shaders TSL. As fontes compilam centenas de estratégias de otimização, como a compressão de ativos com Draco e KTX2, além de técnicas para reduzir chamadas de desenho via instanciamento e loteamento. Além de documentação técnica e fóruns de discussão, o material lista cursos educativos, tutoriais para iniciantes e livros especializados que ensinam desde os fundamentos até animações avançadas. O ecossistema inclui bibliotecas auxiliares para React Three Fiber, ferramentas de depuração e suporte para tecnologias imersivas como WebXR. No geral, os textos servem como um manual completo para desenvolvedores que buscam criar experiências 3D de alta performance e qualidade profissional diretamente no navegador.

Quais são as melhores práticas para otimizar a performance?
Como migrar de WebGL para o novo WebGPU Renderer?
Quais cursos e recursos são recomendados para iniciantes?
Hoje • 18:38
Por onde eu devo começar meus estudos no Three.js? Qual as melhores ferramentas?

Para começar seus estudos no Three.js de forma estruturada e eficiente, o ideal é focar nos fundamentos antes de avançar para técnicas complexas. Com base nas fontes, aqui está o caminho recomendado e as ferramentas essenciais:
Por onde começar os estudos
Conceitos Fundamentais: Antes de qualquer código complexo, entenda os quatro pilares que compõem uma cena Three.js: a Cena (Scene) (o contêiner), a Câmera (o ponto de vista), o Renderizador (Renderer) (o que desenha a cena) e os Objetos (Malhas/Meshes), que são formados por Geometria e Material
.
Recursos Gratuitos de Qualidade:
"Discover three.js": É considerado o "manual que faltava", oferecendo uma série de tutoriais gratuitos que cobrem desde o "Hello Cube" até iluminação e animação
.
Tutoriais no YouTube: Canais como Chris Courses (bom para setup com Vite) e Wael Yasmina (focado em simplificar WebGL) são excelentes para iniciantes
.
Cursos Completos (Pagos):
"Three.js Journey" (Bruno Simon): Frequentemente citado como o melhor recurso de aprendizado disponível, cobrindo do zero absoluto até níveis muito avançados
.
Three.js Bootcamp (Zero To Mastery): Uma alternativa prática de 20 horas que foca em construir um portfólio 3D
.
Melhores Ferramentas
Para um fluxo de trabalho profissional, as seguintes ferramentas são recomendadas:
Ambiente de Desenvolvimento: Utilize o Vite para configurar seus projetos. Ele é rápido, moderno e amplamente utilizado na comunidade para gerenciar o Three.js
.
Depuração e Ajustes em Tempo Real:
lil-gui ou Tweakpane: Permitem criar painéis de controle para ajustar cores, posições e intensidades de luz enquanto o código roda
.
stats-gl: Essencial para monitorar o desempenho, mostrando FPS e métricas de CPU/GPU
.
Spector.js: Uma extensão de navegador que permite capturar quadros e entender exatamente o que o computador está desenhando
.
Otimização de Assets:
gltf-transform: Uma ferramenta de linha de comando poderosa para comprimir e otimizar modelos 3D antes de carregá-los no navegador
.
Draco e KTX2: Bibliotecas de compressão para reduzir drasticamente o tamanho de geometrias e texturas, garantindo que sua página carregue rápido
.
Dica para o futuro (2026)
As fontes destacam que o WebGPURenderer é o novo padrão para alta performance, e aprender a nova linguagem de shaders da biblioteca, a TSL (Three Shader Language), é fundamental para quem deseja estar na vanguarda do desenvolvimento 3D na web
.
Contexto: Você é um tutor especialista em computação gráfica e Three.js, focado em ensinar iniciantes que já possuem base em JavaScript.
​Instrução Principal: Com base estritamente nas fontes fornecidas, elabore um roteiro de estudos lógico para eu dominar o Three.js do zero.
​Cadeia de Pensamento (Step-by-Step):
​Identifique os 5 conceitos fundamentais sem os quais nada funciona.
​Liste as ferramentas de desenvolvimento (ecosistema) recomendadas nos textos.
​Explique a ordem correta de aprendizado (ex: o que vem antes, Geometria ou Iluminação?).
​Restrições e Formato de Saída: > - Não utilize conhecimentos externos, foque no que está nos PDFs/Links.
​Apresente o roteiro em formato de tabela com as colunas: "Tópico", "Por que é importante" e "O que praticar".
​Ao final, crie um glossário com 5 termos técnicos essenciais encontrados nas fontes.

Para dominar o Three.js do zero, preparei um roteiro lógico baseado estritamente nas fontes fornecidas. Como você já possui base em JavaScript, o foco será entender como a biblioteca abstrai o WebGL para criar gráficos 3D no navegador
.
Ferramentas de Desenvolvimento (Ecossistema)
Antes de iniciar o código, utilize as ferramentas recomendadas para um fluxo de trabalho profissional:
Vite: Recomendado para configurar e gerenciar o projeto Three.js com rapidez
.
lil-gui ou Tweakpane: Essenciais para criar painéis de controle e ajustar parâmetros (como luz e posição) em tempo real
.
stats-gl ou three-perf: Para monitorar o desempenho, como frames por segundo (FPS) e uso de memória
.
Spector.js: Uma extensão de navegador para capturar quadros e depurar o que está sendo desenhado pela GPU
.
gltf-transform: Ferramenta de linha de comando para otimizar modelos 3D
.

--------------------------------------------------------------------------------
Roteiro de Estudos Lógico
A ordem de aprendizado começa pela estrutura básica (Cena/Câmera/Renderizador), seguida pela criação de objetos (Geometria/Material). Só então avançamos para Iluminação, pois as luzes precisam de superfícies para interagir, e finalizamos com otimização e tecnologias modernas como WebGPU
.
Tópico
Por que é importante
O que praticar
1. O Triângulo Fundamental
Sem o contêiner (Cena), o ponto de vista (Câmera) e o desenhista (Renderizador), nada aparece na tela
.
Configurar um arquivo index.html e inicializar o WebGLRenderer
.
2. Geometrias e Transformações
Define a forma física dos objetos (cubos, esferas) e como movê-los (translação, rotação, escala)
.
Criar um "Hello Cube" e alterar sua posição e escala via código
.
3. Materiais e Texturas
Determina a aparência visual (cor, reflexo, rugosidade) e como imagens 2D revestem os objetos
.
Aplicar MeshStandardMaterial e carregar uma textura básica de imagem
.
4. Iluminação e Sombras
Traz realismo e profundidade. Sem luz, materiais avançados ficam pretos; sombras dão senso de lugar
.
Adicionar uma AmbientLight para iluminação geral e uma DirectionalLight para criar sombras
.
5. Loop de Animação
É o "batimento cardíaco" do app, onde os objetos se movem a cada frame (geralmente 60 vezes por segundo) [1.7, 164].
Criar uma função de animação que rotaciona o objeto continuamente usando o método requestAnimationFrame
.
6. Carregamento de Modelos 3D
Permite usar ativos complexos criados em softwares como o Blender, em vez de apenas formas básicas
.
Usar o GLTFLoader para importar um modelo no formato .gltf ou .glb
.
7. WebGPU e TSL
É o futuro da biblioteca (2026), oferecendo alta performance e uma nova linguagem para criar efeitos (shaders)
.
Experimentar o WebGPURenderer e aprender as bases da Three Shader Language (TSL)
.

--------------------------------------------------------------------------------
Glossário: 5 Termos Técnicos Essenciais
Mesh (Malha): É o objeto 3D visível na cena, formado pela combinação de uma Geometria (forma) e um Material (aparência)
.
Draw Call (Chamada de Desenho): O comando que a CPU envia para a GPU desenhar um objeto. Para performance, recomenda-se manter abaixo de 100 por quadro
.
TSL (Three Shader Language): Linguagem baseada em nós que permite escrever shaders uma única vez e fazê-los funcionar tanto em WebGL quanto em WebGPU
.
WebGPU: Uma nova API gráfica que substitui o WebGL, oferecendo acesso mais direto à GPU e performance até 10x superior em cenas complexas
.
Draco Compression: Um sistema de compressão que reduz o tamanho de arquivos de geometria 3D em até 95%, acelerando o carregamento na web
..
 |

> **Reflexão Técnica:** Ao aplicar *Contexto* (Tutor de IA) e *Cadeia de Pensamento* (passo a passo), consegui filtrar informações obsoletas e focar apenas na sintaxe moderna (BufferGeometry e módulos ES6).

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto
[Cole aqui o roteiro de estudos/tabela que a IA gerou no segundo prompt]

### 2. Glossário de Conceitos Chave
* **Scene:** Onde todos os objetos, luzes e câmeras são colocados.
* **Camera:** Define o que será visto na tela (ex: Perspective vs Orthographic).
* **Renderer:** O "motor" que desenha a cena no `<canvas>`.
* **Mesh:** A combinação de uma Geometria (forma) com um Material (aparência).
* **Light:** Essencial para visualizar materiais que reagem à física (ex: StandardMaterial).

### 3. Biblioteca de Prompts Reutilizáveis
Para futuras revisões, utilize estes prompts:
```text
