- symbol operations
	- \
	  collapsed:: true
		- When used between two matrices or vectors, the backslash operator solves systems of linear equations of the form \(Ax = B\). Specifically, `A\B` computes the solution to the equation \(Ax = B\).
		- If \(A\) is an \(m \times n\) matrix and \(B\) is a vector or matrix with \(m\) rows, the result \(x\) is the least-squares solution to the system.
		- This operation is also referred to as matrix left division.
		- For example:
		  ```matlab
		  A = [1 2; 3 4];
		  B = [5; 6];
		  x = A \ B;  % Solves the equation A*x = B
		  ```
	- .
	  collapsed:: true
		- In MATLAB, the dot operator (`.`) is used to perform element-wise operations on arrays or matrices. When placed before certain operators or functions, it specifies that the operation should be applied element-wise rather than matrix-wise. Here are the common usages of the dot operator in MATLAB:
		  
		  1. **Element-wise Multiplication (`.*`)**:
			- Multiplies corresponding elements of two arrays.
			- For example:
			  ```matlab
			  A = [1 2 3];
			  B = [4 5 6];
			  C = A .* B;  % C is [4 10 18]
			  ```
			  
			  2. **Element-wise Division (`./`)**:
			- Divides corresponding elements of two arrays.
			- For example:
			  ```matlab
			  A = [10 20 30];
			  B = [2 4 5];
			  C = A ./ B;  % C is [5 5 6]
			  ```
			  
			  3. **Element-wise Power (`.^`)**:
			- Raises each element of an array to the corresponding power in another array.
			- For example:
			  ```matlab
			  A = [2 3 4];
			  B = [3 2 1];
			  C = A .^ B;  % C is [8 9 4]
			  ```
			  
			  4. **Element-wise Logical Operations**:
			- Perform logical operations element-wise on arrays, such as `&` for AND, `|` for OR, and `~` for NOT.
			- For example:
			  ```matlab
			  A = [true false true];
			  B = [false true true];
			  C = A & B;  % C is [false false true]
			  ```