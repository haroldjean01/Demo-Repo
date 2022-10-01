# Demo-Repo
body {
    margin: 0;
    font-family: Corbel, 'Lucida Grande', 'Lucida Sans Unicode', 'Lucida Sans', 'DejaVu Sans',
        'Bitstream Vera Sans', 'Liberation Sans', Verdana, 'Verdana Ref', sans-serif;
    background: rgb(224, 234, 247);
    display: grid;
    grid-template-rows: auto 1fr;
}

header {
    position: sticky;
    top: 0;
    padding: 20px;
    height: 60px;

    display: flex;
    align-items: center;
    gap: 10px;

    background-color: rgb(254, 251, 245);
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
}

header .logo {
    height: 100%;
}

main {
    padding: 20px;
}

input {
    height: 29px;
}

button {
    height: 35px;
}

.name-tag {
    margin-top: 20px;
    width: 400px;
    height: 255px;
    background: rgb(244, 86, 86);
    color: white;
    text-align: center;
}

h2 {
    margin: 0;
    font-size: 4em;
    text-transform: uppercase;
    padding: 10px;
}

.intro {
    margin: 0;
}

.name-display {
    margin: 0;
    margin-top: 15px;
    padding: 15px;
    background: white;
    color: black;
    font-family: 'Passions Conflict', cursive;
    font-size: 3em;
}