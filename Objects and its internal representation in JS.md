<h1 align="center">Objects and its internal representations in JS</h1></div>
<p align="center">

<h2 align="left">Object Definition: Objects are variable too. But it contains many values. Object values are written as <i>Key:Value</i> pairs, Key and value separated by a colon</h2>
<h2 align="left"><b>Internal Representations in Javascript</b></h2>
<table><tr><td>const person = {firstName:"Raj", lastName:"S", age:29, eyeColor:"black"};</td>
<td>firstName  "Raj"<br> lastName  "S"<br> age  29<br> eyeColor   "black"</td>
</tr>
</table>
<table><h2 align="left">Accessing Object properties & Object Methods</h2>
<tr><td>objectName.propertyName <br> person.age (or) person["lastName"] </td>
<td>29S</td></tr>

<tr><td>const person = {firstName:"Raj", lastName:"S", age:29, eyeColor:"black" <br> fullName: function()<br> { <br> return this.firstName + ' ' + this.lastName;<br>
} <br>}<br>console.log(person.fullName()); </td><td>firstName  "Raj"<br> lastName  "S"<br> age  29<br> eyeColor   "black" <br>fullName Raj S<br> Raj S</td></tr>
</table>




</p>



