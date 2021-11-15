## Java-8-ClockDateMethod's Guide
Java 8 is the most awaited and is a major feature release of Java programming language. This project contains introduction to all the methods that were introduce under java-8 DataTime Package.This
will help you to understand easily how to use all these methods in your projects

## Table of Contents

* [Date](#Date)
  


## Date
Java 8 introduced new APIs for Date and Time to address the shortcomings of the older java.util.Date and java.util.Calendar.

```java
LocalDateTime currentTime = LocalDateTime.now();
System.out.println("Current DateTime: " + currentTime);
		
LocalDate date1 = currentTime.toLocalDate();
System.out.println("date1: " + date1);
```
