In UML class diagrams, the symbols + and - indicate the visibility (access level) of class members (attributes or methods).

Here’s what they mean:

Symbol	Visibility	Meaning
    +	Public	Accessible from anywhere (any other class or object).
    -	Private	Accessible only within the same class.

    
Other visibility symbols you might also see:

Symbol	Visibility	Meaning
    #	Protected	Accessible within the same class and its subclasses.
    ~	Package (default)	Accessible to all classes in the same package/module.



Example UML snippet:


Copy code
-------------------------
|       Person          |
-------------------------
| - name : String       |   // private attribute
| + age : int           |   // public attribute
-------------------------
| + getName() : String  |   // public method
| - setName(n:String)   |   // private method
-------------------------
✅ Summary:

+ → public
- → private
# → protected
~ → package