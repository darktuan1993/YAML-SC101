
#### YAML SC101 ####

#### Question 1

<!--  Convert sang yaml -> keep all newlines  -->
Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
Possimus illo, corrupti aliquid aliquam debitis reprehenderit eum nesciunt pariatur, 
nulla neque vero veritatis nemo quod ut expedita consequatur, architecto ipsa laborum.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
Possimus illo, corrupti aliquid aliquam debitis reprehenderit eum nesciunt pariatur, 
nulla neque vero veritatis nemo quod ut expedita consequatur, architecto ipsa laborum.

#### Question 2

<!-- đặt tên anchors và alias admin -->
users:
    - name: alice
      age: 30
admins:
    - 

#### Question 3
<!-- đặt tên anchors và alias admin -->

demo1: 30 -> chuyển sang str
demo2: "30" -> sang int
demo3: 2023-10-28 -> sang datetime
demo4: "60.78" -> sang float
demo5: "Yes" -> sang boolean

#### Question 4
<!-- tạo 1 list people : bao gồm : name,age ( numeric), address_line_1,address_line_2 -->
bob smith              jane done
30 years old           45 years old 
London                 America
UK                     US

#### Question 5

<!-- kiểu nào trong đây là boolean -->
a. n 
b. !!boolean 'true'
c. ~
d. 'no'


#### Question 5

<!-- - sẽ có khoảng 7-8 dòng - mỗi dòng có 1 dropdown list trong đó có : string,boolean,float,mapping,sequence,leave of empty -->
"True"   ->           ???
OFF      ->           ???
boolean: !!<st> 45.2424343      ->           ???

command:
- "dgdfhgfhfh"
- "dsgdgg"
- "ggffdwrwerereee"

name: Change user password
      user:
        name: isofh
        update_password: always
        password: "{{ new_password }}"


#### Question 6

<!-- - chọn kiểu yaml khớp vs json -> ko nhớ câu hỏi lắm nhưng đại loại như kia  -->
{"demo1":["34343","434343"],"demo2":["gfgfg","fggfgf"]}
{"demo1":[34343,434343],"demo2":[gfgfg,fggfgf]}

? 
- demo1
- demo2
: 
 - 34343
 - 434343

 ? 
 - demo1
 - demo2
 : 
 - "gfgfg"
 - "fggfgf"

 <!-- - chia 2 document nhg chứa trong cùng 1 tệp yaml này nhưng phải chia theo list + sequence -->
#### Question 7
 Items:
    - name: Item1
      price: 30
      description: "alo"
    - name: Item1
      price: 30
      description: "alo"
    - name: Difference Item
      price: 30
      description: "alo"

 <!-- - còn lại mấy câu lý thuyết nhg cũng chỉ chọn đáp án 
 - câu cuối cùng là cho 1 file yaml -> trong đó có 5 lỗi yamllint, sửa lại sao cho đúng -->