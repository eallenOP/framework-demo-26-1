<script>
    import Card from "$lib/components/Card.svelte";
    import bill from "$lib/images/bill.jpeg";

    let person = {
        name: "Bill Murray",
        image: bill
    }
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
 
<Card name={"Elise"} />
<Card {...person} />
<Card name={"Buddy"} />
<Card name={"Fundamentals of Web Development"} />
<Card name={"ID512"} image={"https://plus.unsplash.com/premium_photo-1666777247416-ee7a95235559?q=80&w=687&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"} />
<Card />
<Card />
<Card />
<Card />
<Card />
<Card />