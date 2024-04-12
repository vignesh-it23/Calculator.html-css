<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Calculator</title>
    <link rel="icon" href="./icon.jpeg">
    <style>
        .body {
            width: 275px;
            border-radius: 3rem;
            margin: auto;
            min-height: 500px;
            background:#727B86;
        }
        .front {
            padding: 1.5rem;
        }

        #top {
            font-size: 1.3rem;
            text-align: right;
            color: #727B86;
            padding-bottom: .4rem;
        }

        #option {
            font-size: 2rem;
            text-align: right;
            color: #fff;
        }
        .row {
            display: table;
        }

        .row button {
            display: table-cell;
            width: 25%;
            border-radius: 3rem;
            background: #425062;
            color:blanchedalmond;
            height: 65px;
            font-size: 1.3rem;
            border: none;
            border-color: #3C4857;
            border-width: 1px 1px 0px 0;
            border-style: solid;
        }

        .row button.ac {
            color: #ff7665;
        }

        .row button.ty {
            color: #ffbc56;
        }
        .row button:nth-child(4n) {
            border-right: none;
        }

        .row button:active {
            position: relative;
            top: 1px;
        }

        .row button:hover {
            background: #3e4b5c;
        }
    </style>
</head>
<body>
    <div class="body">
        <div class="front">
            <div id="top">20 + 17 </div>
            <div id="option">37</div>
        </div>
        <div class="row">
            <button class="ac">Ac</button>
            <button class="ty">+</button>
            <button class="ty">%</button>
            <button class="ty">÷</button>
            <button>7</button>
            <button>8</button>
            <button>9</button>
            <button class="ty">×</button>
            <button>4</button>
            <button>5</button>
            <button>6</button>
            <button class="ty">−</button>
            <button>1</button>
            <button>2</button>
            <button>3</button>
            <button class="ty">+</button>
            <button>0</button>
            <button>.</button>
            <button>X</button>
            <button class="ty">=</button>
        </div>
    </div>
</body>
</html>

