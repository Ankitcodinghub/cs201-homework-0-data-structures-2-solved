# cs201-homework-0-data-structures-2-solved
**TO GET THIS SOLUTION VISIT:** [CS201 Homework 0-Data Structures 2 Solved](https://www.ankitcodinghub.com/product/cs201-homework-0-data-structures-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102239&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS201 Homework 0-Data Structures 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

The express purpose of this homework is to get you ready for your forthcoming assignments. It covers

􏰃 OOP in python

􏰃 Allowing native python functionality for your class

1. Introduction

You already know about OOP in C++. This homework will get you used to the corresponding syntax in python. Below is an example class in python.

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
class Car(object): num_wheels = 4

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __init__(self, color):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self.wheels = Car.num_wheels self.color = color

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def drive(self):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if self.wheels &lt;= Car.num_wheels:

return self.color + ‘ car cannot drive!’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return self.color + ‘ car goes vroom!’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def pop_tire(self):

if self.wheels &gt; 0:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self.wheels -= 1

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Line 1 is a class declaration. By convention, all python classes that do not derive from any other class, must derive from the object class. Leaving out this inheritance does not make much difference. All subsequent lines that are indented become part of the definition of this class.

Line 2 declares a class variable. That is, every object of this class has access to the same, single instance of this variable. This variable belongs to the class and not to any instance. Line 9 illustrates the corresponding syntax to access this variable. You may include class variables in your classes if needed.

Line 4 declares the constructor. The double underscores or dunders in the function name are required. The constructor takes a mandatory parameter, self, which is a reserved word in python and automatically refers to the object that is calling this method. This is similar to this in C++. Just that this is passed implicitly in C++ whereas self must be the first parameter in the header of a method. Note that self does not have to be passed when the method is called. The constructor can take any number of additional parameters. In this case, it takes 1, color.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Lines 5 and 6 are the body of the constructor. You can put any desired logic here. Usually, the constructor initializes member variables, which is also the case here. Member variables need to be referred to using the self parameter and the dot syntax.

Lines 8 to 15 define other methods. Note the mandatory first parameter of self in each header, and how member variables are accessed. Line 9 additionally illustrates accessing a class variable. The methods here do not have any parameters other than self. This is a coincidence and not a requirement. That is, methods may have any number of parameters, just like regular functions. Just that the first parameter must be self. If the first parameter is not self, then the method belongs to the class, and not an instance.

Below is an example interaction with our class.

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; my_car = Car(‘red’) &gt;&gt;&gt; print(my_car.color)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
red

&gt;&gt;&gt; print(my_car.wheels)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

&gt;&gt;&gt; print(Car.num_wheels)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

&gt;&gt;&gt; print(my_car.num_wheels)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

&gt;&gt;&gt; print(Car.wheels)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Traceback (most recent call last): File “&lt;stdin &gt;”, line 1, in &lt;module&gt;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
AttributeError: type object ‘Car’ has no attribute ‘wheels’ &gt;&gt;&gt; my_car.pop_tire()

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; my_car.drive()

‘red car cannot drive!’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; Car.drive()

Traceback (most recent call last):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
File “&lt;stdin &gt;”, line 1, in &lt;module&gt;

TypeError: drive() missing 1 required positional argument: ‘self’

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Line 1 creates an instance, my_car. This will internally call the __init__ method of the Car class. Note that nothing needs to be passed for the self parameter of the __init__ method.

Lines 2 to 5 illustrate access to member variables. Note that member variables are public in python!

Lines 5 to 13 illustrate access to class and member variables. The class variable, num_wheels , can be accessed via the class (line 6) and via an instance (line 8). However, a member variable cannot be accessed through the class (line 10).

Lines 14 to 20 illustrate calling member methods. They can be called via an instance using the dot syntax (lines 14 and 15) but not via the class (line 17). Note again that nothing needs to be explicitly passed to correspond to the self parameter of these methods.

Task: Solve the exercises here.

</div>
</div>
<div class="layoutArea">
<div class="column">
2. Disciples of Discipline

Having experienced this heavy semester before, we would like to transfer our wisdom and help you guys plan and execute your semester courses’ study plan in a very structured and disciplined manner. Therefore, we want you to create a portal for managing all of your individual courses which would then help you design a study plan and prioritize study materials as per the commitments of a respective course. We also want you all to learn the art of self-sufficient learning where you are confident with internet scanning when it comes

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
to looking for answers for technical questions that one (and every born programmer) might encounter when coding. Thus, we will be providing you with links for concepts that you have to implement in this task; that you can consult, understand and then implement as per your requirements.

You will create a Course class to encapsulate all the important attributes for any course. It will also support functionality to add, remove, and print assignments. You will also create a Schedule class which will contain your courses and indicate your schedule and total number of credits this semester.

Task: Implement the methods in the Course class provided in the accompanying file, src/course.py.

Task: Implement the methods in the Schedule class provided in the accompanying file, src/schedule.py.

Resources: The classes make use of the datetime.datetime object which you can learn about here.

3. Guten Appetit

You are a celebrated chef with many famous dishes to your name. A believer in open source, you are now looking to share your inventions with the world. A computer scientist at heart, you are developing a library which you will use to program your recipes. You will eventually disseminate this library so that not only do people learn of your recipes but they can use the library to program and share their recipes as well.

Two of the classes in your library are Ingredient and Recipe. Ingredient stores a name. Recipe stores a name and Ingredient objects along with the required quantity in grams. Below is an example interaction with these classes.

1 2 3 4 5 6 7 8 9

10 11 12 13 14

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; my_recipe = Recipe(‘Stairway to Heaven’)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; my_recipe.add_ingredient(Ingredient(‘Sugar’), 10) &gt;&gt;&gt; my_recipe.add_ingredient(Ingredient(‘Spice’), 10)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; my_recipe.add_ingredient(Ingredient(‘Everything Nice’), 20) &gt;&gt;&gt; my_recipe.add_ingredient(Ingredient(‘Chemical X’), 100)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; len(my_recipe) # number of ingredients 4

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; for ing, amt in my_recipe: # iterate over ingredients … print(f'{ing}: {amt}g’)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
…

Sugar: 10g

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Spice: 10g Everything Nice: 20g

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Chemical X: 100g

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Task: Write both classes in the accompanying file, src/recipe.py, such that they support this interaction.

Resources: There are several features you will need to learn about.

􏰃 Writing a custom iterator: See here (first 3 sections only) for an insightful explanation and here for a quick example.

􏰃 Calling len() on a custom class: Included in the above references.. 􏰃 Tuple assignment and unpacking: See here.

</div>
</div>
</div>
