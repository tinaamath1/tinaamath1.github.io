# tinaamath1.github.io
layout: page
title: "How are policies for small scale fisheries measured?"
permalink: /qualproject

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Goal 14.b</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  
<div class="introtext">
  <h1>How are policies for small scale fisheries measured?</h1>
  <div class="infobold">
  <p>Small scale fisheries are critical to livelihood and food security throughout the world. Yet, they are often overlooked by policymakers. </p>
  </div>
  <div class="info">
  <p>UN SDG Goal 14.b measures access to resources and markets for small-scale fisheries based on a country's response to three questions given on a questionaire by the FAO'S Code of Conduct for Responsible Fisheries. The data are collected in order to measure whether a country has legal framework or policies that protect small scale fisheries which provide over half of fish catch in developing countries. The data tells us that each country has a degree of implementation score from 1-5, otherwise very low to very high. This visualization is a tool to show how those qualitiative answers are quanitified. </p>
  <p>Hover and click on the variables below to learn how the UN measures access to resources for a country. </p>
</div>
<div class="infolight">
  <p>This is fictious data to depict the weighting of qualitative data. The bar chart below shows a country's potential overall degree of implementation score.</p>
  <p>Each variable has a unique weighting based on how important this variable is to aiding small scale fisheries.</p>
</div>
</div>


<!-- 
  <figure>
    <figcaption>
      Degree of implementation of framework
    </figcaption> 
    <figcaption class="description">
      The overall score is the sum of variable 1, 2, and 3. Each band interval represents degree of implementation (low, medium, high, etc). In order to show these weightings, I've used fictious data under "Oceania" for overall score, variable 1, 2, and 3.  
    </figcaption>
    <div class="btn-group">
      <button class="overall">OVERALL</button>
      <button class="var_1">VARIABLE 1</button>
      <button class="var_2">VARIABLE 2</button>
      <button class="var_3">VARIABLE 3</button>
    </div>
     <svg width="100" height="100" class="chart">
    </svg> 
  </figure>  -->

 
  <div class="static" style="width:50%; height: 100%; float: left;"> 
    <!-- <section class="bar"> -->
  <svg class="bar" style= "height: 1500px; width:650px">


    <g class="labels x-labels">
    <text x="145" y="250">0</text>
    <text x="242" y="250">.2</text>
    <text x="342" y="250">.4</text>
    <text x="442" y="250">.6</text>
    <text x="540" y="250">.8</text>
    <text x="645" y="250">1</text>
    </g>

    <g class="bands labels">
      <text x="155" y="88">Very Low (1)</text>
      <text x="255" y="88">Low (2)</text>
      <text x="353" y="88">Medium (3)</text>
      <text x="455" y="88">High (4)</text>
      <text x="555" y="88">Very High (5)</text>
    </g>

    <g class= "scale label">
      <text x="10" y="280">Degree of</text>
      <text x="10" y="300">Implementation</text>
      <text x="10" y="320">Score</text>
    </g>

    <g class="scale_lines">
      <line x1="150" y1="315" x2="650" y2="315" stroke="black"></line>
      <text x="155" y="305">Very Low (1)</text>
      <line x1="150" y1="280" x2="150" y2="315" stroke="gray"></line>
      <text x="270" y="305">Low (2)</text>
      <line x1="250" y1="280" x2="250" y2="315" stroke="gray"></line>
      <text x="360" y="305">Medium (3)</text>
      <line x1="350" y1="280" x2="350" y2="315" stroke="gray"></line>
      <text x="470" y="305">High (4)</text>
      <line x1="450" y1="280" x2="450" y2="315" stroke="gray"></line>
      <text x="555" y="305">Very High (5)</text>
      <line x1="550" y1="280" x2="550" y2="315" stroke="gray"></line>
      <line x1="650" y1="280" x2="650" y2="315" stroke="gray"></line>
    </g>

    <line x1="150" y1="75" x2="150" y2="225" stroke="lightgray"></line>
    <line x1="250" y1="75" x2="250" y2="225" stroke="lightgray"></line>
    <line x1="350" y1="75" x2="350" y2="225" stroke="lightgray"></line>
    <line x1="450" y1="75" x2="450" y2="225" stroke="lightgray"></line>
    <line x1="550" y1="75" x2="550" y2="225" stroke="lightgray"></line>
    <line x1="650" y1="75" x2="650" y2="225" stroke="lightgray"></line>  
    <rect  class="var1bar" width="100" height="20" x= "150" y= "150"></rect>
    <!-- <text class="variable1hover" x="170" y="180">Variable 1</text> -->
    <rect class="var2bar"  width="75.5" height="20" x= "250" y="150"></rect>
    <rect class="var3bar"  width="150" height="20" x="325" y="150"></rect> 


  </svg>
  </div>

  
    <!-- <div class="allbuttons">
   <div class="button">
  <img id="image" src="" /> 
  
   
  <button type="button"
    onclick="show()" id="btnID">
  </button>
   
  <script>
    function show() {
   
    /* Get image and change value
    of src attribute */
    let image = document.getElementById("image");
    
    image.src = "variable1-07.png"
    
    document.getElementById("btnID")
    .style.display="none";
    }
  </script>
  </div>

 <div class="button"> 
    <img id="image" src="" />
    
     
    <button type="button"
      onclick="show()" id="btnID">
    </button>
     
    <script>
      function show() {
     
      /* Get image and change value
      of src attribute */
      let image = document.getElementById("image");
      
      image.src = "variable2-08.png"
      
      document.getElementById("btnID")
      .style.display="none";
      }
    </script>
    </div> -->

    <!--
   <div class="button">
      <img id="image" src="" />
      
       
      <button type="button"
        onclick="show()" id="btnID">
      </button>
       
      <script>
        function show() {
       
        /* Get image and change value
        of src attribute */
        let image = document.getElementById("image");
        
        image.src = "variable3-09.png"
        
        document.getElementById("btnID")
        .style.display="none";
        }
      </script>
      </div>
      </div>  -->
     







