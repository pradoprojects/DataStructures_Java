# General Instructions

* *[arranjo](./arranjo/)* is the folder where the list (Lista.java), stack (Pilha.java) and queue (Fila.java) are located.
* All the other ".java" files in this directory are solutions for the problems stated below. Each solution is specifically indicated by the links provided below.

<section>
<div align="justify">
<br/>

<h2> Problem "List Test" </h2>
<p>
You must implement a class that tests the methods of the Lista.java class. As the list is implemented over an array of objects, consider that the objects that will be inserted/removed in the list will be objects of the Integer class. 
</p>
<a href="./TestaLista.java">Check Solution</a>  
<br>
<br>
<br>
  
  
<h2> Problem "New List Operations" </h2>
<ol>
  <li>
You must implement the method "insereAposChave" in the List (Lista.java) so that it inserts an item after the first occurrence of a given key. <a href="./arranjo/Lista.java#L63" target="_blank">Check Solution</a> 
  </li>
  <li>
  You must implement the method "insereSemRepetir" in the List (Lista.java) so that it inserts an item only if there is no other item in the list with the same key as the item to insert.<a href="./arranjo/Lista.java#L106" target="_blank">Check Solution</a> 
  </li>
  <li>
  You must implement the method "uneListas" in the List (Lista.java) so that it joins two lists given as a parameter (the second must be joined at the end of the first). <a href="./arranjo/Lista.java#L129" target="_blank">Check Solution</a> 
  </li>
  
  <li>
  You must implement a class that tests the methods implemented for the previous itens. <a href="./TestaLista2.java" target="_blank">Check Solution</a> 
  </li>
</ol>
<br>
<br>
<br>
  
  
<h2> Problem "Stack Test" </h2>
<ol>
<li>
Define a method on the stack (Pilha.java) that prints the elements of the stack on the screen, in stack format. <a href="./arranjo/Pilha.java#L30" target="_blank">Check Solution</a> 
</li>
<li>
Test the method  that prints the the stack on the screen, in stack format. <a href="./arranjo/TestaPilha.java" target="_blank">Check Solution</a> 
</li>
  
<li>
  Build a program that exercises, in this order:
  <ol>
  <li>Creating two stacks.</li>
  <li>Filling the first stack with user-supplied integer values.</li>
  <li>Print the first stack.</li>
  <li>Filling the second stack by popping the items from the first.</li>
  <li>Printing the two stacks.</li>
  </ol>
  <a href="./TestaPilha2.java" target="_blank">Check Solution</a> 
</li>
</ol>
<br>
<br>
<br>
  
  
<h2> Problem "New Stack Operations" </h2>
<ol>
  <li>
  Build a program that exercises, in this order:
  <ol>
  <li>Creating two stacks.</li>
  <li>Filling the first stack with user-supplied integer values.</li>
  <li>Print the first stack.</li>
  <li>Filling the second stack by popping the items from the first.</li>
  <li>Printing the two stacks.</li>
  </ol>
  <a href="./TestaPilha2.java" target="_blank">Check Solution</a> 
  </li>
</ol>  
<br>
<br>
<br>

<h2> Problem "Queue Test and Interleaving Queue" </h2>
<ol>
  <li>
  Implement a method that prints the queue items in the order they were queued (oldest first and newest last). Test it.  <a href="./arranjo/Fila.java#L36" target="_blank">Check Solution (Part 1)</a> <a href="./Exercicio18.java" target="_blank">Check Solution (Part 2)</a>
  </li>
  <li>
  Implement a method on the queue in which, given another queue, it creates a third queue by interleaving the elements of the second with those of the first. Start merging with the queue that contains the method. Test it. <a href="./arranjo/Fila.java#L46" target="_blank">Check Solution (Part 1)</a> <a href="./Exercicio19.java" target="_blank">Check Solution (Part 2)</a>
  </li>
</ol>
<br>
<br>
<br>

  
<h2> Problem "Ticket Emission" </h2>
<ol>
  <li>
Implement a ticket class (Senha.java) which contains a password number, a type of service (priority or normal) and the time it was issued. Your class should override the toString() method in order to return a String with nr. password, time and type of service. 
  <a href="./Senha.java" target="_blank">Check Solution</a> 
  </li>

  <li>
Implement a test class that allows the user to generate 10 tickets. These tickets must be entered into a single list as they are generated. At the end of ticket generation, your program should go through the list, queuing priority service tickets in one queue and normal service tickets in another, following the order of the time they were issued. When finished, your program should alternately dequeue a ticket from each queue. For each unqueued ticket, you must print the information for that ticket. <a href="./Exercicio20.java" target="_blank">Check Solution</a>
</li>
</ol>
<br>
<br>
<br>

</div>   
</section>  
