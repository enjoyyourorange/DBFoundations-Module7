
Introduction
Assignment # 7: Functions
Functions can be baked into the RDMS software, or you can create them yourself. The benefit of functions is that they are re-usable and it’s much quicker to reference a function that already exists than manually creating equations such as sums or averages.
User Defined Functions (UDFs)
User defined functions are handy in that they are modular in that you can alter them based on whether your dataset changes. They’re also convenient when it will be a script that you would be writing often. Say you have an employee on a PIP, rather than writing a script to see what their daily output was every weekday, you could create a function that would pull the employee’s production that day without having to write a new query.
Scalar, Inline, and Multi-Statement Functions
Scalar functions will return only a single value. Inline functions can return a set of values from a single SELECT statement, and that SELECT statement does not necessitate you structure the table that will be returned. With Multi-statement, or MSTVFs, you have to include the syntax that will construct the table your function returns. MSTVF’s also require a BEGIN and END syntax.
Summary
We discussed, generally, user defined functions and spoke to some of their variations. Functions are very convenient as they reduce code redundancy.
