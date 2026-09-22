# OOP-Cpp-Unit-II Inheritance Code Book

Student Name: Parth Bhupesh Lohi

PRN: 125UME1165

Class/Division: S.Y. B.Tech. Artificial Intelligence and Data Science

Course Name: Object-Oriented Programming with C++ (ADPC303) - Unit II: Inheritance

## List of Programs

* Program 01: Basic Single Inheritance (`Person` to `Student`)


* Program 02: Protected Member Access (`Employee` to `Developer`)


* Program 03: Public versus Private Inheritance Accessibility


* Program 04: Multilevel Inheritance (`Person` $\rightarrow$ `Employee` $\rightarrow$ `Manager`)


* Program 05: Hierarchical Inheritance (`Vehicle` base with `Car` and `Bike`)


* Program 06: Multiple Inheritance (`Academic` and `Sports` to `Student`)


* Program 07: Resolving Multiple-Inheritance Ambiguity via Scope-Resolution


* Program 08: Constructor and Destructor Execution Order


* Program 09: Parameterized Base Constructor Initialization


* Program 10: Function Overriding with `virtual` and `override`

* Program 11: Abstract Class and Pure Virtual Functions (`Shape` area calculation)


* Program 12: Virtual Base Class and Diamond Inheritance Resolution


* Program 13: Friend Class Access Control (`Auditor` and `Account`)


* Program 14: Nested Class Implementation (`University::Department`)


* Program 15: Mini-Project - Vehicle Rental System (Integrated Inheritance)


* Program 16: Mini-Project - Employee Payroll System (Abstract Base & Overriding)



---

## Brief Description of Each Program

### Program 01

👤 Basic Single Inheritance
An object-oriented C++ program implementing single inheritance to establish an "is-a" relationship where `Student` inherits from a base class `Person`.

🚀 Key Features

* **Inheritance Relationship:** Derived class `Student` receives accessible members from base class `Person`.


* **Protected Encapsulation:** Utilizes `protected` members in the base class for controlled access.



📊 Sample Output

```text
Name: Amit
Roll Number: 101
```[cite: 2]

---

### Program 02
🛡️ Protected Member Access
A C++ program demonstrating how a derived class (`Developer`) accesses protected members (`name`) defined within a base class (`Employee`)[cite: 2].

🚀 Key Features
* **Protected Scope:** Protected members are accessible inside derived classes but restricted from direct outside code access[cite: 2].

📊 Sample Output
```text
Developer: Neha
Language: C++
```[cite: 2]

---

### Program 03
🔒 Public versus Private Inheritance
A C++ program observing how different inheritance modes affect member accessibility and visibility[cite: 2].

🚀 Key Features
* **Public Inheritance:** Public base members remain public through the derived object[cite: 2].
* **Private Inheritance:** Public and protected base members become private inside the derived class[cite: 2].

📊 Sample Output
```text
Base public function
Base public function
```[cite: 2]

---

### Program 04
📈 Multilevel Inheritance
A C++ program implementing a three-level hierarchy using `Person` $\rightarrow$ `Employee` $\rightarrow$ `Manager`[cite: 2].

🚀 Key Features
* **Hierarchical Chains:** Properties and methods propagate sequentially across multiple generation layers.

📊 Sample Output
```text
Name: Ravi
Employee ID: 501
Team Size: 8
```[cite: 2]

---

### Program 05
🚗 Hierarchical Inheritance
A C++ program implementing hierarchical inheritance with a common base class `Vehicle` branching into `Car` and `Bike`[cite: 2].

🚀 Key Features
* **Common Base Sharing:** Multiple derived classes share features from a single base class while implementing unique functionalities.

📊 Sample Output
```text
Vehicle MH12AB1234 started
Car boot opened
Vehicle MH12CD5678 started
Please wear a helmet
```[cite: 2]

---

### Program 06
🎓 Multiple Inheritance
A C++ program demonstrating multiple inheritance where a `Student` class inherits features from both `Academic` and `Sports` base classes[cite: 2].

🚀 Key Features
* **Multiple Base Integration:** Combines attributes and behaviors from more than one base class simultaneously.

📊 Sample Output
```text
Academic Marks: 80
Sports Marks: 15
Total Marks: 95
```[cite: 2]

---

### Program 07
🔀 Resolving Multiple-Inheritance Ambiguity
A C++ program resolving naming conflicts when two base classes contain identical function names using the scope-resolution operator (`::`)[cite: 2].

