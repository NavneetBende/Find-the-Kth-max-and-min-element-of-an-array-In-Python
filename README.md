Find the “Kth” max and min element of an array
prepinsta-prime


Get over 200+ Courses under One Subscription

Get Prime
Course List
mute







Get Prime

Don’t settle Learn from the Best with PrepInsta Prime Subscription












Learn from Top 1%
Get Prime
One Subscription, For Everything
The new cool way of learning and upskilling -

1
Limitless Learning
One Subscription access everything

2
Job Assurance
Get Access to PrepInsta Placement Cell

3
Top Faculty
from FAANG/IITs/TOP MNC's

Get Prime →

PrepInstaPrime
Get over 200+ course One Subscription
Courses like AI/ML, Cloud Computing, Ethical Hacking, C, C++, Java, Python, DSA (All Languages), Competitive Coding (All Languages), TCS, Infosys, Wipro, Amazon, DBMS, SQL and others.

Get Prime
Course List
Prepinsta Prime
Login/Signup to comment


Mathavan SG
k=int(input(‘enter k value’))
a=list(map(int,input().split()))
n=len(a)
def findkmax(k,a):
for i in range(n):
for j in range(0,n-1-i):
if a[j]a[j+1]:
a[j],a[j+1]=a[j+1],a[j]
print(a)
print(‘kin element’,a[k-1])

findkmax(k,a)
findkmin(k,a)
