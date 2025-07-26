# Advanced Java Core: Transaction System

## Overview

This is a Java project which use CLI. You can see your transaction story and your finance in special menu.
Project was my learning project at SkillBox. In that project I used: OOP, arrays and work with data.

---

## Technology 

- OpenJDK24
- Library: Scanner
- IDE: IntelliJ IDEA 

---

## Feature
- Add income and expense transactions
- Display total balance, income, and expenses
- Show last 5 transactions
- Data stored in memory using an array
- Console-based navigation using Enums

---

## Project architecture
```
src/
└── java_string_and_dates/
├── Main.java 
│
└── explotation/
│  ├── Acceleration.java 
│  ├── Breakbale.java
│  ├── Cargo.java 
│  ├── Refuelled.java
│  └── Viability.java 
│
└── services/
│ └── Competition.java
└── technique/
  ├── Bike.java 
  ├── Car.java
  ├── Motorcyle.java 
  └─── Vehicle.java
```
### Description
```
- Main.java                                 #Entery point
- Package explotation                       # Store interface classes
- Competition 
  - public Vehicle race(Vehicle[] vehicles) # defines winner
- techinque/Vehicle.java                    # abstract class 
  - Bike, Car, Motorcycle                   # class heirs
```
---

## How to Run

To run the project locally:

```
git clone https://github.com/mihaidaniel-it/Racing.git

cd java_core_advanced     

javac Main.java

java Main
```
---

## Future Improvements
- Add unit tests with JUnit
- Add function with which user can add his car

---


## Author

- **Developed:** Mihai Daniel
- **Email:** [mihaidaniel.it@gmail.com](mailto:mihaidaniel.it@gmail.com)
