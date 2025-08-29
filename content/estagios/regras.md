---
# Título da página que aparece na aba do navegador e nos menus
title: "Regras de Estágio"
date: "2025-08-29"
# Define que esta página será construída com "blocos"
type: landing

sections:
  # Bloco 1: Introdução e Definição de Estágio
  - block: markdown
    id: definicao
    content:
      title: "O que é um Estágio?"
      subtitle: "Diretrizes para estudantes do curso de Informática Biomédica da UFPR"
      text: |
        <p style="text-align: justify;">
        <strong>Estágio</strong> é uma atividade desenvolvida por um estudante em uma empresa ou outra instituição, na área do curso, visando proporcionar ao(à) estudante a oportunidade de colocar em prática os conhecimentos adquiridos. Um estágio pode ter até 6 horas diárias, até 30 horas semanais e até 24 meses na mesma empresa.
        </p>
        <div class="alert alert-warning">
        <strong>Atenção:</strong> Todo estágio deve ser previamente autorizado pelo curso e pela universidade. Sem essa autorização prévia, seu estágio não existe oficialmente e seu trabalho nele é ilegal.
        </div>

  # Bloco 2: Regulamentação e Normas Principais
  - block: features
    id: normas
    content:
      title: "Regulamentação e Normas"
      items:
        - name: "Legislação"
          description: "Os estágios são regulados pela <strong>Lei Federal 11.788/2008</strong> e pelo <strong>Manual de Estágios da COAFE/UFPR</strong>."
          icon: gavel
          icon_pack: fas
        - name: "Regra da Barreira"
          description: "Estudantes que não superaram as disciplinas da barreira <strong>não possuem autorização</strong> para estagiar, salvo exceções analisadas pela COE."
          icon: university
          icon_pack: fas
        - name: "Requisito de Aprovação"
          description: "Após a barreira, o(a) estudante deve ter sido aprovado(a) em, no mínimo, <strong>50% das disciplinas</strong> cursadas no semestre anterior."
          icon: user-check
          icon_pack: fas

  # Bloco 3: Link para Formulários
  - block: features
    id: formularios
    content:
      title: "Precisa dos Formulários?"
      # Vamos modificar o campo 'text' para adicionar o HTML do botão
      text: |
        <div class="container text-center">
          <p class="lead" style="font-size: 1.2rem;">
            Acesse a página da COAFE – Unidade de Estágio – para encontrar todos os formulários úteis para a contratação, regularização e encerramento de estágios na UFPR.
          </p>
          <a href="https://www.prograd.ufpr.br/portal/coafe/" class="btn btn-lg btn-light mt-3" target="_blank" rel="noopener">Acessar Página da COAFE</a>
        </div>
    # A seção 'cta' foi REMOVIDA daqui de baixo.
    design:
      background:
        color: "primary"
        # Recomendo usar 'true' aqui para que o texto principal fique branco e contraste com o fundo 'primary'
        text_color_light: false

  # Bloco 4: Entidades Envolvidas
  - block: markdown
    id: envolvidos
    content:
      title: "Entidades Envolvidas no Processo"
      text: |
        O processo de estágio envolve a coordenação de várias partes. É importante saber a quem se reportar:
        <ul>
          <li><strong>Estagiário(a):</strong> Estudante regularmente matriculado no curso.</li>
          <li><strong>Empresa:</strong> Local onde o estágio será realizado.</li>
          <li><strong>Supervisor(a):</strong> Profissional da empresa que acompanha o estágio.</li>
          <li><strong>Orientador(a):</strong> Professor(a) do curso que acompanha academicamente o estágio.</li>
          <li><strong>COE (Comissão Orientadora de Estágios):</strong> Comissão local do curso que avalia e autoriza os pedidos.</li>
          <li><strong>COAFE:</strong> Coordenação geral da UFPR que gerencia os estágios.</li>
          <li><strong>Secretaria do Curso:</strong> Realiza os trâmites administrativos.</li>
        </ul>

  # Bloco 5: Membros da COE e Aviso sobre Prazos
  - block: markdown
    id: coe
    content:
      title: "COE – Comissão Orientadora de Estágios"
      text: |
        Atualmente a comissão é formada pelos seguintes membros:
        <ul>
          <li>Prof. David Menotti</li>
          <li>Prof. Eduardo Jaques Spinosa</li>
          <li>Prof. Eduardo Todt</li>
          <li>Prof. Lucas Ferrari Oliveira</li>
          <li>Prof. Marco Antonio Zanata Alves</li>
        </ul>
        <div class="alert alert-info">
        <strong>Lembre-se:</strong> A assinatura de documentos pela COE ocorre após o envio por e-mail (ibm@inf.ufpr.br) para a secretaria, com um prazo médio de <strong>72 horas</strong> para retorno.
        </div>
---
