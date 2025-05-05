# cop3503-lab-9---maps-solved
**TO GET THIS SOLUTION VISIT:** [COP3503 Lab 9 – Maps Solved](https://www.ankitcodinghub.com/product/cop3503-lab-9-maps-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;30416&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP3503 Lab 9 – Maps Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<h1>Overview</h1>
In this assignment you are going to use the map classes from the standard template library to store different types of data. For this assignment, main() is mostly implemented for you; you just need to fill in the blanks.

<h1>Description</h1>
<h2>Part 1</h2>
For the first part, you are going to store the results of some randomly generated numbers. A map is a

great data structure for storing information with identifiers, but especially when encountering data that you don’t know about before the program runs. This is where maps can really shine.

An effective method for generating random numbers is provided for you, but here’s what it looks like:

// An “engine” for generating random numbers std::mt19937 random_mt;

&nbsp;

// Using that engine, generate a random number between the given parameters (inclusively)int Random(int min, int max)

{

uniform_int_distribution&lt;int&gt; dist(min, max); &nbsp;&nbsp;&nbsp;return dist(random_mt);

}

&nbsp;

You need to create a function that has the following signature: void RollDice(int numberOfRolls, int numberOfSides);

In this function, you’re going to create a map&lt;key,value&gt; object to store the results of these rolls. The number rolled is the key, and the number of times it is rolled is the value. Your output will look something like this:

&nbsp;

With larger quantities of rolls, the distribution of each value should approach uniformity—that is, if you were to generate a random number within a certain range an infinite number of times, all numbers within that range would be generated equally. As the number of rolls shrinks, there may be a larger imbalance between some of the values, which is normal.

Since you will be recording the results that are rolled, how do you get a 0? This isn’t something you would always do necessarily, but for this assignment you should “seed” the map object with a default value for all key/value pairs.

<h2>Part 2</h2>
For this part, you are going to store data in a slightly more complex format. You’re going to load a file that has information about states in the US. The data will in a CSV file, and is structured like this:

<table width="623">
<tbody>
<tr>
<td width="125">State</td>
<td width="113">Per capita income</td>
<td width="79">Population</td>
<td width="164">Median household income</td>
<td width="141">Number of households</td>
</tr>
<tr>
<td width="125">Mississippi</td>
<td width="113">21036</td>
<td width="79">2994079</td>
<td width="164">39680</td>
<td width="141">1095823</td>
</tr>
<tr>
<td width="125">West Virginia</td>
<td width="113">22714</td>
<td width="79">1850326</td>
<td width="164">41059</td>
<td width="141">735375</td>
</tr>
<tr>
<td width="125">Arkansas</td>
<td width="113">22883</td>
<td width="79">2966369</td>
<td width="164">41262</td>
<td width="141">1131288</td>
</tr>
<tr>
<td width="125">Alabama</td>
<td width="113">23606</td>
<td width="79">4849377</td>
<td width="164">42830</td>
<td width="141">1841217</td>
</tr>
<tr>
<td width="125">New Mexico</td>
<td width="113">23683</td>
<td width="79">2085572</td>
<td width="164">44803</td>
<td width="141">760916</td>
</tr>
<tr>
<td width="125">Kentucky</td>
<td width="113">23684</td>
<td width="79">4413457</td>
<td width="164">42958</td>
<td width="141">1712094</td>
</tr>
<tr>
<td width="125">Idaho</td>
<td width="113">23938</td>
<td width="79">1634464</td>
<td width="164">47861</td>
<td width="141">591587</td>
</tr>
<tr>
<td width="125">Etc…</td>
<td width="113"></td>
<td width="79"></td>
<td width="164"></td>
<td width="141"></td>
</tr>
</tbody>
</table>
&nbsp;

You will need to create a class/structure to store one of these rows of data as an object, and ultimately store all of the states in a map&lt;string,WhateverYouCallYourClass&gt;.

After that, you will need to get input for one of two options: either print out all the key/values in the map object, or do a search for a particular key, and then print the key/value pair based on the search result. The search is case-sensitive (the first letter of the key is capitalized).

&nbsp;

The key to going through STL containers is to use iterators. While some objects like vectors and strings store their data contiguously, making simple for loop iteration possible, that’s not true of all containers. For that, you need an iterator. In C++ iterators commonly revolve around permutations of 2 functions: begin(), and end().

Want to start with the first element in a list? That’s begin(). Want to reach the end of the list? That’s just BEFORE end(). Before? Why not on end()? The end() function returns an iterator that is beyond the range of elements.

Think of it like this: if you were looping through an array of 10 elements, the valid indices would be 0-9.

The “end” index would be 10, or 1 past the last element. With iterators, end() functions the same way. In both cases, you should never try to USE that “just past the end” element, but it can be helpful to check against that.
