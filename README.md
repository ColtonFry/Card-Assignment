<!DOCTYPE html>
<center>
    <head>
        <h1>Card Assignment</h1>
        <h2>Question 1</h2>
    </head>
    <style>
        .label:after {
            content: 'What is 2 + 2 = ?';
        }
        .label:hover:after {
            content: 'The Answer is 4.';
        }
    </style>
    <body>
        <p>
            <span class="label"></span>
        </p>
    </body>
<br>
 
<h2> Question 2</h2>
<style>
    .tooltip {
        position: relative;
        display: inline-block;
        border-bottom: 1px dotted black;
    }

    .tooltip .tooltiptext {
        visibility: hidden;
        width: 120px;
        background-color: black;
        color: #fff;
        text-align: center;
        border-radius: 6px;
        padding: 5px 0;

        /* Position the tooltip */
        position: absolute;
        z-index: 1;
    }

    .tooltip:hover .tooltiptext {
        visibility: visible;
    }
</style>
<body style="text-align:center;">
 <p>
        In what month is Tax Day?
    </p>

    <div class="tooltip">
        Hover HERE for answer
        <span class="tooltiptext">April</span>
    </div>
<br>
<h2> Question 3</h2>
 <style>
        .tooltip {
            position: relative;
            display: inline-block;
            border-bottom: 1px dotted black;
        }

        .tooltip .tooltiptext {
            visibility: hidden;
            width: 120px;
            background-color: black;
            color: #fff;
            text-align: center;
            border-radius: 6px;
            padding: 5px 0;

            /* Position the tooltip */
            position: absolute;
            z-index: 1;
        }

        .tooltip:hover .tooltiptext {
            visibility: visible;
        }
    </style>
    <body style="text-align:center;">
        <p>
            Name this coding word St*l*
        </p>

        <div class="tooltip">
            Hover HERE for answer
            <span class="tooltiptext">STYLE</span>
        </div>
    
