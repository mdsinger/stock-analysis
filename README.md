# stock-analysis
XX Overview of Project

The purpose of this project was to refactor the VBA code used to create stock analysis for 2017 and 2018. The goal was to increase the efficiency of the code and create a faster run time by improving the code.

XX Results

The original code for running the stock analysis is:

![image](https://user-images.githubusercontent.com/114033254/204890142-4602c860-3826-4f81-8906-e0fa4fe67dbf.png)
![image](https://user-images.githubusercontent.com/114033254/204890253-3a16a79c-8f0e-4246-97d6-0aa2f8fb13b9.png)
![image](https://user-images.githubusercontent.com/114033254/204890391-095af69f-65a1-4c15-9334-351725aa91de.png)

This code ran in 0.46 seconds as shown below.
![VBA_Challenge_2018](https://user-images.githubusercontent.com/114033254/204890512-e2278126-6c98-404b-a43a-74f2959abb26.png)

After refactoring the code, the analysis only took 0.015 seconds to run.  
![VBA_Challenge_refactored_2018](https://user-images.githubusercontent.com/114033254/204890776-e6a45f35-49ca-45b5-950a-b4d8dde85887.png)

Below is the refactored code:

![image](https://user-images.githubusercontent.com/114033254/204890847-fab74d3c-3caa-445b-8912-8794f99b9402.png)
![image](https://user-images.githubusercontent.com/114033254/204890903-fb8d5824-e8b4-4d3d-a544-2c01f20e6d8f.png)
![image](https://user-images.githubusercontent.com/114033254/204890976-f07d2215-3b2f-46a9-8bc0-28cf46a59f2b.png)
![image](https://user-images.githubusercontent.com/114033254/204891044-cb767b6d-5180-4828-bec7-e69b59f57da8.png)

## Summary

The advantages of refactoring code is that it was much quicker to output the analysis. Another advantage is that you are not repeating the same code over and over.
However, since the code is more difficult, it is necessary to write clear comments describing the code's intentions.

These pros and cons apply to refactoring original VBA script because it is very important to document your code very clearly when using nested if loops as they can get confusing and hard to follow without notes.









