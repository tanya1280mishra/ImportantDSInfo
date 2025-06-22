## On what bases the evaluation of machine coding round is done by the messho company
In Meesho’s machine coding round (and similar product-based companies), the evaluation is typically based on **multiple dimensions**, not just correctness. Here's a breakdown of the **key evaluation criteria** Meesho and similar companies usually focus on:

---

### ✅ 1. **Code Functionality & Correctness**

* Does the code meet all the functional requirements in the prompt?
* Are all edge cases handled properly?
* Does it pass all the given test cases (and possibly hidden test cases)?
* Is the feature set complete (basic + bonus)?

---

### 🧠 2. **Code Design / Modularity**

* Are you using proper abstraction (classes, functions, modules)?
* Is your code extensible? Can someone else easily build on top of it?
* Example: In an e-commerce cart system — are you separating concerns like `Cart`, `Product`, `DiscountEngine`, etc.?

---

### 📦 3. **Object-Oriented Design**

* Are OOP principles like **Encapsulation**, **Abstraction**, **Polymorphism**, and **Inheritance** applied correctly?
* Is your class design clean and intuitive?
* Do your entities map logically to real-world objects?

---

### 🧹 4. **Code Cleanliness & Readability**

* Is the code readable and clean (naming conventions, spacing, structure)?
* Are magic numbers avoided?
* Is the logic easy to follow for another developer?

---

### 📈 5. **Scalability & Performance**

* Can the solution handle a large number of users or inputs (within the scope of the problem)?
* Are you using appropriate data structures and algorithms?

---

### 🧪 6. **Test Coverage**

* Have you written unit tests or at least some driver code to validate your classes/methods?
* Are different edge cases and failure scenarios covered in your tests?

---

### 🔒 7. **Error Handling**

* Are exceptions, invalid input, and error cases handled gracefully?
* Is the system robust and resilient to failures?

---

### 📊 8. **Database Design (if applicable)**

* If the problem involves data persistence, how well is your schema designed?
* Do you use normalization, proper keys, and indexes?

---

### ⏱️ 9. **Time Management**

* Did you build a working MVP (minimum viable product) within the given time?
* Are the core use cases prioritized first before the bonus ones?

---

### 🧩 10. **Bonus: Feature Extensibility**

* Have you implemented bonus features (if any)?
* Is your code structured in a way that allows easy feature addition?

---

### 💡 Example: If the question is “Design a Parking Lot System”

A top submission would:

* Follow SOLID design principles
* Separate responsibilities (e.g., `ParkingLot`, `Vehicle`, `Slot`, `TicketingSystem`)
* Include unit tests
* Handle edge cases like full parking or invalid vehicle types
* Possibly include extensibility like dynamic pricing, levels, or entry/exit gates

---
## Which other companies and hackathons use machine coding round ??
Great question! The **machine coding round** is becoming increasingly common, especially for **backend-heavy roles**, **system design-oriented positions**, and **product-based companies** that want to test practical coding and design skills under time pressure.

Here’s a list of **companies and hackathons** that are known to use **machine coding rounds**:

---

### 🚀 **Top Product-Based Companies Using Machine Coding Rounds**

| Company               | Typical Round Focus                                      |
| --------------------- | -------------------------------------------------------- |
| **Meesho**            | Backend system design + OOP + Clean code                 |
| **Curefit (Cult)**    | OOP, modularity, scalable service (e.g., Booking system) |
| **Flipkart**          | Design a system (e.g., Rate limiter, Parking lot, Cart)  |
| **Swiggy**            | Real-world microservices (food delivery, order mgmt)     |
| **Zomato**            | System functionality, OOP, extensibility                 |
| **Dream11**           | Match simulation, scalable logic for games               |
| **Razorpay**          | Transactional systems, payment simulations               |
| **PhonePe**           | Backend-heavy machine coding                             |
| **Udaan**             | Order or delivery simulation-based questions             |
| **Atlassian**         | Complex logic + clean class design                       |
| **InMobi / Glance**   | Emphasis on modularity, testable code                    |
| **Gojek**             | Complex system flows, like queueing or booking           |
| **Juspay**            | Real-time system simulation, async code sometimes        |
| **CRED**              | Class structure, APIs, testable design                   |
| **BrowserStack**      | Design a web-scale backend service                       |
| **Hotstar / Disney+** | Event scheduling, ticketing systems, etc.                |

---

### 🏆 **Hackathons That Use Machine Coding Rounds**

These usually include **Machine Coding as an online or shortlist round**:

| Hackathon                   | Hosted by           | Round Includes                                      |
| --------------------------- | ------------------- | --------------------------------------------------- |
| **Flipkart GRiD**           | Flipkart            | Machine coding as a filtering round                 |
| **Swiggy Hunt**             | Swiggy              | System design/coding round to shortlist finalists   |
| **Juspay Hiring Challenge** | Juspay              | Pure machine coding with functional constraints     |
| **Curefit Tech Challenge**  | Curefit             | Machine coding for backend selection                |
| **Turing Cup (Turing.com)** | Turing              | Backend project in machine coding style             |
| **Dream11 CodePremier**     | Dream11             | Sports/game-based simulation machine coding         |
| **Walmart CodeHers**        | Walmart Global Tech | Machine coding + DS/Algo                            |
| **Zomato Tech Challenge**   | Zomato              | Real-life system building under constraints         |
| **ByteXL Codewars**         | Multiple partners   | System design-based machine coding for shortlisting |

---

### ✅ **What They Look for in Machine Coding**

Most companies/hackathons evaluate on:

* Functional completeness
* Object-oriented design
* Clean, readable code
* Modular and extensible structure
* Optional: API structure, if it’s a REST-based problem

---

