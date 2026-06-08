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
      css_style: 'min-height: 60vh; padding: 350px 0; text-align: center !important;'
      css_class: 'hero-centered'
      #   gradient_end: "rgba(66, 184, 38, 0.8)"
      #   gradient_start: "rgba(0, 156, 59, 0.8)"
      #   text_color_light: true
      # css_style: "min-height: 100vh; padding: 400px 0; text-align: center !important;"
      # css_class: "hero-centered"

  - block: features
    id: about
    content:
      title: |
        <span style="font-size: 1em;">Sobre o curso</span>
      text: |
        <div style="max-width: 900px; margin: 0 auto; text-align: left !important; font-size: 1.05rem; line-height: 1.7;">
          <div style="margin-bottom: 40px;">
            <p>O curso de <strong>Bacharelado em Informática Biomédica da UFPR</strong> oferece uma formação interdisciplinar, integrando as áreas de Ciências Exatas, Biológicas e da Saúde.</p>
            <p>São ofertadas <strong>30 vagas anuais</strong>, com ingresso sempre no primeiro semestre.</p>
            <p>Criado em 2011, o curso tem a duração de 4 anos e é ofertado no campus do <strong>Centro Politécnico da UFPR</strong> com aulas predominantemente no período da tarde e noite (13h30 às 19h30).</p>
          </div>
          <div style="background: rgba(125, 125, 125, 0.04); padding: 30px; border-radius: 12px; border: 1px solid rgba(125,125,125,0.1);">
            <h4 style="font-size: 1.1rem; margin-top: 0; margin-bottom: 25px; font-weight: 700; text-align: center; text-transform: uppercase;">Áreas de Formação</h4>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 25px 40px;">
              <div>
                <div style="display: flex; justify-content: space-between; margin-bottom: 5px; font-size: 0.95rem;">
                  <span style="font-weight: 500;">Informática</span><strong>70%</strong>
                </div>
                <div style="background-color: rgba(125, 125, 125, 0.2); border-radius: 4px; height: 8px; width: 100%; overflow: hidden;">
                  <div style="background-color: #3182ce; height: 100%; width: 70%; border-radius: 4px;"></div>
                </div>
              </div>
              <div>
                <div style="display: flex; justify-content: space-between; margin-bottom: 5px; font-size: 0.95rem;">
                  <span style="font-weight: 500;">Biológicas</span><strong>13%</strong>
                </div>
                <div style="background-color: rgba(125, 125, 125, 0.2); border-radius: 4px; height: 8px; width: 100%; overflow: hidden;">
                  <div style="background-color: #38a169; height: 100%; width: 13%; border-radius: 4px;"></div>
                </div>
              </div>
              <div>
                <div style="display: flex; justify-content: space-between; margin-bottom: 5px; font-size: 0.95rem;">
                  <span style="font-weight: 500;">Matemática</span><strong>9%</strong>
                </div>
                <div style="background-color: rgba(125, 125, 125, 0.2); border-radius: 4px; height: 8px; width: 100%; overflow: hidden;">
                  <div style="background-color: #dd6b20; height: 100%; width: 9%; border-radius: 4px;"></div>
                </div>
              </div>
              <div>
                <div style="display: flex; justify-content: space-between; margin-bottom: 5px; font-size: 0.95rem;">
                  <span style="font-weight: 500;">Saúde</span><strong>6%</strong>
                </div>
                <div style="background-color: rgba(125, 125, 125, 0.2); border-radius: 4px; height: 8px; width: 100%; overflow: hidden;">
                  <div style="background-color: #319795; height: 100%; width: 6%; border-radius: 4px;"></div>
                </div>
              </div>
              <div>
                <div style="display: flex; justify-content: space-between; margin-bottom: 5px; font-size: 0.95rem;">
                  <span style="font-weight: 500;">Estatística</span><strong>2%</strong>
                </div>
                <div style="background-color: rgba(125, 125, 125, 0.2); border-radius: 4px; height: 8px; width: 100%; overflow: hidden;">
                  <div style="background-color: #718096; height: 100%; width: 2%; border-radius: 4px;"></div>
                </div>
              </div>
            </div>
          </div>
        </div>

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
      title: '<span>Endereço</span>'
      text: |
      address:
        street: R. Evaristo F. Ferreira da Costa, 383-391
        city: Curitiba
        region: PR
        postcode: '82590-300'
        country: Brazil
        country_code: BR
      coordinates:
        latitude: '-25.451115'
        longitude: '-49.232082'
      autolink: true
    design:
      columns: '1'
---
