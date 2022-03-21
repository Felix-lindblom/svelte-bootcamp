<script>
    const grace = {
        title: 'Grace Hopper',
        img: 'https://upload.wikimedia.org/wikipedia/commons/5/55/Grace_Hopper.jpg',
        subTitle: 'Coolaste kodaren i marinen',
        content: 'Grace Hopper var en amerikansk dator-pionjär och sjöofficer (flottiljamiral). Hon var bland annat med och utvecklade Harvard Mark I och skapade den första kompilatorn. Hon populariserade användningen av programmeringsspråk som var oberoende av maskinen, något som ledde till utvecklingen av COBOL, ett högnivå programmeringsspråk som fortfarande används idag.'
    }
    
    let title = grace.title
    let image = grace.img
    let subText = grace.subTitle
    let mainText = grace.content

</script>
<main>
    <body class="realbody">
        <h1> {title} </h1>
        <img src="{image}" alt="Bild på Grace hopper">
        <aside> <h3> {subText} </h3> </aside>
        <main> {mainText} </main>        
    </body>

</main>
<style>
    *{
        margin: 0px;
        padding: 0px;
    }
    .realbody{
        padding: 0%;
        margin: 0px;
        height: 100vh;
        width: 100vw;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        background-color: grey;
    }
    img{
        height: 10rem;
        width: auto;
    }
    aside{
        display: flex;
        justify-content: flex-start;
    }
    h3{
        color: bisque;
    }
    main{
        width: 60vw;
    }
</style>