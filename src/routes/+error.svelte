<script>
    import { page } from "$app/stores";
    import "../styles/global.css";

    console.log($page)
</script>

<main>
    <h1>Ooops {$page.status}</h1>
    <p>{$page.error?.message}</p>
    <a href="/guides">View all guides</a>
</main>

<style>
    main {
        max-width: 960px;
        margin: 20px auto;
    }
</style>
