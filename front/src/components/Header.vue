<template>
    <div class="container">
        <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed&display=swap" rel="stylesheet">
        <nav class="nav-header">
        <ul>
            <li><a href="#">Mariage</a></li>
            <li><a href="#">Portrait</a></li>
            <li><a href="#">Tarif</a></li>
            <li><router-link to="/about">A propos</router-link></li>
            <li><a href="#">Me contacter</a></li>
        </ul>
        </nav>
    </div>
</template>

<style>
nav{
    display: flex;
    justify-content: center;
}

.nav-header a {
    margin-left: 20px;
    font-size:1.4rem;
    font-family: 'Roboto Condensed', sans-serif;
}

ul{
    display: flex;
    list-style-type: none;
}

a:link{
    text-decoration: none;

}
</style>