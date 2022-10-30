# Stock-Analysis

## Overview of Project

Steve has asked for datasets of stock information to aid him in his attempt to help his parents make wise stock choices. He wants to be able to search through thousands of stocks and have the program determine their starting price, ending price, and display their return with positive or negative results.

## Results

I was able to creat a Macro which displayed the desired information as well as showed the amount of time it took for the module to complete its task. I followed the _Challenge Starter Code_ and was able to insert the code under the comments, for example.
![Screen Shot 2022-10-30 at 1 37 09 AM](https://user-images.githubusercontent.com/115502048/198864215-65a83c74-f4b6-499e-896d-4cd13b930d46.png)
The original Macro, without any refactored took .24 seconds to produce results for stocks in 2018.
![Screen Shot 2022-10-30 at 1 40 49 AM](https://user-images.githubusercontent.com/115502048/198864377-45e99dd7-3dfc-4cc3-a342-4ac10f5f9549.png)
The new Macro with was able to accomplish the same task in .05 seconds.
![VBA_Challenge_2018](https://user-images.githubusercontent.com/115502048/198864408-5b92d6a2-9f82-4478-8b2c-09d31b226862.png)
I was also able to make running the Macro easy by creating a button and assigning the new Macro to it so all _Steve_ has to do is push a button and type in the year in order to see results. 

##Summary

The advantage of refactoring code is that you can trim down the amount of actions needed to accomplish a task so that the macro runs quicker because there is less for it to do in order to accomplish its goal. The disadvantage in my estimation is that trimming down a macro too much can lead to errors and limit its flexability for possible future use.

It is hard for me to determine the disadvantages of the original code since it was able to produce results in less than a quarter of a second. That being said I assume when it comes to creating macros the quality of results might often be measured in tenths of seconds. The final code was able to produce the same results faster and with more eye catching results due to the color coded Return columns. 
