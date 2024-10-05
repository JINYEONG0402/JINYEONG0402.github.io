---
title: mySQL로 함수작성 후 프로시저 실행하기
date: 2023-06-02
image:
  focal_point: 'top'
---

After creating a function in MySQL, create a procedure with a CREATE PROCESSEDURE statement and run it with a CALL statement to perform the desired action

<!--more-->


The process of creating functions and executing procedures in MySQL is very simple. First, you start by connecting to the database you want. Then, you define the function to perform the necessary actions using the CREATE FUNCTION statement. This function is a structure that takes parameters, performs specific actions, and returns results.

Once you've created the function, it's time to create the procedure. A procedure is a set that allows multiple SQL statements to be executed at once using a CREATE PROCESSEDURE statement. You can also call the function here, making it easy to do the computation and data processing you need.

When the procedure is ready, it can be executed using a CALL statement. If the procedure requires an input, it must be accompanied by it. After it is finished, it will check the results and make sure they are as desired. Finally, if you don't like the result, you can modify the code of the function or procedure to get better results.
