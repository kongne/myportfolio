<template>

    <!-- Header -->
    <Heading tempID="projects" heading="Projects" headingNum="02"></Heading>


    <!-- Place Special Tiles Here </ -->
    
    <Tile 
        special="true"
        title="The North Star Theme" 
        description="A cyan-ish dark theme extension for Visual Studio Code." 
        :languages="['VS Code', 'JSON', 'Coolors']" 
        gitLink="https://github.com/AkosoCodes/north-star-theme" 
        exLink="https://marketplace.visualstudio.com/items?itemName=AkosoCodes.north-star-theme" 
        imageURL="/images/theme1.png"
    ></Tile>


    <Tile 
        flip="true"
        special="true"
        title="Travel Agency Web App" 
        description="A fully functioning frontend side of the travel agency web application, built using the MEAN tech stack." 
        :languages="['Angular', 'TypeScript', 'NodeJS', 'CSS']" 
        gitLink="https://github.com/AkosoCodes/Travel-Agency-Frontend" 
        exLink="" 
        imageURL="/images/frontend.png"
    ></Tile>

    <Tile 
        special="true"
        title="Travel Agency API (Backend)" 
        description="A fully functioning backend side of the travel agency web application. It was built in JavaScript, and uses a non-relational MongoDB database." 
        :languages="['JavaScript (ES6)', 'NodeJS', 'ExpressJS', 'MongoDB', 'Mongoose']" 
        gitLink="https://github.com/AkosoCodes/Travel-Agency-Frontend" 
        exLink="" 
        imageURL="images/backend.png"
    ></Tile>

    <Tile
        flip="true"
        title="Connect Four Game" 
        description="The Connect 4 game is a classic strategy game in which players alternately place pieces on a grid. It is terminal based and built using C programming language. " 
        :languages="['C', 'Terminal']" 
        gitLink="https://github.com/AkosoCodes/Travel-Agency-Frontend" 
        exLink="" 
        imageURL="images/connectfour.png"
    ></Tile>

    <!-- /> Place Normal Tiles Here -->


    <!-- Other Projects -->
    <div class="w-2/3 h-auto rounded-lg bg-accent mx-auto mb-50px z-0">

        <h1 class="text-main text-center text-[25px]">The rest of my projects can be found on <a class="hover:text-main text-accent" href="https://github.com/kongne" target="_blank">my GitHub Profile.</a></h1>

    </div>

</template>


<script>

    import Heading from '../heading.vue';
    import Tile from '../tile.vue';

    export default{
        name: "projects",
        components: { 
            Heading,
            Tile
        },

    }

</script>

