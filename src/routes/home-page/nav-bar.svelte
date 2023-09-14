<div class="header">
    <div class="nav-bar">
        <div class="header-block">CAR PROJECT</div>
        <div class="header-block">PROJECT B</div>
        <div class="header-block">PROJECT C</div>
        <div class="header-block">PROJECT D</div>
    </div>
    <div class="name-block">
        <pre class="my-name">ELAZAR ROSENFELD</pre>
    </div>
</div>

<style>
    .header {
        height: 50px;
        /* border: solid green; */
    }
    .nav-bar {
        position: relative;
        display: flex;
        height: 50px;
        width: 400px;
        left: 50%;
        /* justify-content: space-evenly; */
        gap: 30px;
        /* border: solid red; */
        color: white;
        font-size: large;
    }
    .name-block {
        position: relative;
        height: 50px;
        width: 225px;
        left: 20%;
        top: -60px;
        font-size: xx-large;
        font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
            "Lucida Sans", Arial, sans-serif;

        color: white;
        /* border: solid green; */
    }
    .my-name {
        position: relative;
        bottom: 10px;
    }
    .header-block {
        position: relative;
        top: 25px;
        font-size: small;
        font-family: Georgia, "Times New Roman", Times, serif;
    }
    @media (min-width: 950px) {
        .nav-bar {
            left: 50%;
        }
        .name-block {
            left: 20%;
        }
    }

    @media (max-width: 900px) {
        .nav-bar {
            left: 50%;
        }
        .name-block {
            left: 15%;
        }
    }

    @media (max-width: 750px) {
        .nav-bar {
            left: 55%;
            top: 50px;
        }
        .name-block {
            left: 17%;
        }
    }

    @media (max-width: 750px) {
        .nav-bar {
            left: 55%;
            top: 50px;
        }
        .name-block {
            left: 17%;
        }
    }

    @media (max-width: 400px) {
        .nav-bar {
            left: 8%;
            top: 40px;
        }
        .name-block {
            left: 30%;
        }
    }
</style>
