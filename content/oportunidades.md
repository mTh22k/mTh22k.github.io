---
title: Oportunidades
share: false
profile: false
show_date: false
reading_time: false
---

<style>
  /* Alarga consideravelmente o contêiner principal para ocupar as laterais */
  .article-container {
    max-width: 1300px !important;
    text-align: center !important;
    padding: 0 20px !important;
  }
  
  /* Centralização do título principal da página */
  h1, .article-title, .universal-wrapper h1 {
    text-align: center !important;
    width: 100% !important;
    margin-top: 30px !important;
    margin-bottom: 30px !important;
    font-weight: 800 !important;
    letter-spacing: -0.5px !important;
  }

  /* Oculta as informações de data e autoria do tema */
  .article-metadata {
    display: none !important;
  }

  /* Nova estrutura de grade configurada para 2 colunas lado a lado */
  .grid-oportunidades {
    display: grid !important;
    grid-template-columns: repeat(2, 1fr) !important;
    gap: 30px !important;
    margin: 40px auto !important;
    max-width: 1250px !important;
    text-align: center !important;
  }

  /* Responsividade: vira uma única coluna caso seja acessado pelo celular */
  @media (max-width: 768px) {
    .grid-oportunidades {
      grid-template-columns: 1fr !important;
      gap: 20px !important;
    }
  }

  /* Card Premium estruturado em coluna para empurrar o botão para a base */
  .card-premium {
    border-radius: 16px !important;
    padding: 40px 35px !important;
    text-align: center !important;
    box-sizing: border-box !important;
    display: flex !important;
    flex-direction: column !important;
    justify-content: space-between !important;
    box-shadow: 0 4px 20px rgba(0,0,0,0.01) !important;
  }

  /* Cores translúcidas que se adaptam aos temas claro e escuro */
  .card-ic {
    background: rgba(49, 130, 206, 0.04) !important;
    border: 1px solid rgba(49, 130, 206, 0.15) !important;
  }
  .card-monitoria {
    background: rgba(56, 161, 105, 0.04) !important;
    border: 1px solid rgba(56, 161, 105, 0.15) !important;
  }
  .card-ej {
    background: rgba(221, 107, 32, 0.04) !important;
    border: 1px solid rgba(221, 107, 32, 0.15) !important;
  }
  .card-extensao {
    background: rgba(183, 121, 31, 0.04) !important;
    border: 1px solid rgba(183, 121, 31, 0.15) !important;
  }

  .card-premium h3 {
    margin-top: 0 !important;
    margin-bottom: 0 !important;
    font-size: 1.4rem !important;
    font-weight: 700 !important;
    letter-spacing: -0.3px !important;
  }

  /* Traço indicador minimalista */
  .card-divider {
    width: 35px !important;
    height: 3px !important;
    margin: 15px auto 22px auto !important;
    border-radius: 2px !important;
  }

  .card-premium p {
    margin-top: 0 !important;
    margin-bottom: 30px !important;
    font-size: 0.98rem !important;
    line-height: 1.7 !important;
    text-align: center !important;
    opacity: 0.85 !important;
  }

  /* Botões em formato de pílula */
  .btn-premium {
    display: inline-block !important;
    background-color: #3182ce !important;
    color: #ffffff !important;
    padding: 12px 32px !important;
    border-radius: 30px !important;
    text-decoration: none !important;
    font-weight: 600 !important;
    font-size: 0.8rem !important;
    text-transform: uppercase !important;
    letter-spacing: 1px !important;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05) !important;
    align-self: center !important;
    margin-top: auto !important; /* Garante o alinhamento horizontal perfeito na base */
  }

  .btn-premium:hover {
    opacity: 0.95 !important;
    color: #ffffff !important;
    text-decoration: none !important;
    box-shadow: 0 6px 15px rgba(0,0,0,0.1) !important;
  }
</style>

<div style="font-size: 1.15rem; line-height: 1.8; margin-bottom: 20px; max-width: 850px; margin-left: auto; margin-right: auto; text-align: center !important; opacity: 0.95;">
  O curso de Informática Biomédica incentiva a participação dos estudantes em diversas atividades acadêmicas e profissionais que enriquecem a formação científica, prática e de integração com a sociedade.
</div>

<div class="grid-oportunidades">

  <div class="card-premium card-ic">
    <div>
      <h3 style="color: #3182ce;">Iniciação Científica</h3>
      <div class="card-divider" style="background-color: #3182ce;"></div>
      <p>É uma atividade acadêmica que permite ao estudante de graduação participar de projetos de pesquisa orientados por um professor da UFPR, podendo ser realizada com bolsa ou de forma voluntária. Por meio dela, o(a) aluno(a) tem contato com métodos e práticas de investigação, podendo explorar temas de interesse e, muitas vezes, apresentar resultados da pesquisa em eventos científicos.</p>
    </div>
    <a href="https://prppg.ufpr.br/" target="_blank" class="btn-premium">Mais Informações</a>
  </div>

  <div class="card-premium card-monitoria">
    <div>
      <h3 style="color: #38a169;">Monitoria</h3>
      <div class="card-divider" style="background-color: #38a169;"></div>
      <p>É uma atividade acadêmica em que estudantes de graduação auxiliam colegas em disciplinas que já cursaram, sob a orientação de um professor da UFPR. O monitor apoia na resolução de dúvidas, realiza atendimentos e pode colaborar em aulas práticas. Além de reforçar o próprio conhecimento, a monitoria desenvolve habilidades de comunicação e didática, sendo uma atividade que pode ser realizada com bolsa ou de forma voluntária.</p>
    </div>
    <a href="https://prograp.ufpr.br/coafe/uaf/monitoria/" target="_blank" class="btn-premium" style="background-color: #38a169 !important;">Mais Informações</a>
  </div>

  <div class="card-premium card-ej">
    <div>
      <h3 style="color: #dd6b20;">Empresa Júnior</h3>
      <div class="card-divider" style="background-color: #dd6b20;"></div>
      <p>É uma atividade acadêmica que permite aos estudantes vivenciar, na prática, o desenvolvimento de projetos e a interação com pessoas e empresas do mercado de tecnologia. Na UFPR, temos a Empresa Júnior de Informática (Ecomp) que integra estudantes dos cursos de Informática Biomédica, Ciência da Computação e Tecnologia em Análise e Desenvolvimento de Sistemas. A participação é voluntária e o ingresso ocorre por meio de processo seletivo.</p>
    </div>
    <a href="https://ecomp.co/" target="_blank" class="btn-premium" style="background-color: #dd6b20 !important;">Acessar Site da Ecomp</a>
  </div>

  <div class="card-premium card-extensao">
    <div>
      <h3 style="color: #b7791f;">Projetos de Extensão</h3>
      <div class="card-divider" style="background-color: #b7791f;"></div>
      <p>É uma atividade em que estudantes têm a oportunidade de aplicar, na prática, os conhecimentos adquiridos no curso, por meio do desenvolvimento de ações e projetos voltados à sociedade. Essa atividade pode ocorrer com bolsa ou de forma voluntária, sob a orientação de um professor da UFPR. No Departamento de Informática existem diversos projetos de extensão coordenados pelos professores como: Liga Acadêmica de Informática em Saúde (Lainf), concat(Gurias), Proteca, Capimara, dentre outros.</p>
    </div>
    <a href="https://web.inf.ufpr.br/dinf/" target="_blank" class="btn-premium" style="background-color: #b7791f !important;">Projetos do Departamento</a>
  </div>

</div>
