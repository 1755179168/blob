<template>
  <Avatar url="https://img2.baidu.com/it/u=1823002002,334531521&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=751" />
  <div>{{fullName}}</div>
  <Icon type="wran" />
  <Icon type="zhenque" />
  <Pager @changePage="handlerChangePage" />
</template>

<script>
import Avatar from "@/components/avatar";
import Icon from "@/components/icon";
import Pager from "@/components/page";
export default {
  components: {
    Avatar,
    Pager,
  },
  computed: {
    fullName: {
      get() {
        return 1;
      },
      set(val) {
        return val;
      },
    },
  },
};
</script>

<style scoped>
.icon-container {
  font-size: 100px;
}
</style>