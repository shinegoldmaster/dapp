<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
body {
    font-family: Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
}
a {
    color: #42b983;
    text-decoration: none;
    cursor: pointer;
}
a:hover {
    color: #70caa2;
}
h1 {
    font-size: 1.6rem;
    font-weight: normal;
    margin: 0.1em 0 0.5em 0;
}

h2 {
    color: #556;
    font-size: 1.1rem;
    font-weight: normal;
    margin: 1.5em 0;
}

h3 {
    color: #246648;
    font-size: 1rem;
    margin: 0.5em 0;
}

article {
    max-width: 640px;
}

article h1 {
    color: #4A90E2;
}

article h2 {
    font-weight: bold;
    margin-bottom: 0.5em;
}

header, footer, .container {
    width: 1000px;
    margin: 1em auto;
}
header h2 {
    margin-top: 0;
}

footer {
    margin-top: 2em;
    display: table;
    table-layout: fixed;
}
footer ul {
    display: table-cell;
    width: 100%;
    list-style: none;
    padding: 0 1em;
    vertical-align: top;
}
footer li {
    margin-bottom: 0.5em;
}
.adGrid {
    margin: 0 auto;
    position: relative;
    width: 1000px;
    height: 1000px;
    background: #ddd;
}
article ul {
    list-style: none;
}
article li {
    margin-bottom: 0.5em;
}

#floating-chat {
    width: 2.5em;
    height: 2.5em;
    fill: #4a90e2;
    position: fixed;
    bottom: 10px;
    right: 10px;
}
</style>