🚀 Key Features
* **Explicit Scoping:** Uses `BaseClass::memberName` to avoid compiler ambiguity.

📊 Sample Output
```text
Academic information
Sports information
Academic information
Sports information
```[cite: 2]

---

### Program 08
⚙️ Constructor and Destructor Order
A C++ program tracking the exact execution lifecycle sequence during the creation and destruction of a derived object[cite: 2].

🚀 Key Features
* **Creation Order:** Base constructor executes before the derived constructor[cite: 2].
* **Destruction Order:** Derived destructor executes before the base destructor[cite: 2].

📊 Sample Output
```text
Base constructor
Derived constructor
Derived destructor
Base destructor
```[cite: 2]

---

### Program 09
📥 Parameterized Base Constructor
A C++ program demonstrating how to pass arguments from a derived class constructor to initialize a parameterized base class constructor[cite: 2].

🚀 Key Features
* **Member Initializer Lists:** Safely passes parameters upward to the base constructor.

📊 Sample Output
```text
Name: Kiran
Roll Number: 24
```[cite: 2]

---

### Program 10
🔄 Function Overriding
A C++ program utilizing `virtual` functions and `override` specifiers to achieve runtime polymorphism[cite: 2].

🚀 Key Features
* **Run-time Polymorphism:** Enabled via the `virtual` keyword in the base class[cite: 2].
* **Compile-time Verification:** Uses `override` to ensure correct function signature matching in derived classes[cite: 1, 2].

📊 Sample Output
```text
Car moves on roads
Boat moves on water
```[cite: 2]

---

### Program 11
📐 Abstract Class
A C++ program implementing an abstract base class (`Shape`) containing pure virtual functions (`area()`)[cite: 2].

🚀 Key Features
* **Interface Enforcement:** Abstract classes cannot be instantiated directly and force derived classes to implement core behaviors[cite: 2].

📊 Sample Output
```text
Rectangle Area: 15
Circle Area: 12.5664
```[cite: 2]

---

### Program 12
💠 Virtual Base Class and Diamond Inheritance
A C++ program solving duplicate-base ambiguity in diamond inheritance structures using virtual base classes (`virtual public Person`)[cite: 2].

🚀 Key Features
* **Single Shared Sub-object:** Ensures only one copy of the common base class exists in the most-derived class.

📊 Sample Output
```text
Name: Riya
```[cite: 2]

---

### Program 13
🤝 Friend Class
A C++ program demonstrating special external access permissions granted to a `Friend Class` (`Auditor`) to inspect private attributes of `Account`[cite: 2].

🚀 Key Features
* **Controlled Exception Access:** Allows specific classes to inspect private data members when explicitly declared as a friend.

📊 Sample Output
```text
Account Balance: 5000
```[cite: 2]

---

### Program 14
📦 Nested Class
A C++ program demonstrating a class defined inside another enclosing class scope (`University::Department`)[cite: 2].

🚀 Key Features
* **Encapsulated Scope:** Groups tightly related helper classes inside upper-level modules.

📊 Sample Output
```text
Department: Artificial Intelligence and Data Science
```[cite: 2]

---

### Program 15
🚗 Mini-Project: Vehicle Rental System
An integrated inheritance application managing rental calculations, rates, and specialized attributes for different vehicle types (`Car`, `Bike`)[cite: 2].

🚀 Key Features
* **Polymorphic Rental Computations:** Overrides calculation and display logic based on vehicle classification.

📊 Sample Output
```text
Car Details
Registration: MH12AB1234
Rate per day: 2000
Doors: 5
Rent for 3 days: 6000

Bike Details
Registration: MH12CD5678
Rate per day: 800
Engine Capacity: 150 cc
Rent for 3 days: 2160
```[cite: 2]

---

### Program 16
💳 Mini-Project: Employee Payroll System
An advanced salary management application utilizing abstract base classes (`Employee`), pure virtual functions, and polymorphic reference interfaces (`PermanentEmployee`, `ContractEmployee`)[cite: 2].

🚀 Key Features
* **Unified Payslip Generation:** Processes heterogeneous employee records uniformly through base class references.

📊 Sample Output
```text
Employee ID: 101
Name: Asha
Salary: 48000

Employee ID: 102
Name: Vikas
Salary: 40000
```[cite: 2]

```
