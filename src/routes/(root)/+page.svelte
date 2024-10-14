<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p> -->
<script>
    let title = "Ninja gaming guides";

    const updateTitle = () => {
        title = "Weedma gaming";
    };
</script>


<div class="index">
    <h2>{title}</h2>
    <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eligendi quo
        dicta animi ducimus dolores, voluptate numquam nihil debitis sint
        ratione, doloribus ad. Itaque, tenetur. Iste placeat corrupti esse
        eligendi delectus? Dolore omnis enim animi! Minus, eaque aspernatur
        delectus ipsum hic cupiditate similique iure. Velit cumque repellat ad
        earum eaque, nam iure sint tempore perferendis debitis beatae sequi
        labore voluptas odit. Tempore maiores, laudantium, ipsa sunt tempora
        esse quae deleniti sint laborum, nostrum dolore possimus totam
        praesentium cupiditate. Est, aperiam necessitatibus nam minus excepturi
        laboriosam doloribus, cupiditate ratione iste laudantium illo. Eligendi
        hic velit iste numquam voluptatum eius provident, cupiditate vitae
        labore consectetur suscipit neque magnam doloremque voluptatibus
        quibusdam sint quas laudantium aut eos laborum! Sint laborum possimus
        officia alias assumenda. Voluptate ut ipsum molestiae sint ipsa
        repudiandae vero, nam nemo laboriosam alias quasi sapiente at!
        Quibusdam, molestias minus quo fugit impedit animi placeat quia natus
        fugiat, consequuntur expedita dignissimos dolor.
    </p>

    <a href="/guides">Guides</a>
    <a href="/about">About</a>
    <button on:click={updateTitle}> Change title</button>
    <input type="text" bind:value={title} />
</div>

<style>
    .index {
        text-align: center;
        display: block;
        margin: 20px auto;
    }
</style>
