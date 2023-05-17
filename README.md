<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Week 11</title>
</head>
<style>
    .container {
        display: grid;
        grid-template-columns: 0.6fr 1.2fr 1.2fr 1fr;
        grid-template-rows: 0.5fr 2fr 0.5fr;
        gap: 0px 0px;
        grid-auto-flow: row;
        grid-template-areas:
            "grid-header grid-header grid-header grid-header"
            "grid-nav grid-text grid-svg grid-svg"
            "grid-nav grid-text grid-controls grid-controls";
    }

    .grid-header {
        grid-area: grid-header;
    }

    .grid-nav {
        grid-area: grid-nav;
    }

    .grid-text {
        grid-area: grid-text;
    }

    .grid-svg {
        grid-area: grid-svg;
    }

    .grid-controls {
        grid-area: grid-controls;
    }
</style>

<body>

    <div class="container">
        <div class="grid-header"></div>
        <div class="grid-nav"></div>
        <div class="grid-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sollicitudin, nibh vitae
            iaculis malesuada, ipsum sapien eleifend orci, ac vulputate massa erat ut nulla. Nunc ultricies aliquam
            neque, at auctor neque viverra in. Nullam placerat, ante et scelerisque viverra, ex leo dignissim diam, sit
            amet scelerisque massa turpis et arcu. Pellentesque in nibh quis odio scelerisque malesuada id a lacus.
            Nullam pretium, nisl auctor blandit sagittis, neque dolor pulvinar felis, et maximus tellus leo eget odio.
            Donec iaculis tellus sed dignissim lacinia. Integer vel augue volutpat, mollis nulla at, scelerisque massa.
        </div>
        <div class="grid-svg"></div>
        <div class="grid-controls"><input type="button" value="Click me!"></div>
    </div>
    <img src="https://placekitten.com/400/600"
    alt="bio-page-image">
    <svg viewBox="0 0 500 300" xmIns="http://www.w3.org/2000/svg">
        <circle cx="0%" cy="0%" r="50"/>
        <circle cx="100%" cy="0%" r="50" />
        <circle cx="100%" cy="100%" r="50"/>
        <circle cx="0%" cy="100%" r="50" />
    </svg>
   
    

</body>

</html>
