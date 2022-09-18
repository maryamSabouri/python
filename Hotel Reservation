a11 = []
a12 = []
a13 = []
###
a21 = []
a22 = []
a23 = []
a24 = []
###
a31 = []
a32 = []
########
b11 = []
b12 = []
b13 = []
###
b21 = []
b22 = []
b23 = []
b24 = []
###
b31 = []
b32 = []
########
c11 = []
c12 = []
c13 = []
###
c21 = []
c22 = []
c23 = []
c24 = []
###
c31 = []
c32 = []
########

n = 0

def check (date,room):
    m = 0
    for i in date:
        if i in room:
            m = m+1
            return m
            break

    return m




while n < 2430:
    
    a = input ( "Please enter the room type [A, B, C] : " )
    a = a.upper()
    print ( ' -----------------------------------------------' )
    
    b = input ( "Please enter the number of beds [1, 2, 3] : " )
    print ( ' -----------------------------------------------' )
    
    p = [a,b]
    
    
    if p==['A', '1']:
        
        print ( "Reserved days: \n", " room1 = ", a11, "\n", " room2 = ", a12, "\n", " room3 = ", a13  )
        print ( ' -----------------------------------------------' )
        
        num_stay_a1 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_a1 <=0 or num_stay_a1 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_a1 > 0 and num_stay_a1 < 30:
            sum_la_1 = []
            k = 0
            while k < num_stay_a1:
                da_1 = int ( input ( " Please enter the date of your stay = " ) )
                if da_1 <=0 or da_1 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    la_1 = [da_1]
                    sum_la_1 = sum_la_1 + la_1
                    k = k + 1
            sum_la_1.sort()
                
            print ( sum_la_1 )

            s1 = check (sum_la_1,a11)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_1 )

                    for i in sum_la_1:
                        a11.append(i)
                    a11.sort()
  
                        
                    
            elif s1 != 0:
                s2 = check (sum_la_1,a12)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_1 )

                    for i in sum_la_1:
                        a12.append(i)
                    a12.sort()


                        
            if s1 != 0 and s2 != 0:
                s3 = check (sum_la_1,a13)
                if s3 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_1 )

                    for i in sum_la_1:
                        a13.append(i)
                    a13.sort()


            if s1 != 0 and s2 != 0 and s3 != 0:
                    print ( " Your selected date is reserved. Please choose another date " )
                    
        print ( ' -----------------------------------------------' )
        print ( "Reserved days: \n", " room1 = ", a11, "\n", " room2 = ", a12, "\n", " room3 = ", a13  )              
        print ( " *********************************************************" )
#/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

    if p==['A', '2']:
        
        print ( "Reserved days: \n", " room1 = ", a21, "\n", " room2 = ", a22, "\n", " room3 = ", a23, "\n", " room4 = ", a24  )
        print ( ' -----------------------------------------------' )
        
        num_stay_a2 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_a2 <=0 or num_stay_a2 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_a2 > 0 and num_stay_a2 < 30:
            sum_la_2 = []
            k = 0
            while k < num_stay_a2:
                da_2 = int ( input ( " Please enter the date of your stay = " ) )
                if da_2 <=0 or da_2 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    la_2 = [da_2]
                    sum_la_2 = sum_la_2 + la_2
                    k = k + 1
                    
            sum_la_2.sort()
            print ( sum_la_2 )

            s1 = check (sum_la_2,a21)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_2 )

                    for i in sum_la_2:
                        a21.append(i)
                    a21.sort()
  
                        
                    
            elif s1 != 0:
                s2 = check (sum_la_2,a22)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_2 )

                    for i in sum_la_2:
                        a22.append(i)
                    a22.sort()


                        
            if s1 != 0 and s2 != 0:
                s3 = check (sum_la_2,a23)
                if s3 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_2 )

                    for i in sum_la_2:
                        a23.append(i)
                    a23.sort()

            if s1 != 0 and s2 != 0 and s3 != 0:
                s4 = check (sum_la_2,a24)
                if s4 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_2 )

                    for i in sum_la_2:
                        a24.append(i)
                    a24.sort()


            if s1 != 0 and s2 != 0 and s3 != 0 and s4 != 0:
                    print ( " Your selected date is reserved. Please choose another date " )
                    
        print ( ' -----------------------------------------------' )             
        print ( "Reserved days: \n", " room1 = ", a21, "\n", " room2 = ", a22, "\n", " room3 = ", a23, "\n", " room4 = ", a24  )         
        print ( " *********************************************************" )
