# cse108-assignment-2--inheritence-solved
**TO GET THIS SOLUTION VISIT:** [CSE108 Assignment 2- Inheritence Solved](https://www.ankitcodinghub.com/product/cse108-assignment-2-inheritence-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96918&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE108 Assignment 2- Inheritence Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Suppose you are working on a turn-based (i.e. user makes a move, then the CPU makes a move (much like chess) war strategy game. They all have the following attributes:

<ol>
<li>Range: the distance upto which it can attack enemies</li>
<li>Health Point (HP): the unit dies when HP drops to 0 or a lower value</li>
<li>Cost: the amount of coins needed to deploy it</li>
<li>Damage: the amount of damage it can in ict upon its enemies per turn</li>
</ol>
There are two type of units:

<ul>
<li>Moving Unit</li>
<li>Stationary Unit</li>
</ul>
Archers and Advanced Archers are part of the Moving unit where Bowman and Advanced Bowman are part of the Stationary unit. Bowmen shoots basic arrows and Advanced Bowmen shoots using canon. On the other hand, Archers shoot advanced arrows and Advanced Archers shoot improved arrows. Although the stationary unit cannot move, because of their high shooting range, they can be pretty handy. The Archers move by running on the field whereas the Advanced Archers ride horses. The advanced archers are much like Dothraki from Game of Thrones. They are very efficient in war and can cause great damage to the opponent; making them an excellent troop. Whenever you deploy a force, it will cost you some coin. The stationary unit has one advantage. Whenever they die, they will give you some coin back.

Besides these, there is an Enemy Tower which has tremendous defensive mechanism. The Enemy tower remains still but its shooting range is extremely high. A comprehensive summary is given in the following table:

Table 1: Description of different units.

<table width="653">
<tbody>
<tr>
<td width="81">unit</td>
<td width="59">range</td>
<td width="61">health</td>
<td width="66">Damage</td>
<td width="54">Cost</td>
<td width="57">Step size</td>
<td width="63">Return Coin</td>
<td width="132">Shoot Type</td>
<td width="79">movement</td>
</tr>
<tr>
<td width="81">bowman</td>
<td width="59">110</td>
<td width="61">60</td>
<td width="66">10</td>
<td width="54">100</td>
<td width="57">N/A</td>
<td width="63">40</td>
<td width="132">Basic Arrow</td>
<td width="79">N/A</td>
</tr>
<tr>
<td width="81">advanced bowman</td>
<td width="59">130</td>
<td width="61">85</td>
<td width="66">15</td>
<td width="54">200</td>
<td width="57">N/A</td>
<td width="63">60</td>
<td width="132">Canon</td>
<td width="79">N/A</td>
</tr>
<tr>
<td width="81">archer</td>
<td width="59">50</td>
<td width="61">100</td>
<td width="66">25</td>
<td width="54">150</td>
<td width="57">25</td>
<td width="63">N/A</td>
<td width="132">Advanced Arrow</td>
<td width="79">Run</td>
</tr>
<tr>
<td width="81">advanced archer</td>
<td width="59">50</td>
<td width="61">120</td>
<td width="66">50</td>
<td width="54">600</td>
<td width="57">30</td>
<td width="63">N/A</td>
<td width="132">Improved Arrow</td>
<td width="79">Ride Horse</td>
</tr>
<tr>
<td width="81">Enemy Tower</td>
<td width="59">200</td>
<td width="61">300</td>
<td width="66">40</td>
<td width="54">N/A</td>
<td width="57">N/A</td>
<td width="63">N/A</td>
<td width="132">Fire Arrow</td>
<td width="79">N/A</td>
</tr>
</tbody>
</table>
<strong>Gameplay</strong>

The game progresses in rounds, each round consisting of two turns (the first turn for the user and the second one for the CPU). Suppose right now you are interested to test a simplified version of the game. In this version there is a single enemy tower (which is stationary) that you need to destroy. The tower is at 100 units distance from your base camp. You can generate as many units as you want (within the coin limit) one after another (i.e. after one unit dies, you can generate another one), but you cannot generate more than one unit simultaneously. That means only one of your units will be active at a time. After it is destroyed, you can generate the next one. Also remember, it will cost you some coin to generate a unit. You can choose which unit you want to generate. In each turn, a unit moves towards the enemy tower in order to get as close to it as possible, but never crosses it. It then shoots the target if it is within range. If the unit dies, user can choose the next unit to generate. Every time the newly generated unit will start from the beginning. The user has a fixed amount of coin initially which in this case is 1600. If all the coins get spent during the game, the user will lose. If the user can destroy the enemy tower, he will be the winner.

<strong>&nbsp;</strong>

<strong>Instructions</strong>

You must use your concept of inheritance appropriately. The class hierarchy should be maintained properly. A small code fragment is given. In the code segment, you can see that we have created a base class pointer w<strong>. You have to complete all the functionalities of the user using only the base class pointer w.</strong> You cannot instantiate any of your derived classes. That means you cannot write the following code fragment or something similar to this:

&nbsp;

<strong>Archer arch;</strong>

&nbsp;

If you complete this assignment correctly, you will be able to understand the full power of inheritance. For the enemy tower, you may instantiate another base class pointer. &nbsp;However, you cannot instantiate any derived class for that as well. You have been given an exe of the solution. You can run the exe file to get a better understanding of what you have to do. Try to show your outputs according to the output of the exe file.
