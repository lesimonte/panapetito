<script setup>
import { useRoute } from 'vue-router';

const ruta =useRoute()
const categorias = ruta.params.categorias;
</script>