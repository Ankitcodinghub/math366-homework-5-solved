# math366-homework-5-solved
**TO GET THIS SOLUTION VISIT:** [MATH366 Homework 5 Solved](https://www.ankitcodinghub.com/product/math366-homework-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92281&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MATH366 Homework 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<strong>Problem 1: </strong>Suppose we have an ordered list of <em>n </em>items of food. Let <strong>a </strong>∈ R<em><sup>n </sup></em>denote the <em>price vector </em>of all these food items, let <strong>p </strong>∈R<em><sup>n </sup></em>denote the protein vector, <strong>c </strong>∈R<em><sup>n </sup></em>denote the carbohydrate vector, <strong>f </strong>∈R<em><sup>n </sup></em>denote the fats vector.

Denote by <em>x<sub>i </sub></em>to be amount of food item <em>i</em>, and

<strong>x </strong>= (<em>x</em><sub>1</sub><em>,x</em><sub>2</sub><em>,…,x<sub>n</sub></em>)

to be the vector all these food combinations.

Find the vector <strong>x </strong>which will minimize the total cost, i.e. <strong>a</strong><em><sup>t</sup></em><strong>x</strong>, subject to the constraints that the total protein of the food combination needs to be at least <em>p</em>, total carbohydrate needs to be at least <em>c</em>, and the total fats need to be at least <em>f </em>(here <em>p,c,f </em>are given real numbers). Let us further require that the total calories of the food combination needs to be in the interval [cal<sub>low</sub><em>,</em>cal<sub>high</sub>] i.e. at least cal<sub>low </sub>calories but at most cal<sub>high </sub>calories, again the numbers cal<sub>low </sub>and cal<sub>high </sub>must be specified.

Create a code in R called, optimize.food(a,p.vec,c.vec,f.vec,p,c,f,cal.low,cal.high)

Which will return the vector <strong>x </strong>of food combinations that need to be selected that will minimize the total cost of production. Check that your code solves our special example that we did in class.

1

<strong>Problem 2: </strong>Suppose a firm produces a certain product. The demand for this product varies through out the year. Let <strong>d </strong>∈R<em><sup>n </sup></em>denote the demand vector, where <em>n </em>is the number of divisions of a full year (when <em>n </em>= 12 the year is broken up into months, when <em>n </em>= 26 the year is broke up biweekly, ect.).

The full year is broken up into <em>n </em>equal time blocks. The employees of the firm can produce at most <em>r </em>tons of this product, the cost for production is <em>k </em>dollars/ton. It is possible to overwork the employees so that they will produce beyond what they normally do. However, the cost for additional production is <em>K </em>dollars/ton (in applications this is always a bigger number than <em>k</em>) and the employees can only product up to <em>a </em>extra tons.

There is a storage cost of <em>s </em>dollars/ton where any unsold product can be carried into the next time block.

The goal of the firm is to sell off its entire product by the end of the year with no remaining surplus, meet the demand for each time block, and minimize the total cost of production.

Write the following code in R.

optimal.production(d,r,k,a,K,s) = computes the ideal production model to minimize the cost.
