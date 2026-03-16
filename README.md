<h2>🚗 Detecção automática de vagas de estacionamento usando Visão Computacional</h2>

<p>
Este projeto implementa um sistema capaz de identificar vagas livres e ocupadas em um estacionamento a partir da análise de vídeo utilizando <b>Python</b> e <b>OpenCV</b>.
</p>

<p>
O algoritmo realiza o processamento do vídeo <i>frame a frame</i>, aplicando técnicas de processamento digital de imagens para detectar a ocupação das vagas.
</p>

<h3>Etapas do algoritmo</h3>

<ul>
<li>Conversão da imagem para escala de cinza</li>
<li>Aplicação de <b>Gaussian Blur</b> para redução de ruído</li>
<li>Aplicação de <b>threshold adaptativo</b></li>
<li>Uso de <b>operações morfológicas</b> para melhorar a segmentação</li>
<li>Análise de pixels por região de interesse (<b>ROI</b>) correspondente a cada vaga</li>
</ul>

<p>
Ao final do processamento, o sistema gera um novo vídeo contendo a identificação das vagas de estacionamento, destacando visualmente as vagas livres e ocupadas.
</p>

<h3>Tecnologias utilizadas</h3>

<ul>
<li>Python</li>
<li>OpenCV</li>
<li>Computer Vision</li>
</ul>

Site: https://ingridmxavier.github.io/visao_computacional/