#/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

    if p==['A', '3']:
        
        print ( "Reserved days: \n", " room1 = ", a31, "\n", " room2 = ", a32 )
        print ( ' -----------------------------------------------' )
        
        num_stay_a3 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_a3 <=0 or num_stay_a3 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_a3 > 0 and num_stay_a3 < 30:
            sum_la_3 = []
            k = 0
            while k < num_stay_a3:
                da_3 = int ( input ( " Please enter the date of your stay = " ) )
                if da_3 <=0 or da_3 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    la_3 = [da_3]
                    sum_la_3 = sum_la_3 + la_3
                    k = k + 1
                    
            sum_la_3.sort()
            print ( sum_la_3 )

            s1 = check (sum_la_3,a31)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_3 )

                    for i in sum_la_3:
                        a31.append(i)
                    a31.sort()
   
                        
                    
            elif s1 != 0:
                s2 = check (sum_la_3,a32)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_la_3 )

                    for i in sum_la_3:
                        a32.append(i)
                    a32.sort()



            if s1 != 0 and s2 != 0:
                print ( " Your selected date is reserved. Please choose another date " )

        print ( ' -----------------------------------------------' )     
        print ( "Reserved days: \n", " room1 = ", a31, "\n", " room2 = ", a32 )
        print ( " *********************************************************" )
###############################################################################


    if p==['B', '1']:
        
        print ( "Reserved days: \n", " room1 = ", b11, "\n", " room2 = ", b12, "\n", " room3 = ", b13  )
        print ( ' -----------------------------------------------' )
        
        num_stay_b1 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_b1 <=0 or num_stay_b1 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_b1 > 0 and num_stay_b1 < 30:
            sum_lb_1 = []
            k = 0
            while k < num_stay_b1:
                db_1 = int ( input ( " Please enter the date of your stay = " ) )
                if db_1 <=0 or db_1 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    lb_1 = [db_1]
                    sum_lb_1 = sum_lb_1 + lb_1
                    k = k + 1
            sum_lb_1.sort()
                
            print ( sum_lb_1 )

            s1 = check (sum_lb_1,b11)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_1 )

                    for i in sum_lb_1:
                        b11.append(i)
                    b11.sort()
  
                        
                    
            elif s1 != 0:
                s2 = check (sum_lb_1,b12)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_1 )

                    for i in sum_lb_1:
                        b12.append(i)
                    b12.sort()


                        
            if s1 != 0 and s2 != 0:
                s3 = check (sum_lb_1,b13)
                if s3 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_1 )

                    for i in sum_lb_1:
                        b13.append(i)
                    b13.sort()


            if s1 != 0 and s2 != 0 and s3 != 0:
                    print ( " Your selected date is reserved. Please choose another date " )
                    
        print ( ' -----------------------------------------------' )
        print ( "Reserved days: \n", " room1 = ", b11, "\n", " room2 = ", b12, "\n", " room3 = ", b13  )              
        print ( " *********************************************************" )
