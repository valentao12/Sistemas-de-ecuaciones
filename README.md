# Sistemas-de-ecuaciones
Project
% File resist . m 
% Solves for the currents i 1 i _ 2 , i _ 3 
R = [5 , 100 , 200 , 150 , 250] * 1000;' 
v1 100 ; v2 = 50 ; 
A1 = [R ( 1) + R (4) , - R (4) , 0] ; 
A2 = [-R (4) , R (2) + R (4) + R (5) , - R ( 5) ] ; 
A3 = [0 , R ( 5) , - (R ( 3) + R ( 5) ) ] ; 
A = [A1 ; A2 ; A3] ; 
b=[v1 ; 0 ; v2] ; 
current = A\b ; 
disp( ' The currents a re : ' ) 
disp (curren t )
