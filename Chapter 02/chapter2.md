#print("Hello Python World!")
message = "Hello Python World!"
print(message)

message = "Hello Python Crash Course World"
print(message)


#using various case methods on the name variable
name ="ada lovelace"
print(name.title())
print(name.upper())
print(name.lower())

#inserting variable's valus in a string
first_name = "John"
last_name = "doe"
full_name = f"{first_name} {last_name}"
print(full_name)
print(f"Hello, {full_name.title()}!")   # we use "f" in the beginning to inform that this is a f-string, 
										#then use quotation marks, then write hello, then use {} to indicate the use of variable,
										# then write our variable name, then use (.)operator to apply title() method on full name var

message = f"Hello, {full_name.title()}!"
print(message)


#adding whitespaces 
print("\tPython")					# \t adds a tab
print("begins \nNOW") 				# \n adds a new line

#removing unnecessary whitespaces
space = "puppy "
print(space)
space.rstrip()  				# .rstrip() method removes extra right spaces, removes temporarily
print(space)
space = space.rstrip() 			# storing the rstrip() value in a variable permanently deletes the whitespace.
								# also storing the new space value in the same space variable, updates the value of space.

space = space.lstrip()			# lower case L ie lstrip() removes left spaces
space = space.strip()  			# strip() removes spaces from both sides


#using quotes correctly
message = "one of Python's strengths is it's diverse community"				# using double quotes to use apostrophe in the string
print(message)
message = 'python is "very" easy'											# using single quotes to use single quotes in the string
print(message)


#integers
a = 2 + 3			# + used for add
b = 3 - 2			# - used for sub
c = 2 * 3			# * used for multiply
d = 3 / 2			# / used for divide
e = 3 ** 2			# python uses ** to represent exponents
f = 2 + 3 * 4		# multiple operators are allowed
g = (2 + 3) * 4		# parenthesis are used to modify the order of operators as parenthesis are preferred first
print(a, b, c, d, e, f, g)

#float
a = 0.1 + 0.1		# float are decimal numbers that uses same operators as integers 
print(a)
b = 3 * 0.1			# sometimes we can get arbitrary no. of decimal places but python tries to be as precise as possible
print(b)


#integers and floats
a = 4/2				# when you divide any 2 no.s, even if they are integers that result in whole no., you'll always get a float 
print(a)
b = 1 +  0.2		# mixing integer and float will result in float
print(b)


#underscores in numbers
universe_age = 14_000_000_000		# long no.s can be grouped using underscores for better readability
print(universe_age) 				# no. defined using underscores, python only prints digits and not the underscores


#multiple assignments
x, y, z = 0, 0, 0 					# you need to separate the variable names and their respective values using commas
print(x,y,z)

#constants
MAX_VALUE = 1000 					# using all capital letters while defining a variable name makes it a constant
print(MAX_VALUE)

