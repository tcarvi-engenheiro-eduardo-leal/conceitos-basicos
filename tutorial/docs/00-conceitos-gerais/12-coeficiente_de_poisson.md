# Coeficiente de Poisson

- Símbolo:
  - 𝜈
  - ν
- Também conhecido como **razão de Poisson**
- O coeficiente de Poisson é uma medida importante na engenharia estrutural que descreve a **relação entre as deformações laterais e longitudinais em um material quando submetido a uma carga externa**. É denominado em homenagem ao físico francês Siméon Poisson.
- Quando um material é esticado na direção longitudinal, ele tende a contrair na direção transversal. Quando um material é comprimido na direção longitudinal, ele tende a expandir na direção transversal. O coeficiente de Poisson quantifica essa resposta transversal.
- Fórmula:
  - 𝜈 = − (𝜖 transversal) /  (𝜖 longitudinal)
- O coeficiente de Poisson (geralmente denotado por ν) é definido como a razão entre a deformação lateral (ou transversal) e a deformação longitudinal de um material quando submetido a uma carga axial. Em uma aplicação estrutural, quando uma carga é aplicada a um material, ele se deforma em várias direções. O coeficiente de Poisson nos dá uma ideia de como o material se deforma nessas direções.
- Um material com um coeficiente de Poisson positivo indica que, quando ele é esticado longitudinalmente, ele se contrai lateralmente, enquanto um material com coeficiente de Poisson negativo (teoricamente possível, mas raro na prática) indicaria que se expande lateralmente quando esticado longitudinalmente.
- Na engenharia estrutural, entender o coeficiente de Poisson é fundamental para prever o comportamento de materiais sob carga e projetar estruturas que possam suportar as deformações esperadas sem falhar. 
- Ele é usado em uma variedade de aplicações, desde o projeto de pontes e edifícios até componentes em nível microscópico, como na fabricação de chips de computador.
​- O sinal negativo da fórmula indica que, para a maioria dos materiais, uma tensão de tração causa uma contração transversal, enquanto uma tensão de compressão causa uma expansão transversal. Usa-se o sinal negativo para ter sinal oposto a este significado.
- Valores Típicos:
  - Aço: Aproximadamente 0,28 a 0,30.
  - Concreto: Aproximadamente 0,15 a 0,20.
  - Borracha: Aproximadamente 0,45 a 0,50.
  - Alumínio: Aproximadamente 0,33.
- Os valores típicos do coeficiente de Poisson para diversos materiais variam entre 0 e 0,5:
  - Materiais incompressíveis: Para materiais como a borracha, que praticamente não mudam de volume sob compressão, ν aproxima-se de 0,5.
  - Materiais isotrópicos e elásticos: Para muitos metais e ligas, o coeficiente de Poisson está geralmente na faixa de 0,25 a 0,35.
- Importância em Engenharia Estrutural
  - Análise de Deformações: O coeficiente de Poisson é essencial para entender como os materiais se deformam sob cargas. 
  - Ele permite prever as deformações laterais, ajudando a avaliar a integridade estrutural e o desempenho de elementos de engenharia.

##  Exemplo de Cálculo:
- Suponha que temos um material de prova em forma de barra com uma seção transversal quadrada. Vamos aplicar uma força de tração na direção longitudinal da barra. Como resultado dessa força, a barra se esticará na direção longitudinal e se contrairá na direção transversal. Queremos calcular o coeficiente de Poisson desse material.
- Vamos denotar as seguintes grandezas:
  - ΔW: a mudança na largura da barra na direção transversal.
  - ΔL: a mudança no comprimento da barra na direção longitudinal.
  - L: comprimento original da barra.
  - W: largura original da barra.
  - ΔW/W = 𝜖 transversal: deformação transversal adimensional
  - ΔL/L = 𝜖 longitudinal: deformação longitudinal adimensional
- O coeficiente de Poisson (ν) pode ser calculado pela fórmula:
  - ν = − (ΔW/W) / (ΔL/L)
  - ν = − (𝜖 transversal) / (𝜖 longitudinal)
- Vamos supor que, após a aplicação da força:
  - a barra se estique longitudinalmente ΔL = 0.001L, ou seja, 0,1%.
  - a barra se contraia transversalmente ΔW = − 0.0002W, ou seja, 0,02%.
- Substituindo esses valores na fórmula, temos:
  - ν = − (−0.0002)/(0.001)
  - ν = − (- 0,2)
  - ν = 0,2 (medida adimensional)
- Neste caso hipotético, o coeficiente de Poisson do material é ν = 0.2
- Isso indica que o material se contrai lateralmente em 0,2 vezes a quantidade que se estica longitudinalmente quando submetido a uma carga axial.
