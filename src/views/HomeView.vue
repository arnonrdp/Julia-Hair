<template>
  <section class="q-ma-sm text-center">
    <h2 class="text-h5 text-primary">Tenha um tratamento individualizado para sua queda capilar.</h2>
    <div class="row justify-center">
      <q-video class="full-width q-my-lg" src="https://www.youtube.com/embed/0aRMSj_qZq4" :ratio="16 / 9" />
      <!-- <q-img class="col-sm-5 col-xs-12 q-ma-sm radius-24" src="src/assets/cabelo1.jpg" spinner-color="primary" spinner-size="30rem" />
      <q-img class="col-sm-5 col-xs-12 q-ma-sm radius-24" src="src/assets/cabelo2.jpg" spinner-color="primary" spinner-size="30rem" /> -->
    </div>
    <q-btn color="primary" href="https://wa.me/5521973666897" rounded target="_blank">Quero agendar</q-btn>
  </section>

  <q-separator inset spaced />

  <section class="flex column items-center q-gutter-md">
    <h2 class="text-h5 text-primary">Se você...</h2>
    <div class="justify-center row text-center">
      <SmallCard imgName="icon-queda" label="Está passando por uma queda de cabelo acentuada" />
      <SmallCard imgName="icon-cabelo-fino" label="Sente que seu cabelo está ficando fino e o couro cabeludo aparente" />
      <SmallCard imgName="icon-cabelo-sumindo" label="Nota que seu cabelo está sumindo aos poucos" />
      <SmallCard imgName="icon-tratamento" label="Já fez diversos tratamentos e não teve resultado" />
      <SmallCard imgName="icon-cabelo-fragil" label="Sente que seu cabelo está frágil e quebradiço" />
    </div>
    <h2 class="text-h5 text-primary">Agende uma consulta capilar agora mesmo</h2>
    <q-btn color="primary" href="https://wa.me/5521973666897" rounded target="_blank">Agendar consulta</q-btn>
  </section>

  <q-separator inset spaced />

  <section class="row items-center justify-center">
    <h2 class="col-sm-6 col-xs-12 text-h5 text-center text-primary">
      Resultados dos tratamentos capilares realizados, tanto presencialmente quanto de forma online
    </h2>
    <q-img class="col-sm-6 col-xs-12 radius-24" src="src/assets/tratamento.jpg" spinner-color="primary" spinner-size="82px" width="400px" />
  </section>

  <q-separator inset spaced />

  <section class="q-ma-sm text-center">
    <h2 class="text-h5 text-primary">Por que buscar uma consulta capilar?</h2>
    <q-img class="radius-24" src="src/assets/queda-cabelo.jpg" spinner-color="primary" spinner-size="82px" width="400px" />
    <h2 class="text-h5 text-primary">Existem vários tipos de queda de cabelo</h2>
    <p class="text-body1 text-secondary">
      Queda de cabelo não é tudo igual. Existem vários tipos de alopecias e é preciso identificar qual é a sua, para então tratar da maneira
      correta.
    </p>
    <p class="text-body1 text-secondary">
      Todos os dias eu recebo pacientes que se queixam por já terem tomado várias vitaminas, usado tônicos variados e não tiveram resultado.
    </p>
    <p class="text-body1 text-secondary">Só resolvem buscar ajuda profissional quando o quadro já está avançado.</p>
    <h2 class="text-h5 text-primary">Você vai esperar chegar até que ponto para procurar um profissional qualificado para te ajudar?</h2>
    <q-img class="radius-24" src="src/assets/cabelos-secos.jpg" spinner-color="primary" spinner-size="82px" width="400px" />
    <h2 class="text-h5 text-primary">TEMPO É CABELO</h2>
    <p class="text-body1 text-secondary">
      Há casos em que o cabelo perdido não pode ser recuperado. Quanto antes iniciar o tratamento correto, melhores são as chances de um bom
      resultado.
    </p>
    <p class="text-body1 text-secondary">
      Coloque na ponta do lápis quanto você já gastou ou pensou em gastar com shampoos antiqueda que não funcionam, tônicos caseiros sem
      embasamento científico algum, e até produtos importados que prometiam resultados milagrosos.
    </p>
    <p class="text-body1 text-secondary">E o que aconteceu?</p>
    <h2 class="text-h5 text-primary">Você perdeu dinheiro, tempo... e cabelo!</h2>
    <p class="text-body1 text-secondary">
      É muito mais econômico que você agende primeiro uma consulta profissional, para investir no tratamento que é realmente indicado e
      efetivo para o seu caso.
    </p>
  </section>

  <q-separator inset spaced />

  <section class="q-ma-sm q-mb-xl text-center">
    <h2 class="text-h5 text-primary">Como funciona a consulta presencial?</h2>
    <p class="text-body1 text-secondary">
      A consulta presencial dura cerca de uma hora e acontece perante horário agendado, no seguinte endereço:
    </p>
    <address>Av. Roberto Silveira, 215 - Icaraí Av. Roberto Silveira, 215 - Icaraí, Niterói - RJ, 24230-151</address>
    <p class="text-body1 text-secondary">Ela se divide em 3 partes principais:</p>
    <section class="row justify-center q-gutter-xl q-ma-lg">
      <div class="col-md-3 col-sm-12 q-pa-lg q-mx-auto radius-24 bg-pink-2 shadow-2">
        <!-- TODO: Criar componente "BigCard.vue" para reutilizar cada um dos 3 cards abaixo -->
        <h6>
          1
          <br />
          Coleta de Informações
        </h6>
        <p>
          Após agendar seu horário, o paciente recebe um documento, via WhatsApp, com orientações de como se preparar para a consulta: fotos
          específicas e um exame físico simples que ele faz sozinho.
        </p>
        <p>As fotos devem ser enviadas previamente, junto com exames laboratoriais recentes e outros documentos importantes, se houver.</p>
        <p>O pagamento (Pix ou Cartão de Crédito) é feito nessa etapa.</p>
      </div>
      <div class="col-md-3 col-sm-12 q-pa-lg q-mx-auto radius-24 shadow-20">
        <h6>
          2
          <br />
          A Consulta
        </h6>
        <p>
          Durante a chamada de vídeo, várias perguntas são feitas ao paciente a fim de conhecer seu histórico referente a queixa, todo o
          caso clínico e qualquer outra informação relevante para identificação do tipo de queda.
        </p>
        <p>Ao final da consulta, será explicado todo o caso ao paciente e o tratamento será proposto e orientado.</p>
      </div>
      <div class="col-md-3 col-sm-12 q-pa-lg q-mx-auto radius-24 shadow-20">
        <h6>
          3
          <br />
          Pós Consulta
        </h6>
        <p>
          O acompanhamento do tratamento acontece via WhatsApp, diretamente comigo, e o paciente tem livre acesso para tirar suas dúvidas
          durante o tratamento.
        </p>
        <p>Quando necessário, é agendada a consulta de seguimento para avaliar a evolução e ajustar o tratamento.</p>
      </div>
    </section>
  </section>

  <q-separator inset spaced />
  <!-- TODO: Adicionar seção "Como funciona a consulta online" -->
  <!-- TODO: Adicionar component BigCard.vue que vc criou anteriormente e inserir: "Pré-Consulta", "A Consulta" e a "Pós Consulta" -->
  <!-- TODO: Incluir icones também -->
  <!-- Precisei me ausentar e não consegui dar continuidade abaixo -->
  <section class="q-ma-sm text-center">
    <h2 class="text-h5 text-primary">Como tratar a distância?</h2>
    <p>Ao final da consulta é enviado ao paciente, via WhatsApp, a prescrição de seu tratamento.</p>
    <p>O tratamento, na maioria das vezes,é oral (cápsula/sachê) e tópico (tônico/shampoo).</p>
    <p>O paciente manipula em uma farmácia de manipulação e faz o tratamento em casa.</p>
    <p>
      Se houver indicação de procedimento feito em clínica, o mesmo será indicado e orientado (a sugestão de frequência, intensidade,
      substâncias usadas e tempo). E então o paciente pode buscar em sua região uma clínica especializada que realize o procedimento em
      questão.
    </p>
    <button>Agendar Consulta Online</button>
    <div>
      <h5>Tratamento In & Out</h5>
      <p>
        Cabelo deve ser tratado de dentro para fora e de fora para dentro. O tratamento consiste em prescrição oral e tópica, somado a
        procedimentos em consultório.
      </p>
    </div>
    <div>
      <h5>Tratamento Individual</h5>
      <p>Cada queda de cabelo é única e não existe um tratamento milagroso e que atenda a todo mundo.</p>
    </div>
    <div>
      <h5>Contato via WhatsApp</h5>
      <p>O acompanhamento do tratamento é feito em contato direto comigo.</p>
    </div>
  </section>

  <section>
    <h4>Veja o que dizem sobre a consulta e o tratamento capilar</h4>
    <p>Colocar carrosel aqui.</p>
  </section>

  <section>
    <h6>Perguntas Frequentes</h6>
    <a href="" class="elemento">Qual a diferença da consulta presencial e online?</a>
  </section>

  <section class="flex column items-center q-gutter-md">
    <h4>Nosso Estabelecimento</h4>
    <p>Nosso estabelecimento está localizado no coração da cidade.</p>
    <iframe
      allowfullscreen
      class="q-mx-auto"
      loading="lazy"
      height="450"
      referrerpolicy="no-referrer-when-downgrade"
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3675.2854430393013!2d-43.109142985410834!3d-22.90284018501375!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9983e534f35a03%3A0x618cde7ed094c742!2sAv.%20Roberto%20Silveira%2C%20215%20-%20Icara%C3%AD%2C%20Niter%C3%B3i%20-%20RJ%2C%2024230-151!5e0!3m2!1spt-BR!2sbr!4v1665930973060!5m2!1spt-BR!2sbr"
      width="100%"
    />
  </section>
</template>

<script setup>
import SmallCard from '@/components/SmallCard.vue'
</script>
