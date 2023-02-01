# GettingStartedwithProgramminginJava11-5
Plural Course

Time && Date
  
https://www.w3schools.com/java/java_date.asp

        Class	Description - need to import
        
        LocalDate	    Represents a date (year, month, day (yyyy-MM-dd))
        LocalTime	    Represents a time (hour, minute, second and nanoseconds (HH-mm-ss-ns))
        LocalDateTime	Represents both a date and a time (yyyy-MM-dd-HH-mm-ss-ns)
        DateTimeFormatter	Formatter for displaying and parsing date-time objects
  
  
      - Time of event - instant time include the hours/ minutes/ seconds
      - Local human-friendly time - dateTime
      - Global human-friendly time - ZoneDateTime
    
e.g

       LocalDate today = LocalDate.now();
       System.out.println(today); // 2023-02-01

       DateTimeFormatter usDateFormat = DateTimeFormatter.ofPattern("MM-dd-yyyy");
       System.out.println(today.format(usDateFormat)); // 02-01-2023
   
        parse??  - 3:15 - TO BE CONTINUE
   
    
