# FULL_SUBTRACTOR
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/351addef-f7bb-4862-9817-616a41b4c882)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/906152b8-63bc-4f70-9132-6b6b4420b22d)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/7d480140-153a-4a7e-a6d2-5323c6bd4974)

VERILOG CODE
`````
module fullsubractor(a,b,bin,d,bout);
input a,b,bin;
output d,bout;
wire w1,w2,w3;
xor (d,a,w1);
xor(w1,b,bin);
and(w2,~b,bin);
and (w3,~w1,a);
or (bout,w1,w2);
endmodule
`````

OUTPUT

![image](https://github.com/YEMANTHKUMAR/FULL_SUBTRACTOR/assets/160569469/9aea5431-d924-4222-b219-5d22975106f8)




