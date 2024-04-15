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
<br>
        <h2>Question 4</h2>
    </head>

    
   <center>
       <style>
        .label:after {
            content: 'Name the Two Transitions we learned about in this lesson';
        }
        .label:hover:after {
            content: 'DELAY & TIMING-FUNCTION';
        }
    </style>
    <body>
        <p>
            <span class="label"></span>
        </p>
    </body>
            Hover Over Question for answers
            <span class="tooltiptext">STYLE</span>
        </div>

        <br>
        <h2>Question 5</h2>
    </head>

    
   <center>
       <style>
        .label:after {
            content: 'What is Keyframe-selector?';
        }
        .label:hover:after {
            content: 'Set the directions for the animation';
        }
    </style>
    <body>
        <p>
            <span class="label"></span>
        </p>
    </body>
            Hover Over Question for answers
            <span class="tooltiptext">STYLE</span>
        </div>
    
<br>
        <h2>Question 6</h2>
        <center>
       <style>
        .label:after {
            content: 'What is Animation Properties??';
        }
        .label:hover:after {
            content: 'Used to tell the target element it is going to perform the animation';
        }
    </style>
    <body>
        <p>
            <span class="label"></span>
        </p>
    </body>
            Hover Over Question for answers
            <span class="tooltiptext">STYLE</span>
        </div>

    <style>
<br>
        
        <style>
  @keyframes anim2 {
    0% {
      transform:rotate(0deg);
    }
    50% {
      transform:rotate(90deg);
      color:#333333;
    }
    100% {
      transform:rotate(90deg);
      color:#BBBBBB;
    }
  }

  div {
    width: 150px; 
    height: 75px; 
    border: 2px solid #333; 
    margin-top: 40px;
    animation-name: anim2;
    animation-duration: 3s;
    animation-iteration-count: infinite;
  }
</style>

<div>Question 7 What controls the number of steps and when they happen?</div>
<style>
  @keyframes anim1 {
    0% {
      transform:rotate(0deg);
    }
    50% {
      transform:rotate(90deg);
      color:#333333;
    }
    100% {
      color:#BBBBBB;
    }
  }

  div {
    width: 150px; 
    height: 75px; 
    border: 2px solid #333; 
    margin-top: 40px;
    animation-name: anim1;
    animation-duration: 3s;
    animation-iteration-count: infinite;
  }
</style>

<div>ANSWER: Animations</div>

<br>
        <h2>Question 8</h2>
    </head>

    
   <center>
       <style>
        .label:after {
            content: 'Name the Two Transitions we learned about in this lesson';
        }
  <br>
           <center>
           A few seconds before animation starts is called what?
           <style>
  @keyframes timeIt {
    from {
      transform: rotate(0deg);
      left: 10px;
    }
    to {
      transform: rotate(180deg);
      left: 500px;
    }
  }
  section {
     position: relative;
  }
  section div {
    width: 75px;
    padding: 10px;
    position: absolute;
    background-color: lightpink;
    border: 2px solid purple;
    border-radius: 10px;
    font-size: 1.2em;
    font-weight: bold;
    text-align: center;
    animation-name: timeIt;
    animation-duration: 2s;
    animation-delay: 2s;
    animation-timing-function: ease-in;
    animation-iteration-count: infinite;
  }
</style>

<section>
  <div>delay & timing</div>
</section>
