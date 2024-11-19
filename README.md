https://drive.google.com/file/d/1Tz_7S6dpnSEcF-fjV-W5HHvEmWxixr-w/view?usp=sharing

https://github.com/rahul-verma/genaia-x/blob/main/zint/LLMJumpstart/ex/files/requirements.pdf

```
  # MISSION
  Generate tests based on equivalence class partitioning in a situation where multiple inputs are provided together and have inter-relationships.
  
  # INPUT
  As a part of user registration on a web form, you must enter your date of birth composed of:
  1. Day as a number
  2. Month as a string e.g. January
  3. Year as a number between 1950 and 2024.
  
  The recipient logic returns Valid/Invalid date.
  
  # INSTRUCTIONS
  - **Test Generation**: Generate test cases based on equivalence class partitioning to achieve minimum coverage. 
  - Please use only this technique. Don't expand it to include boundary value analysis. In the consideration of equivalence classes, consider various types of inputs, numeric as well as non-numeric, that can be sent to the server.
  - **Verbosity**: Please keep your response terse. 
  - **Response Format for Equivalence Classes**: Respond with only the identified classes, their categorization into valid/invalid and a single phrase for the corresponding reasons of categorization. List the equivalence classes as a table. The table should have the columns: EC ID, Equivalence Class and Reason for Categorization. In the consideration of equivalence classes, consider various types of inputs, numeric as well as non-numeric, that can be sent to the server. Generate separate equivalence classes for the 3 inputs, while also considering inter-relationships e.g. Feb month can have 28 or 29 days depending on whether it is a leap year.
  - **Response Format for Tests**: Present the generated tests as a separate table in reference to the Equivalence Class IDs. The table structure should have the headers: Test ID, Day, Month, Year, Equivalence Class(es) Covered, Reason for Categorization and Expected Outcome. Don't combine more than one invalid equivalence class in a single test.
  - **Target Coverage** :From coverage perspective, target minimum coverage of equivalence classes. It means that there should be at least one test case per equivalence class.
```

