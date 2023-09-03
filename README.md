# Sympy Documentation 

## Gotchas and Pitfalls <br>

1.**Equal Signs (=)** <br>
	- Single Equal Sign - (**=**) Assignment operator <br>
		<pre>
		'''python 
			from sympy.abc import x,y 
			a=x-y
			print(a)'''</pre>	
			
	- Double Equal Signs - **==**  Testing Equality <br>
	
		 '''python
			(x+1)**2 - == x\*\*2+2\*x+1
			False

			
2. **Variables**

	st.code(''' python
		from sympy import Symbol
		a = Symbol('a')  # Symbol, `a`, stored as variable "a"
		b= a + 1         # an expression involving `a` stored as variable "b"
		print(b)		 # a+1
		a = 4            # "a" now points to literal integer 4, not Symbol('a')
		print(a)         # 4
		print(b)         # a+1 ( "b" is still pointing at the expression involving `a`)''')
		
	
		

 