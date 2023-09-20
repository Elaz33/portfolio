<div class="outer-box">
    <h1 class="title">HI I AM ELAZAR</h1>
    <h1 class="title">I AM A WEB DEVELOPER</h1>
    <h1 class="title">IN OHIO</h1>
    <h3 class="title">
        The definition of genius is taking the complex and making it simple
    </h3>

    <img class="pic" src="img/Bak (36) (1).JPEG" alt="" />
    <br class="line" />
    <p class="about">
        I have completed a course from PCS in Lakewood New Jersey
    </p>
    <p />
    <p class="about">for Software Development and I am currently interning</p>
    <p class="about">and working within the framework of Svelte</p>
    <div class="icon-row">
        <img
            class="icon"
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/svelte/svelte-original-wordmark.svg"
        />
        <img class="icon" src="img/javascript-39402.png" />

        <img class="icon" src="img/imageedit_5_8327855680.png" />

        <img
            class="icon"
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg"
        />

        <img
            class="icon"
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg"
        />

        <img
            class="icon"
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg"
        />

        <img
            class="icon"
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg"
        />

        <img
            class="icon git"
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg"
        />
    </div>
    <!-- <i class="devicon-github-original-wordmark"></i> -->
</div>

<style>
    :global(body) {
        background-color: rgb(75, 66, 66);
    }
    .outer-box {
        height: 10000px;
        overflow: hidden;
    }
    .title {
        z-index: 10;
        position: relative;
        left: 20%;
        top: 2.5%;
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
        color: rgb(70, 134, 134);
    }
    .about {
        position: relative;
        top: -2.5%;
        left: 20%;
        font-size: larger;
        color: rgb(43, 79, 43);
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
    }

    .pic {
        position: relative;
        top: 0.5%;
        width: 400px;
        left: 60%;
        border-radius: 8px;
        background-color: rgb(135, 117, 117);
    }
    .icon-row {
        display: flex;
        position: relative;
        top: -1.4%;
        left: 18%;
        flex-direction: row;
        gap: 20px;
    }
    .icon {
        width: 60px;
        left: 16%;
        top: -1%;
    }
    .git{
      
    }
    .line {
        position: relative;
    }

    @media (max-width: 1525px) {
        .pic {
            right: 0;
        }
        .outer-box {
            overflow: visible;
        }
        .title {
            top: 5.5%;
            color: whitesmoke;
        }
        .about {
            top: 0.6%;
        }
        .icon-row {
            top: 0.9%;
        }
        .icon {
            top: 0.7%;
        }
    }

    @media (max-width: 400px) {
        .pic {
            left: 5%;
        }

        .title {
            top: 5.5%;
            color: whitesmoke;
        }
        .about {
            top: 0.5%;
        }
        .icon-row {
            top: 0.8%;
        }
        .icon {
            top: 0.7%;
            width: 38px;
        }
    }
</style>
