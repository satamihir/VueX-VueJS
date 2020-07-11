<template>
    <div class="row">
      <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
          <h1>Vuex</h1>
          <br>
          <appCounter ></appCounter>
          <br>
          <appAcounter></appAcounter>
          <hr>
          <appResult></appResult>
          <appAResult></appAResult>
      </div>
    </div>
</template>

<script>
import Counter from './components/Counter';
import Acounter from './components/Acounter';
import Result from './components/Result';
import AResult from './components/AResult';
export default{
  components:{
    appCounter: Counter,
    appAcounter: Acounter,
    appResult: Result,
    appAResult: AResult
  }
}
</script>

<style lang="scss">

</style>
