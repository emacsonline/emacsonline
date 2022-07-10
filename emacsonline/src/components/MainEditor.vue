<template>
    <div id="editor" style="width: 1280px; height: 1024px"></div>
</template>

<script>
import loader from "@monaco-editor/loader";

export default {
 name: "MainEditor",
 async mounted() {

   loader.init().then((monaco) => {

     monaco.editor.create(document.getElementById("editor"));
    
   });
  
 },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
