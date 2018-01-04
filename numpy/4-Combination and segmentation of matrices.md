# Combination and segmentation of matrices

## Combination operation
### 1.np.concatenate
    x = np.array([1,2,3])
    y = np.array([1,2,3])
    
    #concatenate((a1, a2, ...), axis=0)
    increase row with axis = 0
    increase col with axis = 1
    
    np.concatenate([x,y])   # Pass in a list of matrices

### 2.
    np.vstack   increase row with vstack
    np.hstack   increase col with hstack
    np.vstack([a1,a2,...,an])
    np.vstack([a1,a2,...,an])
    
## segmentation operation
### 1. np.split()
      
    #np.split(ary, indices_or_sections, axis=0)
    split up-down with axis = 0
    split left-right with axis = 1

    x1 , x2 , x3 = np.split(x,[3,7])   #[x1,x2,...,xn] segmentation points
    y1 , y2 = np.split([2],axis = 1)
       

### 2.
    
    np.vsplit(arg , [x1,x2,...xn])    #split up-down with np.vsplit
    np.hsplit(arg , [y1,y2,...,yn])   #split left-right with np.hsplit
    
    
    
    
    
       
    
    
