EPIC1 USER ACCOUNT
Login
1. email
2. password
--------------DONE---------------------

Sign up (Diner)
1. username
2. email (取@前string作为username)
3. postcode
4. password
5. confirm password
--------------DONE---------------------

Sign up (Eatery)
1. eatery name (backend存为username)
2. password
3. comfirm password
4. address (长string)
5. postcode
6. cuisines offered (select dropdowbox - Burgers/ Fast Food/ Chiken/ Pizza/ Asian/ BBQ/ Cafe/ Vegan/ Others)
7. Email
8. Menu (file type - pdf/ image)
--------------DONE---------------------

Logout
------------DONE-------------

Profile (Diner)
0. profile image
1. username 
2. email
3. postcode
4. Reset password - 1. current password 2. new password 3. confirm password
------------DONE------------


Profile (Eatery)
0. profile image
1. eatery name (backend: == username)
2. email
3. address
4. postcode
5. cuisines offered (select dropdowbox - Burgers/ Fast Food/ Chiken/ Pizza/ Asian/ BBQ/ Cafe/ Vegan/ Others)
6. Menu (file type - pdf/ image)
7. Reset password - 1. current password 2. new password 3. confirm password
-----------DONE-------------


EPIC2 CREATE VOUCHER
Creat voucher (Eatery, must disabled for Diner)
1. Resataurant Name
2. discount 
3. voucher code
4. Period
    start: day + time
    end: day + time
5. Voucher Amount 
6. Repeatability (No repeat/ Weekly repeat)
    tuesday
Note: create voucher & create repeat voucher合并。
--------------DONE---------------------

My voucher (Eatery)
1. code
2. discount
3. available/ total (Amount)
4. check detail (link to voucher detail)
---------------DONE-------------------------

My Voucher (Diner)
A. Valid Voucher
1. restaurant_name
2. verify_code(类似于订单号，唯一的，用于提供给商家进行验证)
3. code(voucher code 商家填写的) 
4. discount
5. book_date

B. Past Voucher(使用过的voucher)
1. restaurant_name 
2. code(voucher code 商家填写的) 
3. verified_date
4. add_review(Link to add reviews accordingt to restaurant name)
---------------------------------------


EPIC3 SEARCH
Search Discount
1.


Navigate Eatery
1. Menu (img)
2. eatery name (backend: == username)
3. email
4. address
5. postcode
6. cuisines_offered
7. reviews
------------------DONE---------------------


EPIC4 BOOKING
Voucher Status(首页展示，可去掉，使用recommend替代)
1. eatery_img
2. eatery_name
3. eatery_info
4. Period
    start: day + time
    end: day + time
---------------------------------------

book voucher
1. 


EPIC5 VOUCHER VIRIFY 
Verify voucher (Eatery, must disabled for Diner)
1. verify_code
---------------------------------------

EPIC6 REVIEWS
Add Review
--------DONE---------
Read Review
--------Done---------

EPIC7 RECOMMENDATIONS






