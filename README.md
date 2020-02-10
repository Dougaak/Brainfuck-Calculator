# **Brainfuck-Calculator**
A very simple calculator written in Brainfuck.

## **Author**
**Douglas Liu** \
Github: <https://github.com/DouglasLiuGamer>

## **Description**
This is a very simple Brainfuck calculator program which supports **addition**, **subtraction**, **multiplication** and **division** on two **positive integral operants**.

**No input checking** is provided. The consequence of wrong input is undefined.

The range of all numbers used in this calculator depends on the given Brainfuck standard of the compiler or interpreter.\
The reason behind is that all numbers, including both integer operants and results, are store in one unit of the memory. For instance, given the classic Brainfuck standard whose unit of memory is 1 byte, the range will be 0-255.\
The consequences of range overflow is undefined.

## **Usage Manual**
### **Running the Calculator**
Please choose a Brainfuck compiler or interpreter to run the source code.

### **Basic steps**
1. Input the first positive integral operant.
   ```
   42
   ```
2. Input one of the operants.
   ```
   42+
   ```
3. Input the second positive integral operant.
   ```
   42+8
   ```
4. Input the equals sign and the result will be outputted after.
   ```
   42+8=50
   ```

### **Addition**
```
100+54=154
```

### **Subtraction**
Support negative result.
```
123-89=34
```
```
89-123=-34
```

### **Multiplication**
```
5*12=60
```

### **Division**
Support integral remainder.
```
30/3=10
```
```
30/9=3...3
```

## **Update Plan**
Currently there is no update plan for this Brainfuck program.

Given spare time (and maybe an extremely boring vocation), following update options may be considered:
* Essential input checking
* Larger range for result
* Comment on the source code

## **License**
This source code is unlicensed. Any user can distribute or modify it freely, although a reference to the author would be appreciated.
