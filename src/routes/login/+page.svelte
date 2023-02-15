<script>
	import { Container } from "postcss";
    import imagotipo from '$lib/assets/imagotipo.png';
</script>

<div class="pt-28 flex justify-center">
    <div class="w-96 h-96 bg-gradient-to-b from-white to-blue-100 rounded-lg">
        <img alt="The project imagotipo" src={imagotipo} />
    
        <div>
            <p>-Bienvenido/a-</p>
            <p>Se requiere una validadcion con e.firma:</p>
        </div>
        
        <button>Iniciar sesion</button>
    </div>
</div>




<style lang="postcss">
    :global(html) {
      background-color: theme(colors.gray.100);
    }
</style>