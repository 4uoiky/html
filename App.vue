<template>
  <div id="app">
    <!-- {{ msg }}
    <button @click="updateMsg">修改数据</button>
    <PublicHeader></PublicHeader>
    <PublicFooder></PublicFooder>
    <VueOne class="wp" id="wp" :send-msg="msg" :send-static=123 :send-obj="{ a: 1, b: 2 }"></VueOne>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <VueOne v-model="ckd"></VueOne>
    {{ ckd?"选中":"不选中" }}
    <VueOne @focus="oniptfcs" @blur="onIptBlur" v-model="value"></VueOne>
    <VueOne></VueOne>
    <VueOne></VueOne>
    <VueSlot>插槽信息</VueSlot>
    <VueSlot send-msg="信息">
      具名插槽
      <template v-slot:header>
        具名信息
      </template>
      作用域
      <template v-slot:default="getDt">{{ getDt.sendObj.nm }}</template>
      <template v-slot:slotC="getDt">{{ getDt.sendObj.age }}</template>
      动态插槽名
      <template v-slot:[dynamic]>动态插槽名D的内容</template>
      具名插槽的缩写
      <template #[dynamic]>动态插槽名E+具名插槽的缩写的内容</template>
    </VueSlot> -->
    <!-- <button v-for="(cmptItem,idx) in curArr" :key="idx" @click="switchCmpt(idx)"> 切换组件{{idx+1 }}</button>
    <keep-alive>
      <component :is="curCmpt"></component>
    </keep-alive> -->

    <!-- <CmptOne></CmptOne>
    <CmptTwo></CmptTwo> -->
    <!-- <VueCmptThree ref="chdTwo"></VueCmptThree> -->
    <!-- <button @click="getChdt">获取后代组件信息</button> -->
    <!-- <VueCommunication :sendP="pMsg" ref="chdOne" ></VueCommunication>
    <button @click="getChdFn">获取后代组件方法</button> -->
    <!-- <TreeLi @chdEvt="getChd" @chdEvtOnce.once="chdEvtOnce"></TreeLi> -->
    <!-- <MenuTree :treeData="treeData" @treeClk="getClkMsg"></MenuTree> -->
  </div>
</template>

<script>
// import VueCmptThreeVue from './components/VueCmptThree.vue';
// import HelloWorld from './components/HelloWorld.vue'
// import VueOne from "./components/vue-test.vue"
// import VueSlot from "./components/VueSlot.vue";
// import CmptOne from "./components/VueCmptOne.vue"
// import CmptTwo from "./components/VueCmptTwo.vue"
// import VueCommunication from './components/VueCommunication.vue';
// import VueCmptThree from './components/VueCmptThree.vue'
// import TreeLi from './components/TreeLi.vue'
// import MenuTree from "./components/MenuTree.vue";
export default {
  name: "App",
  // provide: function () {
  //   return {
  //     sendMsg: "祖先组件内定义的信息",
  //   };
  // },
  components: {
    // MenuTree,
    // TreeLi,
    // VueCommunication,
    // VueCmptThree
    // HelloWorld
    // VueOne
    // VueSlot
    // CmptOne,
    // CmptTwo
    // CmptTwo:()=>import("./components/VueCmptTwo.vue")
    // CmptTwo:()=>({
    //   component:import("./components/VueCmptTwo.vue")
    // })
  },
  data() {

    // return {
    //   treeData: [
    //     {
    //       treeId: 1,
    //       treeNm: "一级菜单1",
    //       children: [
    //         {
    //           treeId: 12,
    //           treeNm: "二级菜单12",
    //           children: [
    //             { treeId: 121, treeNm: "三级菜单121" },
    //             { treeId: 122, treeNm: "三级菜单122" },
    //             { treeId: 123, treeNm: "三级菜单123" },
    //           ],
    //         },
    //         { treeId: 13, treeNm: "二级菜单13" },
    //         {
    //           treeId: 14,
    //           treeNm: "二级菜单14",
    //           children: [{ treeId: 141, treeNm: "三级菜单141" }],
    //         },
    //       ],
    //     },
    //     { treeId: 2, treeNm: "一级菜单2" },
    //     {
    //       treeId: 3,
    //       treeNm: "一级菜单3",
    //       children: [
    //         {
    //           treeId: 31,
    //           treeNm: "二级菜单31",
    //           children: [
    //             { treeId: 311, treeNm: "三级菜单13" },
    //             { treeId: 312, treeNm: "三级菜单13" },
    //           ],
    //         },
    //         { treeId: 32, treeNm: "二级菜单32" },
    //       ],
    //     },
    //     {
    //       treeId: 4,
    //       treeNm: "一级菜单4",
    //       children: [{ treeId: 41, treeNm: "二级菜单41" }],
    //     },
    //   ],
    // };
  },

  // return {
  //   pMsg:"父组件信息"
  // }
  // return{
  //   curCmpt:"CmptOne",
  //   curArr:["CmptOne","CmptTwo"]
  // }
  // return {
  //   value: "123",
  //   ckd: true,
  //   a: 1,
  //   msg: "父组件信息",
  //   dynamic:"default",

  // }

  methods: {
    // getClkMsg(msg){
    //   console.log(msg);
    // }
    // getChdFn(){
    //   this.$refs.chdTwo.trigger()
    // },
    // getChdt(){
    //   console.log(this.$refs.chdOne.cMsg);
    // }
    // switchCmpt(idx){
    //   this.curCmpt=this.curArr[idx]
    // },
    // onIptBlur() { },
    // oniptfcs() {
    //   console.log("组件原生获得焦点");
    // },
    // updateMsg() {
    //   this.msg = "修改后的信息"
    // }
  },
};
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
