---
title: "Laboratório de Neurociência e Comportamento"
layout: splash
permalink: /home/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/ib_700x350.png
  cta_label: "Repositórios"
  cta_url: "https://github.com/lab-neuro-comp"
  caption: "UnB - Instituto de Biologia"
excerpt: "Ferramentas utilizadas no Laboratório de Neurociência e Comportamento para auxiliar pesquisas."
intro:
  - excerpt: '`'

protolize_row:
  - image_path: /assets/images/p2.png
    alt: "protolize"
    title: "Protolize!"
    excerpt: '<a class="github-button" href="https://github.com/lab-neuro-comp/P2" data-icon="octicon-star" data-show-count="true" aria-label="Star lab-neuro-comp/P2 on GitHub">Star</a><br><br>
              Ferramenta educacional para processamento de sinais digitais. Roda em MATLAB e contém facilidades para o processamento de sinais eletroencefalográficos com o EEGLab.'
    url: "https://github.com/lab-neuro-comp/P2"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"

scalemate_row:
  - image_path: /assets/images/scalemate.png
    alt: "scalemate"
    title: "Scalemate"
    excerpt: '<a class="github-button" href="https://github.com/ishiikurisu/Scalemate" data-icon="octicon-star" data-show-count="true" aria-label="Star ishiikurisu/Scalemate on GitHub">Star</a>
              <br><br>Plataforma para aplicação de testes psicológicos de pergunta e resposta.'
    url: "https://github.com/ishiikurisu/Scalemate"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"

sst_row:
  - image_path: /assets/images/sst.ico
    alt: "sst"
    title: "SST"
    excerpt: '<a class="github-button" href="https://github.com/lab-neuro-comp/SST" data-icon="octicon-star" data-show-count="true" aria-label="Star lab-neuro-comp/SST on GitHub">Star</a>
              <br><br>Sistema que inclui a implementação do teste Stop-Signal e uma suíte de processamento de dados.'
    url: "https://github.com/lab-neuro-comp/SST"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"


testplatform_row:
  - image_path: /assets/images/testplatform.ico
    alt: "test-platform"
    title: "TestPlatform"
    excerpt: '<a class="github-button" href="https://github.com/lab-neuro-comp/Test-Platform/releases/download/v2.0/TestPlatform_pt-BR.exe" data-icon="octicon-cloud-download" data-size="large" aria-label="Download lab-neuro-comp/Test-Platform on GitHub">Download pt-BR</a>
              <a class="github-button" href="https://github.com/lab-neuro-comp/Test-Platform/releases/download/v2.0/TestPlatform_en-US.exe" data-icon="octicon-cloud-download" data-size="large" aria-label="Download lab-neuro-comp/Test-Platform on GitHub">Download en-US</a>
              <a class="github-button" href="https://github.com/lab-neuro-comp/Test-Platform" data-size="large" data-icon="octicon-star" data-show-count="true" aria-label="Star lab-neuro-comp/Test-Platform on GitHub">Star</a> <br><br>
              Plataforma de testes neuropsicológicos de diferentes paradigmas, tais como teste de tempo de reação e stroop.'
    url: "https://github.com/lab-neuro-comp/Test-Platform"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"

eeglab_row:
  - image_path: /assets/images/eeglab.jpg
    alt: "eeglab"
    title: "EEGLab"
    excerpt: 'Ferramenta para processamento de sinais eletroencefalográficos para o MATLAB desenvolvida pela Universidade da Califórnia.'
    url: "https://sccn.ucsd.edu/eeglab/downloadtoolbox.php"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"

matlab_row:
  - image_path: /assets/images/matlab.jpg
    alt: "matlab"
    title: "MATLAB"
    excerpt: 'Plataforma computacional para cálculo numérico com sua própria linguagem de programação. Este programa já está instalado nos computadores do laboratório'
    url: "https://mathwork.com/help/matlab"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"

eprime_row:
  - image_path: /assets/images/eprime.jpg
    alt: "eprime"
    title: "E-prime"
    excerpt: 'Uma coleção de programas voltados para a confecção, aplicação e análise de testes psicológicos.'
    url: "https://pstnet.com/products/e-prime/"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"

pebl_row:
  - image_path: /assets/images/pebl.jpg
    alt: "pebl"
    title: "PEBL"
    excerpt: 'Programa para criação e execução de testes psicológicos com uma interface gráfica'
    url: "http://pebl.sourceforge.net/"
    btn_label: "Saiba Mais"
    btn_class: "btn--primary"
---

<div align="center">
<h1>Ferramentas desenvolvidas no Laboratório</h1>
</div>

{% include feature_row id="intro" type="center" %}


{% include feature_row  id="protolize_row" type="left" %}

{% include feature_row id="scalemate_row" type="left" %}

{% include feature_row id="sst_row" type="left" %}

{% include feature_row id="testplatform_row" type="left" %}

<div align="center">
<h1>Ferramentas externas utilizadas no Laboratório</h1>
</div>

{% include feature_row id="intro" type="center" %}
{% include feature_row id="eeglab_row" type="left" %}

{% include feature_row id="matlab_row" type="left" %}

{% include feature_row id="eprime_row" type="left" %}

{% include feature_row id="pebl_row" type="left" %}
<!-- Place this tag in your head or just before your close body tag. -->
<script async defer src="https://buttons.github.io/buttons.js"></script>
