
<template>
  <div>
    <v-dialog
      v-model="dialog"
      width="800"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="cyan lighten-1"
          dark
          v-bind="attrs"
          v-on="on"
        >
          Medidas
        </v-btn>
      </template>

      <v-card color="basil" >
        <v-card-title class="text-h5 grey lighten-2">
          Medidas Preventivas
        </v-card-title>

        <v-card-text>
          <p class="text-h6 ml-4">Tomando Medidas para um Futuro Sustentável</p>
      <p class="ml-4 d-flex text-justify mr-3">
        Para enfrentar esses desafios complexos, é necessário um esforço global
        coordenado e ação política decisiva. Os governos, instituições
        internacionais, setor privado e sociedade civil devem trabalhar juntos
        para implementar soluções sustentáveis e resilientes. Isso inclui a
        adoção de políticas de energia limpa e a transição para fontes
        renováveis de energia, como solar, eólica e hidrelétrica. Além disso, é
        crucial investir em tecnologias de baixo carbono, promover práticas
        agrícolas sustentáveis e preservar florestas e ecossistemas terrestres e
        marinhos. A criação de parcerias globais para compartilhar conhecimento,
        recursos e melhores práticas é fundamental para impulsionar a inovação e
        acelerar a transição para uma economia verde e sustentável. Ao mesmo
        tempo, é importante garantir que as comunidades mais vulneráveis tenham
        acesso a recursos e capacitação para enfrentar os desafios da mudança
        climática e da conservação marinha.
      </p>
      <p class="text-h6 ml-4">
        Ação Pró-Ativa na Mitigação dos Impactos Humanos sobre o Meio Ambiente:
        Salvaguardando o Futuro da Terra e dos Oceanos
      </p>
      <p class="ml-4 d-flex text-justify mr-3">
        A crise ambiental que enfrentamos atualmente exige uma abordagem
        pró-ativa e colaborativa na busca de soluções que reduzam ou cessem os
        impactos prejudiciais que os seres humanos exercem sobre o meio
        ambiente. A mudança climática e a degradação dos ecossistemas marinhos
        são sintomas alarmantes desse desafio global, exigindo ação imediata e
        decisiva para proteger nosso planeta para as gerações futuras.
      </p>
      <p class="text-h6 ml-4">Compreendendo a Urgência da Ação</p>
      <p class="ml-4 d-flex text-justify mr-3">
        A evidência científica é clara: a atividade humana está impulsionando
        mudanças significativas no clima do nosso planeta e causando danos
        irreversíveis aos ecossistemas marinhos. Desde o aumento das
        temperaturas globais até a acidificação dos oceanos, os impactos da
        nossa atividade são evidentes e urgentes. No entanto, a proatividade na
        busca de soluções pode oferecer esperança diante desses desafios.
      </p>
      <p class="text-h6 ml-4">
        Promovendo a Inovação e a Tecnologia Sustentável
      </p>
      <p class="ml-4 d-flex text-justify mr-3">
        Uma abordagem proativa na mitigação dos impactos ambientais requer
        investimentos significativos em inovação e tecnologia sustentável. Isso
        significa desenvolver e implementar fontes de energia renovável, como
        solar e eólica, que reduzam nossa dependência de combustíveis fósseis e
        diminuam as emissões de gases de efeito estufa. Além disso, é crucial
        promover práticas agrícolas sustentáveis que preservem a biodiversidade
        do solo, reduzam o desperdício de água e evitem a degradação dos
        ecossistemas terrestres. A agricultura regenerativa e o manejo florestal
        sustentável são exemplos de abordagens que podem ajudar a mitigar os
        impactos negativos da agricultura convencional.
      </p>
      <p class="ml-4 d-flex text-justify mr-3">
        Enfrentar os desafios ambientais que enfrentamos requer uma abordagem
        proativa e colaborativa na busca de soluções sustentáveis. Ao investir
        em inovação e tecnologia, fortalecer a governança e a cooperação
        internacional, e promover a educação e a conscientização pública,
        podemos mitigar os impactos prejudiciais que os seres humanos exercem
        sobre o meio ambiente e garantir um futuro sustentável para o nosso
        planeta e para as gerações futuras. A hora de agir é agora.
      </p>        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            text
            @click="dialog = false"
          >
            Fechar
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
</template>
<script>
  export default {
    data () {

      return {
        dialog: false,
        items: [
          { title: 'Home: Página Inicial', icon: 'mdi-view-dashboard' },
          { title: 'Email: meioAmbiente@hotmail.com', icon: 'mdi-forum' },
          { title: 'Telefone: 3367-XX90', icon: 'mdi-forum' },
        ],
      }

    },
  }
</script>