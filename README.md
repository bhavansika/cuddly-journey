# cuddly-journey
Numpy Basic Programs

#vector length of 10 betweeen values 5 and 50

a=np.linspace(10,49,5)
print("Length 10 with values evenly distributed between 5 and 50:")
print(a)



#multiply two array/vectors

a=np.arange(5)
print(a)
b=np.random.randint(0,10,5)
print(b)
c=np.multiply(a,b)
print(c)



#Write a NumPy program to create a 5x5 zero matrix with elements on the main diagonal equal to 1, 2, 3, 4, 5.
a=np.diag([1,2,3,4,5])
print(a)
