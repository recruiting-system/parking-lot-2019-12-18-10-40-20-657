# Parking lot
===========

### 需求1 

停车取车

停车场实行会员制度，已注册的用户才可以进行停车，现在假定数据库中已经有一批已注册的用户（代码模板中已经给出这些注册的用户）。
停车的时候用户需要提供用户名和密码，在和数据库的用户名密码匹配成功之后，才可以停车，停车成功后用户会得到停车票。
用户取车的时候也需要提供用户名密码和停车票，在和数据库的用户名密码匹配成功并且停车票也有效之后，才可以成功取到车。

### 需求2 

作为一个停车小弟（ParkingBoy），我能够将车顺序停放到多个停车场，并可以取出

### 需求3 

作为一个聪明的停车小弟（Smart Parking Boy），我能够将车停在空车位最多的那个停车场

### 需求4 

作为一个超级停车小弟（Super Parking Boy），我能够将车停在空置率最高的那个停车场

### 需求5 

作为停车场的经理（Parking Manager），我要管理多个停车仔，让他们停车，同时也可以自己停车

### 需求6 

作为停车场的主管（Parking Director），我希望看到一张报表，其中包括经理和每个停车仔所管理的车。
只统计角色(M:Parking Manager B:Boy P:Parking Lot) 空闲车位 已经停车位数

报表：
M 5 20
  P 2 10
  B 2 5
    P 2 5
  B 1 5
    P 0 3
    P 1 2



## 已存在代码说明

已经存在的代码主要讲解如何使用测试,我们看到HelloWorldTest下有两个测试,第一个测试演示了如何进行集成测试。
第二个测试演示了如何进行mock。
