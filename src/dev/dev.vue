<template>
  <aside class="dev">
    <div class="item">
      <VueComponentsTemplate position="" className="red"
                   url="http://oss.zhulogic.com/product_image/cp083b70a1d989419481acf884557c5a41.jpg?x-oss-process=style/w660">
      </VueComponentsTemplate>
    </div>
    <div class="item">
      <VueComponentsTemplate position="x" className="green"
                   url="http://oss.zhulogic.com/product_image/cp083b70a1d989419481acf884557c5a41.jpg?x-oss-process=style/w660">
      </VueComponentsTemplate>
    </div>
    <div class="item">
      <VueComponentsTemplate position="y" className="blue"
                   url="http://oss.zhulogic.com/product_image/cp083b70a1d989419481acf884557c5a41.jpg?x-oss-process=style/w660">
      </VueComponentsTemplate>
    </div>
  </aside>
</template>
<script>
  import VueComponentsTemplate from '../components/vue-components-template.vue'

  export default {
    data() {
      return {};
    },
    methods: {},
    components: {VueComponentsTemplate}
  };
</script>
<style rel="stylesheet/scss" lang="scss">
  .dev {
    .item {
      float: left;
      margin-right: 20px;
      .red {
        border: 1px solid #f00;
      }
      .green {
        border: 1px solid #0f0;
      }
      .blue {
        border: 1px solid #00f;
      }
    }
  }


</style>

