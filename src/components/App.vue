<template>
    <div id="app">
    <button class="btn btn-primary" @click="initJokes">Add Ten Random Jokes</button>
        <h3>Got Jokes ?</h3>
        <div class="">
            {{$store.state}}
        </div>
         
    </div>
</template>

<script>
import { mapActions } from "vuex";
export default {
  methods: mapActions(["initJokes"])
};
</script>