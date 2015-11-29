## Sum to n
The sum-to-n problem can be derscired as follows:

> Define a method `sum_to_n`, which takes an array 
of integers and an additional integer, n, as arguments and return true if any two element in 	the array of integers sum to n. A empty array 	sums to 0 by definition.

The first approach i tried is to use a double for loop like in any other language i've used. The first loop to iterate through the first element, the second loop for the second element. This of course result in some ugly code.
	
	def sum_to_n? arr, n
  		for i in 0...arr.length
    		for j in i+1...arr.length
      			if arr[i] + arr[j] == n
       			 return true
      			end
    		end
  		end
  		return true if arr.empty? && n.zero?
 		return false
	end
	
Nested for loop really is not a good option for Ruby. The code above surely isn't very Rubish.

Luckily for Ruby, there is a Ruby function which is a perfect fit. The problem lies in how to pick two number from an array. Sounds like a math problem from high school. Yes, the answer is combination or permutation if to choose orderly.

	def sum_to_n? arr, n
  		return true if arr.empty? && n.zero?
  		arr.combiantion(2).include? { |a, b| a + b == n }
	end
	
For this particular problem, we can simply go over the array element by element and search whether the complement `n - element` exist of except the element itself. 


