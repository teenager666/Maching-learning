# Basic of matplotlib

        import matplotlib as mpl
        import matplotlib.pyplot as plt
        
        x = np.linspace( 0 , 10 , 1000 )
        y = np.sin(x)
        
        plt.plot(x,y)
        //get a graph of x,y
        plt.show() //display
        
        plt.plot(x,y,color = 'red',linestyle = '-.' , label = "sin(x)")   // --   -.   :  -
        plt.xlim(left,right)
        plt.ylin(up,down)
        plt.axis([left,right,up,down])
        plt.xlabel("x label")
        plt.ylabel("y label")
        plt.title("Welcome to the ML World !")
        plt.show()
        
        plt.scatter(x,y)   //绘制散点图
        plt.scatter(x,y,color = 'red',alpha = 0.1)  //透明度
        plt.show()
        
        
        
