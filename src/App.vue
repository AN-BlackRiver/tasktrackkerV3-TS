<template>

  <AppHeader/>

  <AppFilers/>

  <main class="app-main">
    <AppTodoList/>

    <AppAddTodo/>
  </main>

  <AppFooter/>
</template>

<script setup lang="ts">

import AppHeader from "@/components/AppHeader.vue";
import AppFilers from "@/components/AppFilers.vue";
import AppTodoList from "@/components/AppTodoList.vue";
import AppAddTodo from "@/components/AppAddTodo.vue";
import AppFooter from "@/components/AppFooter.vue";

</script>