#/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
    if p==['B', '2']:
        
        print ( "Reserved days: \n", " room1 = ", b21, "\n", " room2 = ", b22, "\n", " room3 = ", b23, "\n", " room4 = ", b24  )
        print ( ' -----------------------------------------------' )
        
        num_stay_b2 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_b2 <=0 or num_stay_b2 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_b2 > 0 and num_stay_b2 < 30:
            sum_lb_2 = []
            k = 0
            while k < num_stay_b2:
                db_2 = int ( input ( " Please enter the date of your stay = " ) )
                if db_2 <=0 or db_2 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    lb_2 = [db_2]
                    sum_lb_2 = sum_lb_2 + lb_2
                    k = k + 1
                    
            sum_lb_2.sort()
            print ( sum_lb_2 )

            s1 = check (sum_lb_2,b21)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_2 )

                    for i in sum_lb_2:
                        b21.append(i)
                    b21.sort()
  
                        
                    
            elif s1 != 0:
                s2 = check (sum_lb_2,b22)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_2 )

                    for i in sum_lb_2:
                        b22.append(i)
                    b22.sort()


                        
            if s1 != 0 and s2 != 0:
                s3 = check (sum_lb_2,b23)
                if s3 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_2 )

                    for i in sum_lb_2:
                        b23.append(i)
                    b23.sort()

            if s1 != 0 and s2 != 0 and s3 != 0:
                s4 = check (sum_lb_2,b24)
                if s4 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_2 )

                    for i in sum_lb_2:
                        b24.append(i)
                    b24.sort()


            if s1 != 0 and s2 != 0 and s3 != 0 and s4 != 0:
                    print ( " Your selected date is reserved. Please choose another date " )
                    
        print ( ' -----------------------------------------------' )             
        print ( "Reserved days: \n", " room1 = ", b21, "\n", " room2 = ", b22, "\n", " room3 = ", b23, "\n", " room4 = ", b24  )         
        print ( " *********************************************************" )
#/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

    if p==['B', '3']:
        
        print ( "Reserved days: \n", " room1 = ", b31, "\n", " room2 = ", b32 )
        print ( ' -----------------------------------------------' )
        
        num_stay_b3 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_b3 <=0 or num_stay_b3 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_b3 > 0 and num_stay_b3 < 30:
            sum_lb_3 = []
            k = 0
            while k < num_stay_b3:
                db_3 = int ( input ( " Please enter the date of your stay = " ) )
                if db_3 <=0 or db_3 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    lb_3 = [db_3]
                    sum_lb_3 = sum_lb_3 + lb_3
                    k = k + 1
                    
            sum_lb_3.sort()
            print ( sum_lb_3 )

            s1 = check (sum_lb_3,b31)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_3 )

                    for i in sum_lb_3:
                        b31.append(i)
                    b31.sort()
   
                        
                    
            elif s1 != 0:
                s2 = check (sum_lb_3,b32)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lb_3 )

                    for i in sum_lb_3:
                        b32.append(i)
                    b32.sort()



            if s1 != 0 and s2 != 0:
                print ( " Your selected date is reserved. Please choose another date " )

        print ( ' -----------------------------------------------' )     
        print ( "Reserved days: \n", " room1 = ", b31, "\n", " room2 = ", b32 )
        print ( " *********************************************************" )
###############################################################################
    if p==['C', '1']:
        
        print ( "Reserved days: \n", " room1 = ", c11, "\n", " room2 = ", c12, "\n", " room3 = ", c13  )
        print ( ' -----------------------------------------------' )
        
        num_stay_c1 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_c1 <=0 or num_stay_c1 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_c1 > 0 and num_stay_c1 < 30:
            sum_lc_1 = []
            k = 0
            while k < num_stay_c1:
                dc_1 = int ( input ( " Please enter the date of your stay = " ) )
                if dc_1 <=0 or dc_1 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    lc_1 = [dc_1]
                    sum_lc_1 = sum_lc_1 + lc_1
                    k = k + 1
            sum_lc_1.sort()
                
            print ( sum_lc_1 )

            s1 = check (sum_lc_1,c11)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_1 )

                    for i in sum_lc_1:
                        c11.append(i)
                    c11.sort()
  
                        
                    
            elif s1 != 0:
                s2 = check (sum_lc_1,c12)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_1 )

                    for i in sum_lc_1:
                        c12.append(i)
                    c12.sort()


                        
            if s1 != 0 and s2 != 0:
                s3 = check (sum_lc_1,c13)
                if s3 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_1 )

                    for i in sum_lc_1:
                        c13.append(i)
                    c13.sort()


            if s1 != 0 and s2 != 0 and s3 != 0:
                    print ( " Your selected date is reserved. Please choose another date " )
                    
        print ( ' -----------------------------------------------' )
        print ( "Reserved days: \n", " room1 = ", c11, "\n", " room2 = ", c12, "\n", " room3 = ", c13  )              
        print ( " *********************************************************" )
