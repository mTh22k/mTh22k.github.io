---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: hero
    content:
      title: |
        **Informatica Biomedica**
        <br>
        <span style="font-size: 0.6em;">UFPR</span>
    design:
      background:
        image:
          filename: background-curso.jpg
          filters:
            brightness: 0.6
          parallax: false
          position: center
          size: cover
        gradient_end: "rgba(66, 184, 38, 0.8)"
        gradient_start: "rgba(0, 156, 59, 0.8)"
        text_color_light: true
      css_style: "min-height: 100vh; padding: 400px 0; text-align: center !important;"
      css_class: "hero-centered"

  - block: features
    id: about
    content:
      title: |
        <span style="font-size: 1em;">Sobre o curso</span>
      text: |
        <br>
        <p>O curso de Informática Biomédica da UFPR conta como diferencial uma formação predominante na área de Computação. A dinâmica de formação do aluno contempla o conhecimento conceitual em Ciências Exatas, Biológicas e Saúde ao longo dos 4 anos do curso.</p>
        <p>O curso oferta 30 vagas anuais com ingresso no primeiro semestre e teve início em 2011.</p>
        <p>As aulas são realizadas no campus do Centro Politécnico e exigem dedicação em tempo integral, com aulas entre 13h30 e 19h30, sendo que eventualmente alguma disciplina pode ocorrer em outro horário.</p>

    # Seção 3: "Caixas" com as Áreas do Curso
  - block: features
    active: true
    content:
      # O título desta seção de caixas
      title: Áreas de Atuação
      # A lista de caixas/features
      items:
        - name: Bioinformática
          description: Análise de dados genômicos, proteômica e desenvolvimento de algoritmos para biologia molecular.
          icon: dna # Ícone de DNA
          icon_pack: fas # Pacote de ícones (Font Awesome Solid)
        - name: Processamento de Imagens Médicas
          description: Análise e processamento de imagens de exames como ressonância magnética, tomografia e raios-X.
          icon: camera-retro # Ícone de câmera
          icon_pack: fas
        - name: Registros Clínicos e Saúde Pública
          description: Gerenciamento de sistemas de informação hospitalar, prontuários eletrônicos e análise de dados de saúde.
          icon: notes-medical # Ícone de prontuário médico
          icon_pack: fas

  - block: contact
    id: contact
    content:
      title: "<span>Endereço</span>"
      text: |
        e-mail: ibm@inf.ufpr.br
      address:
        street: R. Evaristo F. Ferreira da Costa, 383-391
        city: Curitiba
        region: PR
        postcode: "82590-300"
        country: Brazil
        country_code: BR
      coordinates:
        latitude: "-25.451115"
        longitude: "-49.232082"
      autolink: true
    design:
      columns: "1"
---
