<template>
    <div id="app">
        <img src="../../assets/logo.png">
        <div class="hello">
            <h1>{{ msg }}</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="test1.html">page1</a></li>
                <li><a href="test2.html">page2</a></li>
                <li><a href="test3.html">page3</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'app',
        data() {
            return {
                msg: 'Vue multi-page 1',
            };
        },
    };
</script>

<style>
    body{background: #fff4c2}
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
    h1, h2 {
        font-weight: normal;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #42b983;
    }
</style>