### 🔧 **Common Machine Coding Problems**

* Design a Parking Lot
* Library Management System
* Elevator System
* Cab Booking System
* Order Management
* Food Delivery Simulation
* Snake & Ladder / Game Engine
* Splitwise / Expense Tracker
* Rate Limiter (Token Bucket/Leaky Bucket)
* Auction or Bidding System

---

Would you like:

* ✅ A prep checklist for machine coding rounds?
* 📚 A full roadmap with problems + solutions to practice?
* 🎯 Target company-wise expected machine coding questions?

## Here are some **high-quality resources** to master each **machine-coding problem** you listed, ranging from tutorials and design guides to practical video walkthroughs:

---

## 🅿️ 1. **Parking Lot System**

* Detailed OOD tutorial with UML, class design & code: *GeeksforGeeks* “Design Parking Lot using OOP” ([youtube.com][1], [geeksforgeeks.org][2])
* System design article with architecture and scalability focus: *DEV Community* “Design a parking lot system” ([dev.to][3])
* Low-level design course on *Educative.io*—great for interview prep ([educative.io][4])

---

## 📚 2. **Library Management System**

Search for standard OOP design guides (similar to parking lot). For example, “Design Library Management System using OOP” on GeeksforGeeks or Educative.

---

## 🛗 3. **Elevator System**

Check out community discussions on *LeetCode System Design* under “Design an Elevator system” ([vishalsheth4.medium.com][5]). These include diagrams and scenario handling logic.

---

## 🚖 4. **Cab Booking System**

Explore LeetCode’s “Food delivery app” system design threads—it includes routing, matching, scaling, and relevant for cab booking ([vishalsheth4.medium.com][5]).

---

## 🧾 5. **Order Management**

Look into system design threads like “Amazon Order System” or “Shopping Cart / Payment Gateway” which offer detailed architectures and class breakdowns ([vishalsheth4.medium.com][5]).

---

## 🍱 6. **Food Delivery Simulation**

Similar to food delivery system above—covered in LeetCode discussions on “Food Delivery App” low-level design ([vishalsheth4.medium.com][5]).

---

## 🎲 7. **Snake & Ladder / Game Engine**

* Video walkthrough: “Snake and Ladder | Low Level System Design | Machine Coding” (YouTube)

[Snake and Ladder Low Level Design Walkthrough](https://www.youtube.com/watch?v=zRz1GPSH50I&utm_source=chatgpt.com)

* Coding prompt with input handling guidelines: *WorkAt.tech* “Design Snake And Ladder | Machine Coding Round” ([workat.tech][6])

---

## 💸 8. **Splitwise / Expense Tracker**

Checkout LeetCode discussions tagged “System Design or Splitwise” for data modeling, APIs, and group expense flows ([vishalsheth4.medium.com][5]).

---

## ⏱️ 9. **Rate Limiter (Token Bucket/Leaky Bucket)**

Refer to GitHub lists like *TheCuteGeek/FANG-System-Design-Master-List*, which link to token bucket discussions on LeetCode ([github.com][7]).

---

## 🏆 10. **Auction or Bidding System**

Again, see *TheCuteGeek* system-design list linking to “Bidding System: System Design Interview” on LeetCode .

---

### 📘 Bonus Resources

* **GeeksforGeeks** parking lot OOP tutorial ([geeksforgeeks.org][2])
* **AlgoMonster** parking system implementation (medium complexity) ([algo.monster][8])
* **YouTube** parking lot LLD walkthrough: the "Code with Aryan" series ([youtube.com][9])

---

### 🛠️ How to Use These

1. **Read** the system design threads or tutorials to understand architecture and classes.
2. **Sketch** your own UML diagrams (classes, relationships).
3. **Write** code in your preferred language, focusing on modularity and edge-cases.
4. **Build** unit tests or simulate sample inputs (e.g. moves in Snake & Ladder).
5. **Present** your solution demonstrating OOP, clean code, and error handling.

---

If you'd like **step-by-step guides**, **approximate time estimates**, or **sample code templates**, feel free to ask!

[1]: https://www.youtube.com/watch?v=zRz1GPSH50I&utm_source=chatgpt.com "Snake and Ladder | Low Level System Design | Machine Coding"
[2]: https://www.geeksforgeeks.org/system-design/design-parking-lot-using-object-oriented-principles/?utm_source=chatgpt.com "How to Design a Parking Lot using Object-Oriented Principles?"
[3]: https://dev.to/jayaprasanna_roddam/system-design-design-a-parking-lot-system-4194?utm_source=chatgpt.com "System design: Design a parking lot system - DEV Community"
[4]: https://www.educative.io/courses/grokking-the-low-level-design-interview-using-ood-principles/getting-ready-parking-lot?utm_source=chatgpt.com "Parking Lot System Design - Educative.io"
[5]: https://vishalsheth4.medium.com/system-design-learning-6534e73257a2?utm_source=chatgpt.com "system design learning - Vishalsheth - Medium"
[6]: https://workat.tech/machine-coding/practice/snake-and-ladder-problem-zgtac9lxwntg?utm_source=chatgpt.com "Design Snake And Ladder | Machine Coding Round Questions (SDE I)"
[7]: https://github.com/TheCuteGeek/FANG-System-Design-Master-List?utm_source=chatgpt.com "TheCuteGeek/FANG-System-Design-Master-List - GitHub"
[8]: https://algo.monster/liteproblems/1603?utm_source=chatgpt.com "1603. Design Parking System - In-Depth Explanation - AlgoMonster"
[9]: https://www.youtube.com/watch?v=NU16qSPUmus&utm_source=chatgpt.com "Parking Lot Design | System Design + LLD + Full Code ... - YouTube"

