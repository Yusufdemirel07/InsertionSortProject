# InsertionSortProject
Insertion Sort Project for Patika

# Proje 1

[22,27,16,2,18,6] -> Insertion Sort

<ol>

<li>Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.</li>
<li>Big-O gösterimini yazınız.</li>
<li>Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.</li>
<li>Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.</li>

</ol>

<p> Best Case Complexity O(n) </p>

<p> Worst Case Complexity O(n^2) </p>

<p> Average Case Complexity O(n^2) </p>

<p>Check it in ascending order: [22,27,16,2,18,6]</p>

<p>Firstly let's we check complexity: It is not ordered, so it is not best case. It is not exactly opposite than we need to, so it is not worst case. So, it is average case. Then time complexity is o(n^2).</p>


<p>Let's see how it works. [22,27,16,2,18,6]:</p>

<ol>
<li>i=0 22,27,16,2,18,6 --> 22 is stored and 27 started to compare with first element. So, 27 is greater than first.</li>

<li>i=1 22,27,16,2,18,6 --> 27 was stored and 16 started to compare with stored ones. 16 is smaller than stored ones. So, 16 will go to beginning.</li>

<li>i=2 16,22,27,2,18,6 --> 16 was stored and 2 started to compare with stored ones. 2 is smaller than stored ones. So, 2 will go to beginning.</li>

<li>i=3 2,16,22,27,18,6 --> 2 was stored and 18 started to compare with stored ones. 18 will go to between 16 and 22.</li>

<li>i=4 2,16,18,22,27,6 --> 18 was stored and 6 started to compare with stored ones. 6 will go to between 2 and 16.</li>

<li>i=5 2,6,16,18,22,27 --> 6 was stored and elements were ordered in ascending by insertion algorithm.</li>
</ol>

# Proje 2

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

<ol>

<li>i=0 7,3,5,8,2,9,4,15,6 --> 7 is stored and 3 started to stored one. So, 3 is smaller than first. 3 will go to beginning.</li>

<li>i=1 3,7,5,8,2,9,4,15,6 --> 3 was stored and 5 started to compare with stored ones. So, 5 will go to between 7 and 3.</li>

<li>i=2 3,5,7,8,2,9,4,15,6 --> 5 was stored and 8 started to compare with stored ones. So, 8 will stay at same index.</li>

<li>i=3 3,5,7,8,2,9,4,15,6 --> 8 was stored and 2 started to compare with stored ones. 2 will go to beginning.</li>

<li>i=4 2,3,5,7,8,9,4,15,6 --> 2 was stored and 9 started to compare with stored ones. 9 will stay at same index.</li>

<li>i=5 2,3,5,7,8,9,4,15,6 --> 9 was stored and 4 started to compare with stored ones. 4 will go to between 3 and 5.</li>

<li>i=6 2,3,4,5,7,8,9,15,6 --> 4 was stored and 15 started to compare with stored ones. 15 will stay at same index.</li>

<li>i=7 2,3,4,5,7,8,9,15,6 --> 15 was stored and 6 started to compare with stored ones. 6 will go to between 5 and 7.</li>

<li>i=8 2,3,4,5,6,7,8,9,15 --> 6 was stored and elements were ordered in ascending by insertion algorithm.</li>

</ol>
