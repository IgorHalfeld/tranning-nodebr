<template>
  <section class="section Communities">
    <div class="container CommunitiesContainer">
      <StyledTitle margin="0px 0px 60px 0px">Comunidades Parceiras</StyledTitle>
      <div>
        <a
          target="_blank"
          href="https://www.meetup.com/pt-BR/nodebr/?origin=CursoNodeBR">
          <img
            src="../assets/nodebr.jpg"
            alt="nodebr">
        </a>
        <a
          target="_blank"
          href="https://www.meetup.com/pt-BR/Javascript-SP/?origin=CursoNodeBR">
          <img
            src="../assets/jssp.jpeg"
            alt="jssp">
        </a>
        <a
          target="_blank"
          href="https://www.meetup.com/pt-BR/Nerdzao/?origin=CursoNodeBR">
          <img
            src="../assets/nerdzao.jpeg"
            alt="nerdzao">
        </a>
        <a
          target="_blank"
          href="https://www.facebook.com/groups/534575580022737/?origin=CursoNodeBR">
          <img
            :style="{
              width: '130px'
            }"
            src="../assets/nerdgirlz.jpg"
            alt="nerdgirlz">
        </a>
      </div>
      <div>
        <a
          target="_blank"
          href="https://www.meetup.com/pt-BR/THT-Things-Hacker-Team/?origin=CursoNodeBR">
          <img
            src="../assets/tht.png"
            alt="tht">
        </a>
        
        <a
          target="_blank"
          href="https://criciumadev.com.br/?origin=CursoNodeBR">
          <img
            :style="{
              width: '180px'
            }"
            src="../assets/criciuma.svg"
            alt="criciuma">
        </a>
        <a
          target="_blank"
          href="https://loiane.training/?origin=CursoNodeBR">
          <img
            :style="{
              width: '200px'
            }"
            src="../assets/loianetraining.png"
            alt="Loiane Trainning">
        </a>
        <a
          target="_blank"
          href="https://workweb.congressodeti.com.br/?origin=CursoNodeBR">
          <img
            :style="{
              width: '180px'
            }"
            src="../assets/congresso-ti.png"
            alt="Congresso de TI">
        </a>
        
      </div>
      <div>
        
        <a
          target="_blank"
          href="https://www.meetup.com/pt-BR/Coders-in-Rio/?origin=CursoNodeBR">
          <img
            src="../assets/coders-in-rio.png"
            alt="coders in rio">
        </a>
        
        
        <a
          target="_blank"
          href="https://www.meetup.com/pt-BR/graphdb-sp/?origin=CursoNodeBR">
          <img
            
            src="../assets/graph-databases-sp.jpeg"
            alt="graph databases sp">
        </a>
        <a
          target="_blank"
          href="https://www.meetup.com/pt-BR/nosqlsp?origin=CursoNodeBR">
          <img
            :style="{
              width: '150px'
            }"
            src="../assets/no-sql-sp.jpeg"
            alt="nosql sp">
        </a>
        <a
          target="_blank"
          href="https://fb.com/jundevelopers?origin=CursoNodeBR">
          <img
            
            src="../assets/jundevelopers.jpg"
            alt="JunDevelopers">
        </a>
        <a
          target="_blank"
          href="https://www.facebook.com/DownsHackerOficial?origin=CursoNodeBR">
          <img
            src="../assets/downshacker.png"
            alt="Downs Hacker">
        </a>
        
      </div>
      <div>
        <a
          target="_blank"
          href="https://www.meetup.com/WoMakersCode/?origin=CursoNodeBR">
          <img
            :style="{
              width: '150px'
            }"
            src="../assets/womakerscode.png"
            alt="Womakers Code">
        </a>
        <a
          target="_blank"
          href="https://codeprestige.com.br/?origin=CursoNodeBR">
          <img
            src="../assets/code-prestige.png"
            alt="code prestige">
        </a>
        <a
          target="_blank"
          href="https://reprograma.com.br?origin=CursoNodeBR">
          <img
            :style="{
              width: '150px'
            }"
            src="../assets/reprograma.png"
            alt="Reprograma">
        </a>
        
        <a
          target="_blank"
          href="https://react-brasil-slack.herokuapp.com?origin=CursoNodeBR">
          <img
            
            src="../assets/reactbrasil.png"
            alt="React Brasil">
        </a>
        
        <a
          target="_blank"
          href="https://www.facebook.com/thememecode/?origin=CursoNodeBR">
          <img
            :style="{
              width: '80px'
            }"
            src="../assets/memecode.png"
            alt="memecode">
        </a>
      </div>
    </div>
  </section>
</template>

<script>
import StyledTitle from './Title';
export default {
  name: 'Commuties',
  components: { StyledTitle },
};
</script>

<style lang="scss" scoped>
.Communities {
  > .CommunitiesContainer {
    display: flex;
    flex-direction: column;
    align-items: center;

    > div {
      display: flex;
      flex-wrap: wrap;
      flex-direction: row;
      @media screen and (max-width: 700px) {
        flex-direction: column;
      }

      > a {
        display: flex;
        justify-content: center;
        align-items: center;

        @media screen and (max-width: 700px) {
          margin-top: 20px;
        }
        > img {
          display: inline-block;
          vertical-align: middle;
          max-width: 90%;
          width: 100px;
          height: auto;
          margin: 0 12px 20px 12px;
        }
      }
    }
  }
}
</style>
