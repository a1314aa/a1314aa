a=10
b=6
#显示菜单
print("1、汉堡: 10元；2、薯条: 6元")
#点餐
print("请点餐？")
c=float(input(＇汉堡数量:  ＇))
d=float(input(＇薯条数量:  ＇))
sum=10*c+6*d
#优惠活动: 满20减2
if(sum>=20):
        print(sum－2)
else:
        print(sum)


