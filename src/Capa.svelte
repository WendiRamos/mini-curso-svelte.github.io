<script>

import CaixaDeIcones from "./CaixaDeIcones.svelte";

</script>
<div class="fundo">
    <div class="centro">
        <img src="./img/wendi.jpg" alt="Foto de Wendi" class="foto">
        <h1 class="titulo">Wendi Ramos</h1>
        <h2 class="descricao">Software Developer</h2>
        <CaixaDeIcones />
    </div>
</div>

<style>
    .fundo{
        width: 100%;
        min-height: 100vh;
        background-color: #810845;
    }

    .centro{
        color: white;
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    .foto{
        border-radius: 50%;
        width: 250px;
    }

    .titulo{
        font-size: 40px;
    }

    .descricao{
        font-size: 25px;
    }


</style>