<div class="description" style="margin-left:50%; height:300px;">
  <p>Target 14.b focuses on access to resources and markets for small-scale fisheries.
  In order to guarantee secure access, an enabling environment is necesary which recognizes and protects small-scale fisheries rights.
  Scroll to learn how a country receives its degree of implementaion score.</p>
</div>



<div class="interactive_1">
    <!-- <section class="updated_variable_1">  -->
    <svg class="variable_1"  height="300px" width="700px" > 

    <g class="var1descrip">
    <text x="100" y="50">Variable 1: Are there any laws, regulations, policies, plans or strategies the specifically target or address the </text>
    <text x="100" y="65">small-scale fisheries sector?</text>
    </g>

    <g>
    <rect class="yes1" x="100" y="180" width="25" height="25"></rect>
    <text class="yestext" x="140" y="198">Yes (0.1)</text> 
    <rect class="no" x="100" y="220" width="25" height="25"></rect>
    <text class="yestext" x="140" y="240">No or Unknown (0)</text>
    </g>

    <g>
    <text class="sub-variables" x="300" y="110">Sub-variables</text> 
    <text class= "sub-variables" x="400" y="110">Law</text>
    <text class= "sub-variables" x="400" y="160">Regulation</text>
    <text class= "sub-variables" x="400" y="210">Policy</text>
    <text class= "sub-variables" x="400" y="260">Plan/Strategy</text>
    <text class= "sub-variables" x="400" y="310">Other</text>
    </g>

     <g>
      <text class= "var1descrip" x="500" y="110">1.1</text>
      <text class= "var1descrip" x="500" y="160">1.2</text>
      <text class= "var1descrip" x="500" y="210">1.3</text>
      <text class= "var1descrip" x="500" y="260">1.4</text>
      <text class= "var1descrip" x="500" y="310">1.5</text>
    </g>  

    <g>
      <rect class="yes1" x="600" y="95" width="25" height="25"></rect>
      <rect class="yes1" x="600" y="145" width="25" height="25"></rect>
      <rect class="no" x="600" y="195" width="25" height="25"></rect>
      <rect class="no" x="600" y="245" width="25" height="25"></rect>
      <rect class="no" x="600" y="300" width="25" height="25"></rect>
    </g>

 
    </svg>
    </section>
