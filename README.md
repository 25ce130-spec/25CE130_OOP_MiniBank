# 25CE130 – MiniBank Practicals

Java practicals implementing a **MiniBank** application, progressively applying core Java OOP and advanced concepts.

| Practical | Topics Covered |
|-----------|---------------|
| Practical-01 | Basic Java class structure, single-file bank simulation |
| Practical-02 | Multiple classes: `Account`, `Customer`, `MiniBank` |
| Practical-03 | Constructors, method overloading |
| Practical-04 | Enums, command parsing, validators, formatters |
| Practical-05 | Inheritance: `SavingsAccount`, `CurrentAccount`, `FixedDepositAccount` |
| Practical-06 | Interfaces, packages (`model`, `service`, `util`) |
| Practical-07 | Abstract classes and polymorphism |
| Practical-08 | Custom exceptions (`BankException`, `InsufficientFundsException`, etc.) |
| Practical-09 | Multithreading with `AccountWorker` |
| Practical-10 | Producer-consumer pattern with `TransactionBuffer` |
| Practical-11 | File I/O, serialization, report generation |
| Practical-12 | Collections Framework with `AccountStore` |
| Practical-13 | Annotations and reflection |

## How to Compile & Run

Each practical is self-contained. Navigate into the practical folder and compile:

```bash
# Example for Practical-01
cd Practical-01
javac MiniBank.java
java MiniBank
```

For practicals with packages (Practical-06 onwards), compile from the practical root:

```bash
cd Practical-06
javac -d . model/*.java service/*.java util/*.java
java service.MiniBank
```

## Student Info

- **Enrollment No:** 25CE130
- **Subject:** Java Programming (OOP)

