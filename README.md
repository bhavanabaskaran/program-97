# program-97
def AP(m1,m2,m3):
tot=m1+m2+m3
avg=float(tot/3)
per=float((tot/150)*100)
print(&quot;Average=%0.2f Percentage=%0.2f &quot;%(avg,per))
def main():
i=int(input(&quot;Enter sub1 marks out of 50 : &quot;))
j=int(input(&quot;Enter sub2 marks out of 50 : &quot;))
k=int(input(&quot;Enter sub3 marks out of 50 : &quot;))
AP(i,j,k)
main()