</div> 



 <div class="interactive_2">
      <section class="updated_variable_2"> 
      <svg class="variable_2"  height="600px" width="700px"> 
      
      <g class="var2descrip">
      <text x="100" y="50">Variable 2: Are there any ongoing specific initiatives to implement the small scale fisheries guidelines?</text>
      
      </g>
      
      <g>
      <rect class="yes2" x="100" y="180" width="25" height="25"></rect>
      <text class="yestext" x="140" y="198">Yes (0.03)</text> 
      <rect class="no" x="100" y="220" width="25" height="25"></rect>
      <text class="yestext" x="140" y="240">No or Unknown (0)</text>
      </g>
      
      <g>
      <text class="sub-variables" x="300" y="110">Sub-variables</text>
      <text class= "sub-variables" x="400" y="110">Improving Security</text>
      <text class= "sub-variables" x="400" y="160">Improving Information</text>
      <text class= "sub-variables" x="400" y="210">Promoting Development</text>
      <text class= "sub-variables" x="400" y="260">Enhancing Value Chain</text>
      <text class= "sub-variables" x="400" y="310">Enhancing Gender Equality</text>
      <text class= "sub-variables" x="400" y="360">Enhancing Monitoring</text>
      <text class= "sub-variables" x="400" y="410">Strengthening Institutions</text>
      <text class= "sub-variables" x="400" y="460">Supporting Small Scale Fisheries</text>
      <text class= "sub-variables" x="400" y="510">Improving Capacity Development</text>
      <text class= "sub-variables" x="400" y="560">Addressing Diaster Risk</text>
      </g> 
      
      <g>
        <rect class="yes2" x="600" y="95" width="25" height="25"></rect>
        <rect class="yes2" x="600" y="145" width="25" height="25"></rect>
        <rect class="yes2" x="600" y="195" width="25" height="25"></rect>
        <rect class="yes2" x="600" y="245" width="25" height="25"></rect>
        <rect class="yes2" x="600" y="295" width="25" height="25"></rect>
        <rect class="no" x="600" y="345" width="25" height="25"></rect>
        <rect class="no" x="600" y="395" width="25" height="25"></rect>
        <rect class="no" x="600" y="445" width="25" height="25"></rect>
        <rect class="no" x="600" y="495" width="25" height="25"></rect>
        <rect class="no" x="600" y="545" width="25" height="25"></rect>
      </g>
      
       
      </svg>
      </section>
</div>



<div class="interactive_3">
<section class="updated_variable_3">
<svg height="500px" width="700px">

<g class="var3descrip">
<text x="100" y="50"> Variable 3: Does your country have an advisory/consultative body to Ministry/Department of Fisheries in which</text>
<text x="100" y="65"> fishers/fish workers can participate and contribute to decision-making processes?</text>
</g>

<g>
<rect class="yes3" x="100" y="180" width="25" height="25"></rect>
<text class="yestext" x="140" y="198">Yes (0.3)</text> 
<rect class="no" x="100" y="220" width="25" height="25"></rect>
<text class="yestext" x="140" y="240">No or Unknown (0)</text>
</g>

<g>
<text class="sub-variables" x="300" y="110">Sub-variables</text>
<text class= "sub-variables" x="400" y="110">Advisory Body</text>

</g>


<g>
<rect class="yes3" x="600" y="95" width="25" height="25"></rect>
</g>
</svg>
</section>
</div>

</section> 

</div>



<!-- <section class="visualization">
      <p>Degree of application</p>
      <svg width="4500px" height="50px" >
        <g id="dots"></g>
      </svg>
      
    </div>
  </section>   -->


  



   <script src="https://d3js.org/d3.v7.min.js"></script>
   <script src="./interactive.js"></script>
  <script src="./main.js"></script> 

  
</body>

</html>
