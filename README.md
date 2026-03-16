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

#### 1. Abordagem Básica (Sem técnicas aplicadas)
* **Prompt Utilizado:** > "Por onde eu devo começar meus estudos no Three.js? Qual as melhores ferramentas?"
* **Resultado Obtido:** A IA gerou uma resposta genérica e sem estrutura definida. Ela listou cursos pagos (como Bruno Simon e Zero To Mastery), canais do YouTube, ferramentas de desenvolvimento (Vite, lil-gui, Spector.js) e citou superficialmente os quatro pilares (Cena, Câmera, Renderizador e Objetos), além de mencionar o WebGPURenderer como tendência para o futuro.

#### 2. Abordagem Otimizada (Com Engenharia de Prompt)
* **Técnicas Aplicadas:** Contexto (Roleplay), Instrução Principal, Cadeia de Pensamento (Step-by-Step), Restrições e Formato de Saída.
* **Prompt Utilizado:**
> "Contexto: Você é um tutor especialista em computação gráfica e Three.js, focado em ensinar iniciantes que já possuem base em JavaScript.
> Instrução Principal: Com base estritamente nas fontes fornecidas, elabore um roteiro de estudos lógico para eu dominar o Three.js do zero.
> Cadeia de Pensamento (Step-by-Step):
> 1. Identifique os 5 conceitos fundamentais sem os quais nada funciona.
> 2. Liste as ferramentas de desenvolvimento (ecosistema) recomendadas nos textos.
> 3. Explique a ordem correta de aprendizado (ex: o que vem antes, Geometria ou Iluminação?).
> Restrições e Formato de Saída: Não utilize conhecimentos externos, foque no que está nos PDFs/Links. Apresente o roteiro em formato de tabela com as colunas: "Tópico", "Por que é importante" e "O que praticar". Ao final, crie um glossário com 5 termos técnicos essenciais encontrados nas fontes."
* **Resultado Obtido:** A IA entregou uma resposta técnica, organizada e restrita ao escopo solicitado. O resultado detalhado pode ser visto na seção "Miniguia de Estudo" abaixo.

> **Reflexão Técnica:** Ao aplicar *Contexto* (Tutor de IA) e *Cadeia de Pensamento* (passo a passo), consegui filtrar informações obsoletas ou externas (como propagandas de cursos) e focar estritamente no ecossistema e ferramentas modernas apontadas pelas fontes (como Vite, stats-gl e gltf-transform).

---

## 📖 Miniguia de Estudo (Entrega Final)

Com base no prompt otimizado, o NotebookLM gerou o seguinte roteiro lógico de aprendizado:

### 🚀 Ferramentas de Desenvolvimento (Ecossistema)
Antes de iniciar o código, o uso destas ferramentas é recomendado para um fluxo de trabalho profissional:
* **Vite:** Para configurar e gerenciar o projeto com rapidez.
* **lil-gui ou Tweakpane:** Para criar painéis de controle e ajustar parâmetros (luz, posição) em tempo real.
* **stats-gl ou three-perf:** Para monitorar desempenho (FPS, memória).
* **Spector.js:** Extensão para capturar quadros e depurar o desenho da GPU.
* **gltf-transform:** Ferramenta para otimizar modelos 3D.

### 🗺️ Roteiro Lógico de Estudos
A ordem de aprendizado correta inicia-se pela estrutura básica, passando para objetos, iluminação e, por fim, otimização e tecnologias modernas.

| Tópico | Por que é importante | O que praticar |
| :--- | :--- | :--- |
| **1. O Triângulo Fundamental** | Sem o contêiner (Cena), o ponto de vista (Câmera) e o desenhista (Renderizador), nada aparece na tela. | Configurar um arquivo `index.html` e inicializar o `WebGLRenderer`. |
| **2. Geometrias e Transformações** | Define a forma física dos objetos e como movê-los. | Criar um "Hello Cube" e alterar sua posição/escala via código. |
| **3. Materiais e Texturas** | Determina a aparência visual e como imagens 2D revestem os objetos. | Aplicar `MeshStandardMaterial` e carregar uma textura. |
| **4. Iluminação e Sombras** | Traz realismo e profundidade. A luz é necessária para materiais avançados. | Adicionar `AmbientLight` e `DirectionalLight` para criar sombras. |
| **5. Loop de Animação** | É o "batimento cardíaco" do app, animando objetos frame a frame. | Rotacionar um objeto continuamente usando `requestAnimationFrame`. |
| **6. Carregamento de Modelos 3D** | Permite usar ativos complexos (ex: do Blender). | Usar o `GLTFLoader` para importar modelos `.gltf` ou `.glb`. |
| **7. WebGPU e TSL** | É o futuro da biblioteca (2026), oferecendo alta performance. | Experimentar o `WebGPURenderer` e as bases da TSL. |

### 🔍 Glossário: 5 Termos Técnicos Essenciais
* **Mesh (Malha):** É o objeto 3D visível na cena, formado pela combinação de uma Geometria (forma) e um Material (aparência).
* **Draw Call (Chamada de Desenho):** O comando que a CPU envia para a GPU desenhar um objeto. Para performance, recomenda-se manter abaixo de 100 por quadro.
* **TSL (Three Shader Language):** Linguagem baseada em nós que permite escrever shaders uma única vez para WebGL e WebGPU.
* **WebGPU:** Nova API gráfica que substitui o WebGL, oferecendo acesso direto à GPU e performance até 10x superior.
* **Draco Compression:** Sistema que reduz o tamanho de arquivos de geometria 3D em até 95%, acelerando o carregamento.

