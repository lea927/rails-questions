<div align="center">
  <img height="60" src="https://img.icons8.com/external-tal-revivo-color-tal-revivo/512/external-rails-a-server-side-web-application-framework-written-in-ruby-logo-color-tal-revivo.png">
  <h1>Ruby on Rails Questions</h1>

---

A list of Ruby on Rails questions with answers. This was mainly inspired by the [Javascript Questions](https://github.com/lydiahallie/javascript-questions) and [Awesome Interviews](https://github.com/DopplerHQ/awesome-interview-questions#ruby-on-rails) repos. I'll try my best to update this from time to time.

---

###### 1. What does ruby name refer to?

<details><summary><b>Answer</b></summary>
<p>

- Ruby names refer to the classes, variables, methods, constants and modules that help in the creation of the program.

- These are the names that distinguish other names with the specified ruby names that are being mentioned above.

- Ruby names are useful and used to be written as it is shown. They are useful in the context of writing the programs and while generating the module.

- Ruby names refer to the classes that has to be built and through which the objects will be declared, and methods that will perform on the data that is given.

- The names are reserved such that they can’t be used anywhere else and for any other purpose. The name that is used can be in lower or upper case, letter, number or an underscore.

[Reference](https://www.careerride.com/view.aspx?id=2439)

</p>
</details>

---

###### 2. What is the difference between Symbol and String?

<details><summary><b>Answer</b></summary>
<p>

- The symbol in Ruby on rails act the same way as the string but the difference is in their behaviors that are opposite to each other.

- The difference remains in the object_id, memory and process time for both of them when used together at one time.

- Strings are considered as mutable objects. Whereas, symbols, belongs to the category of immutable.

- Strings objects are mutable so that it takes only the assignments to change the object information. Whereas, information of, immutable objects gets overwritten.

- String objects are written like
```ruby
p: “string object jack”.object_id #=>2250 or
p: “string object jack”.to_sym.object_id #=> 2260, and
p: “string object jack”. to_s_object_id #=> 2270
```

- Symbols are used to show the values for the actions like equality or non-equality to test the symbols faster then the string values.

[Reference](https://www.careerride.com/view.aspx?id=2438)

</p>
</details>

---

###### 3. What does Session and Cookies represent in Ruby on Rails?

<details><summary><b>Answer</b></summary>
<p>

- Sessions are important as they provide with useful information regarding the customer and different server side information.

- Cookies on the other hand use the store information that are stored on the client side platform or related to the browser.

- Sessions are required to store the information regarding the user’s information and the actions that he will take only.

- The session is given as:
```ruby
session [:user] = “Rohit”.
```

- The session remains till the browser till the information is getting stored and the browser is getting closed by the user for the same.

[Reference](https://www.careerride.com/view.aspx?id=2437)

</p>
</details>

---

###### 4. What is the role of MVC architecture in Ruby on Rails?

<details><summary><b>Answer</b></summary>
<p>

- MVC (Model-View-Controller) is the architecture that provides flexibility and scalability of the applications.

- It is almost having the same concept in any other language like PHP, Perl or Python. It is one of the major used architecture involved today due to its simplicity.

- Controller is the main part in this kind of architecture where it handles the request that is coming from another controller.

- Controller contacts the view and passes on the request to the view and it also interacts with the model to define the type of request.

- Model is responsible for interacting with the database and provides the responses to the controller.

- Controller takes the response and gives the response in the output form to the user that has made the request.

[Reference](https://www.careerride.com/view.aspx?id=2435)

</p>
</details>

---

###### 5. What are the components defined in the model from MVC architecture?

<details><summary><b>Answer</b></summary>
<p>

The components involved in defining the model are as follows:

- Validations: this is one of the very essential components and it defines the validations that are being put up on the input type of stream like validate_presence_of, format_of, etc.
- Relationship: this is another type of component that describe the relationship between different types of components and it shows the relationship in the form of has_one, has_many, etc.
- Callbacks: this is essential when it comes to respond after the failure and it allows the application to have certain functionality during failure. This can be given as before_save, after_save, etc.
- Validation group settings: allow users to define the installed plugin settings.
- Active record association relationship: allows current records to be actively having the relationship between one another.

[Reference](https://www.careerride.com/view.aspx?id=2434)

</p>
</details>

---

###### 6. What is the function of ORM in Ruby on Rails?

<details><summary><b>Answer</b></summary>
<p>

- ORM stands for Object Relationship Model that models the classes and helps in setting a relationship between the existing models.

- It allows the classes to be mapped to the table that is present in the database and objects get mapped to the rows in database table.

- It shows the relationship that exists between the object and frame it using the model to display the output to the users.

- It keeps the data in the database according to its relationships and performs the functions accordingly.

- It maps the database in case of any updates and update for the same if the fields are changed or new values are entered.

[Reference](https://www.careerride.com/view.aspx?id=2433)

</p>
</details>

---

###### 7. What are the different types of association relationships that exist?

<details><summary><b>Answer</b></summary>
<p>

- The association relationship depends on the number of models made in the rails application.
- To create the connection for the application the command that is required is createconnection that creates the connection between the models.
- The connection when established there is a need to show the association between the different models and this can be done using three types of associations:
- One-to-one: this is the kind of relationship that exists between one item to another item. For example: Dog->Owner.
- One-to-many: this kind of relationship or association exists between one item to many other item. Teacher-> student.
- Many-to-many: this relationship shows many items to many items association and the items are related to each other. Student->Student.

[Reference](https://www.careerride.com/view.aspx?id=2432)

</p>
</details>

---

###### 8. What is the difference between render and redirect?

<details><summary><b>Answer</b></summary>
<p>

- Redirect is a method that is used to issue the error message in case the page is not found or it issues a 302 to the browser. Whereas, render is a method used to create the content.

- Redirect is used to tell the browser to issue a new request. Whereas, render only works in case the controller is being set up properly with the variables that needs to be rendered.

- Redirect is used when the user needs to redirect its response to some other page or URL. Whereas, render method renders a page and generate a code of 200.

- Redirect is used as:
redirect_to: controller => ‘users’, :action => ‘new’

- Render is used as:
render: partial
render: new -> this will call the template named as new.rhtml without the need of redirecting it to the new action.

[Reference](https://www.careerride.com/view.aspx?id=2431)

</p>
</details>

---

###### 9. What is the difference between Static and Dynamic Scaffolding?

<details><summary><b>Answer</b></summary>
<p>

- Dynamic Scaffolding is used to give the model name that is being used with the function like: scaffold: model_name. Whereas, Static Scaffolding requires manual entry in the command and it is given as:

- Script/generate scaffold Post title: string content:text category_id: integer

- Dynamic Scaffolding automatically generates the entire content and user interface at runtime. Whereas, Static Scaffolding requires the insertion of the command to, generate the data with their fields.

- Dynamic Scaffolding doesn’t require the database to be integrated as it gets created in runtime. Whereas, Static Scaffolding requires the database to, be migrated.

- Dynamic Scaffolding allows the generation of new, edit and deletes methods for the use in application. Whereas, Static Scaffolding doesn’t allow any such generation to, take place.

[Reference](https://www.careerride.com/view.aspx?id=2430)

</p>
</details>

---

###### 10. What is the main function of helpers used in Ruby on Rails?

<details><summary><b>Answer</b></summary>
<p>

- Helpers are the functionality provided by the View for the modules to provide the help classes in MVC architecture.

- Helpers provide the method that automatically used in the view. It helps the controller to take the pre- defined classes given in helper.

- Helpers provide shortcuts to display the code that are used in the programming of the application and used to have the views.

- Helpers allows user to see the structure of the output if the view file is having the less classes and written in a clear manner.

- Helper classes are used to provide the functionality that is required to create an application.

[Reference](https://www.careerride.com/view.aspx?id=2427)

</p>
</details>

---

###### 11. What are the different components of Rails?

<details><summary><b>Answer</b></summary>
<p>

The components used in Rails are as follows:

- Action Controller: it is the component that manages all other controllers and process the incoming request to the Rails application.
-  It extracts the parameters and dispatches the response when an action is performed on the application.
-  It provides services like session management, template rendering and redirect management.

- Action View: it manages the views of the Rails application and it creates the output in both HTML and XML format.
-  It also provides the management of the templates and gives the AJAX support that is being used with the application.

- Active Record: It provides the base platform for the models and gets used in the Rails application. It provides the database independence, CRUID functionality, search capability and setting the relationship between different models.

- Action Mailer: It is a framework that provides email services to build the platform on which flexible templates can be implemented.

[Reference](https://www.careerride.com/view.aspx?id=2426)

</p>
</details>

---

###### 12. What is the directory structure of Rails?

<details><summary><b>Answer</b></summary>
<p>

The directory structure of Rails includes the following:

- app/ - this is the folder that consists of controller, models and views of the appliation.

- config/- this folder consists of the configuration of the application that consists of runtime rules, routes, databases, etc.

- db/- this folder consists the database schema that is being currently used. It also has the information regarding the database migration.

- doc/- this is the folder that consists of all the documentation that is required to be used with the application.

- lib/- this folder consists of the extended modules and the libraries that is being used by the application

- log/- this folder consists of the logs that is being generated during the execution of the application.

- public/- this folder consists of the CSS, images and JavaScript folder to be used in the public domain with the application.

[Reference](https://www.careerride.com/view.aspx?id=2425)

</p>
</details>

---

###### 13. What are the functions performed by Rails migration?

<details><summary><b>Answer</b></summary>
<p>

- Rails migration allows the creation of the table and provides the functionality that can be performed on a table with the following commands:
```ruby
create_table(name, options)
drop_table(name)
rename_table(old_name, new_name)
add_column(table_name, column_name, type, options)
rename_column(table_name, column_name, type, options)
```

- Rails Migration also allows the use of pre-defined data type in the application as it supports all the data types. The data types consist of string, integer, float, etc.

- Rails Migration allows the users to use the valid column options like 
```ruby
limit (:limit=> “50”), default (:default => “hello”), and null (:null => false implies NOT NULL)
```

[Reference](https://www.careerride.com/view.aspx?id=2424)

</p>
</details>

---

###### 14. What is the use of $ in Ruby?

<details><summary><b>Answer</b></summary>
<p>

-$ in Ruby is treated as a global variable and it is used in a class variable that starts with an @sign and followed by upper or lower case letters.

-Class variable can be shared between many other objects of the class and each of the class variables exists for each given class.

-The $ (global variable) is followed by the name character and it defines the scope of the variable that is to be used.

-The global variable can use other punctuation characters like $_ and $-a. The example is given as:

```ruby
class Test
def h
Ã‚ $a = 5
Ã‚ @b = 4
while $a > 0
puts $a
$a= $a - 1
end
end
end
test = Test.new
test.h
puts $aÃ‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ # 10
puts @bÃ‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ Ã‚ #nil
```

[Reference](https://www.careerride.com/view.aspx?id=2423)

</p>
</details>

---

###### 15. What is the function of garbage collection in Ruby on Rails?

<details><summary><b>Answer</b></summary>
<p>

- Garbage collection allows the removal of the pointer values that is left behind when the execution of the program ends.

- It frees the programmer from tracking the object that is being created dynamically on runtime.

- It provides a provision to remove the inaccessible objects from the memory and frees it so that other processes can use it.

- Garbage collection is used as:
```ruby
x = Object.new
# this object is in use and it is residing in the memory. If it is not used then the status says
x = nil
# this means that the object can be removed from the memory and the memory can be freed for the other processes to run.
```

[Reference](https://www.careerride.com/view.aspx?id=2421)

</p>
</details>

---

###### 16. What is the purpose of load, auto_load, and require_relative in Ruby?

<details><summary><b>Answer</b></summary>
<p>
- Load allows the process or a method to be loaded in the memory and it actually processes the execution of the program used in a separate file.

It includes the classes, modules, methods and other files that executes in the current scope that is being defined.
It performs the inclusion operation and reprocesses the whole code every time the load is being called.

- Auto_load: this initiates the method that is in hat file and allows the interpreter to call the method.

- require_relative: allows the loading to take place of the local folders and files.

[Reference](https://www.careerride.com/view.aspx?id=2419)

</p>
</details>
