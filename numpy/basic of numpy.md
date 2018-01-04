# basic of numpy.array

    import numpy
    numpy.__version__   #View version number

    import numpy as np
    np.__version__      #View version number


# Features of Python List

    L = [ i for i in range(10) ]
OUT: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

    L[5] = "Machine Learning"
OUT: [0, 1, 2, 3, 4, 'Maching learning', 6, 7, 8, 9]

    #Python List is a very smart and non-restrictive type of list
    #But inefficiency
    
# Features of Python array
    import array 
    l = array.array( 'i' , [ i for i in range(10) ] )
    
    l[5] = "maching learning" #wrong statement
    #Although python array provides array of limited types
    #But Python array doesn't think of these array as vectors
    

    import numpy as np
    nparr = np.array([ i for i in range(10) ])  #initialize the array of numpy by initialization list
    
    nparr[5] = 100 #Reference element by index
    
    nparr.dtype   #Get the type of this array
    
    
    
    
