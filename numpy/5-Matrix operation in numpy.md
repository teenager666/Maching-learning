# Matrix operation in numpy
&emsp;&emsp;#Given a vector, multiply each number in the vector by 2
            
            #a = (0,1,2)
            #a*2 = (0,2,4)

            import numpy as np
            
            n = 10
            L = np.arange(n)
            A = 2*L 
            A
            
            OUT:array([ 0,  2,  4,  6,  8, 10, 12, 14, 16, 18])
            
            
&emsp;&emsp;#Universal Functions  //通用处理函数
            
            x = np.arange(1,16).reshape(3,5)
            x
            OUT:
                array([[ 1,  2,  3,  4,  5],
                       [ 6,  7,  8,  9, 10],
                       [11, 12, 13, 14, 15]])
                       
             x+1 
             OUT:
                array([[ 2,  3,  4,  5,  6],
                       [ 7,  8,  9, 10, 11],
                       [12, 13, 14, 15, 16]])
             
             
             x / 2  ( float multiplication )
             x // 2 ( int multiplication )
             x ** 2 ( x^2 )
             x % 2 
             
             np.sin(x) 
             np.cos(x)  ..........
             
             np.exp(x)   (e^x)
             np.power(3,x)   3^x
             
             np.log(x)   loge(x)
             no.log2(x) 
             
# matrix operation
             A = np.arange(4).reshape(2,2)
             B = np.full( shape = (2,2) , fill_value = 10 )
             
             A + B   (Aij-Bij)
             A * B   (Aij*Bij)
             A/B     (Aij/Bij)
             
             A.dot(B)   (A*B)
             A.T     (A.T)
             
## vectors and matrix
             V = np.array([1,2])
             A = range(4).reshape(2,2)
             
             V+A
             OUT:
                 [0+1 , 1+2]
                 [2+1 , 3+2]
                 
## np.tile
            np.tile(V, (2,1))
            
            
            np.tile( v , (2,2) )
            OUT:
                  array([[0, 1, 0, 1],
                         [0, 1, 0, 1]])
            
            
## inverse of a matrix
            
            np.linalg.inv(A)   A^(-1)
            A.dot(np.linalg.inv(A)) = 1
            
            np.linalg.pinv(A)   //伪逆矩阵
            
            
            
            
