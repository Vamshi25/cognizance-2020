* Pseudocode to find whether number is Armstrong Number or not

READ number

assign n=number

assign sum=0

WHILE n>=0

           remainder=n%10
           sum=sum+(n%10)*(n%10)*(n%10)
           n=n/10

END WHILE

IF sum=number

    print armstrong number

ELSE

    PRINT not an armstrong number
    
END IF 

end procedure




