# BodyPump
Project to extract choregraphy data in tabular format and objectivize workout intensity.

<!-- 
This <script> tag links to the Embedding API library as a JavaScript ES6 module. 
To use the library in your web application, you need to set the type attribute to 
module in the <script> tag. 
-->

<script type="module" src="https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js"></script>

<!-- 
Initialize the API as part of your HTML code by using the <tableau-viz> web component. 
After linking to the API library, the following code is all you need to embed a Tableau view into your HTML pages.
'https://public.tableau.com/views/Superstore_24/Overview' 
-->

<tableau-viz id="tableauViz"       
  src='https://public.tableau.com/views/Bodypump-StrengthinNumbers/01a-Trackoverallcomparison'     
  height='1100px' width='1400px' toolbar='bottom'>
</tableau-viz>