#/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

    if p==['C', '2']:
        
        print ( "Reserved days: \n", " room1 = ", c21, "\n", " room2 = ", c22, "\n", " room3 = ", c23, "\n", " room4 = ", c24  )
        print ( ' -----------------------------------------------' )
        
        num_stay_c2 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_c2 <=0 or num_stay_c2 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_c2 > 0 and num_stay_c2 < 30:
            sum_lc_2 = []
            k = 0
            while k < num_stay_c2:
                dc_2 = int ( input ( " Please enter the date of your stay = " ) )
                if dc_2 <=0 or dc_2 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    lc_2 = [dc_2]
                    sum_lc_2 = sum_lc_2 + lc_2
                    k = k + 1
                    
            sum_lc_2.sort()
            print ( sum_lc_2 )

            s1 = check (sum_lc_2,c21)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_2 )

                    for i in sum_lc_2:
                        c21.append(i)
                    c21.sort()
  
                        
                    
            elif s1 != 0:
                s2 = check (sum_lc_2,c22)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_2 )

                    for i in sum_lc_2:
                        c22.append(i)
                    c22.sort()


                        
            if s1 != 0 and s2 != 0:
                s3 = check (sum_lc_2,c23)
                if s3 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_2 )

                    for i in sum_lc_2:
                        c23.append(i)
                    c23.sort()

            if s1 != 0 and s2 != 0 and s3 != 0:
                s4 = check (sum_lc_2,c24)
                if s4 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_2 )

                    for i in sum_lc_2:
                        c24.append(i)
                    c24.sort()


            if s1 != 0 and s2 != 0 and s3 != 0 and s4 != 0:
                    print ( " Your selected date is reserved. Please choose another date " )
                    
        print ( ' -----------------------------------------------' )             
        print ( "Reserved days: \n", " room1 = ", c21, "\n", " room2 = ", c22, "\n", " room3 = ", c23, "\n", " room4 = ", c24  )         
        print ( " *********************************************************" )
#/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

    if p==['C', '3']:
        
        print ( "Reserved days: \n", " room1 = ", c31, "\n", " room2 = ", c32 )
        print ( ' -----------------------------------------------' )
        
        num_stay_c3 = int ( input ( " Please enter the number of nights you are staying = " ) )
        print ( ' -----------------------------------------------' )
        
        if num_stay_c3 <=0 or num_stay_c3 > 30:
            print ( " Please try again " )
            continue
              
        elif num_stay_c3 > 0 and num_stay_c3 < 30:
            sum_lc_3 = []
            k = 0
            while k < num_stay_c3:
                dc_3 = int ( input ( " Please enter the date of your stay = " ) )
                if dc_3 <=0 or dc_3 > 30:
                    print ( " Please try again " )
                    continue
                else:                                         
                    print ( ' -----------------------------------------------' )
                    lc_3 = [dc_3]
                    sum_lc_3 = sum_lc_3 + lc_3
                    k = k + 1
                    
            sum_lc_3.sort()
            print ( sum_lc_3 )

            s1 = check (sum_lc_3,c31)
            
            if s1 == 0:
            
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_3 )

                    for i in sum_lc_3:
                        c31.append(i)
                    c31.sort()
   
                        
                    
            elif s1 != 0:
                s2 = check (sum_lc_3,c32)
                if s2 == 0:
                    print ( " Please enter your information " )
                    fname = input ( " Your first name : " )
                    lname = input ( " Your last name : " )
                    print ( ' -----------------------------------------------' )
                    print ( fname, lname, sum_lc_3 )

                    for i in sum_lc_3:
                        c32.append(i)
                    c32.sort()



            if s1 != 0 and s2 != 0:
                print ( " Your selected date is reserved. Please choose another date " )

        print ( ' -----------------------------------------------' )     
        print ( "Reserved days: \n", " room1 = ", c31, "\n", " room2 = ", c32 )
        print ( " *********************************************************" )
###############################################################################
