<script>
    import Imc from "./Imc.svelte";
    import Form from "$lib/Form.svelte";

	const name = "Manu";

</script>
<main>
    <h1>Calculateur IMC</h1>
    <p>Bonjour {name} ! Calculez votre IMC (Indice de Masse Corporelle)</p>
    <Form />
    <Imc />
</main>