Download Link: https://assignmentchef.com/product/solved-cpsc-121-lab-8
<br>
Using the standard library, classes

Using the gladiator class from before, we are going to create two armies that will attack each other. This will be accomplished by using the &lt;vector&gt; library

Write a program that performs the following:

<ol>

 <li>Create two vectors of Gladiators (see last section of Chapter 7), one for the Red team, and one for the Blue team</li>

 <li>Show the number of fighters alive on each team</li>

 <li>Present the user with the following menu

  <ol>

   <li>Take Turn

    <ol>

     <li>Randomly select between red team and blue team</li>

     <li>Use the first/next fighter on that team to attack a random enemy in the enemy team

      <ol>

       <li>Any fighters that get get killed should be removed from the team (With a notification)!</li>

       <li>Describe what happened each attack, including which team the attacker is part of.</li>

      </ol></li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>Repeat this process until all fighters have had a chance to attack.</li>

</ul>

<ol>

 <li>Add Fighters

  <ol>

   <li>Add one fighter to both teams

    <ol>

     <li>It would be easier to give fighters a name randomly selected from a list (array) of potential names, than to ask the user for two names every time they want to add more fighters</li>

     <li>Show the stats of both fighters as/after they have been added</li>

    </ol></li>

   <li>Exit Program</li>

  </ol></li>

 <li>Return to step 2</li>

</ol>

I will soon make a set of bug-free gladiator method definitions for you to use. We will be including it – and the class definition – as separate files in this project – we will go over how to compile it together in lab.

Menu input should accept either a single lowercase char or an integer, prompts should tell user what to enter.

Points:

1.5 – Documentation, readability, format

1.5 – Filename and Header

2 – Output testing

<ul>

 <li>– Proper program flow (conditions, loops, functions, etc)</li>

 <li>– Proper use of vectors</li>

</ul>


