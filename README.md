## **พื้นฐาน PHP**
    สรุปอ่านสอบปลายภาค

## บทเรียน
- [1.PHP 2021 เบื้องต้น](#1php-2021-เบื้องต้น)
- [2.Session คืออะไร](#2session-คืออะไร)
- [3.ch01 พื้นฐาน PHP](#3ch01-พื้นฐาน-php)
- [4.ch02 การจัดการข้อมูลจากฟอร์ม](#4ch02-การจัดการข้อมูลจากฟอร์ม)
- [5.ch03 MySQL](#5ch03-mysql)

# **1.PHP 2021 เบื้องต้น**
- 1.1 การใช้ HTML ร่วมกับ PHP
* print() กับ echo() : funtion ที่ใช้ในการแสดงข้อมูลผ่าน Browser

# 2.Session คืออะไร


# **3.ch01 พื้นฐาน PHP**
- **3.1 PHP คือ**

     PHP ย่อมาจาก PHP Hypertext Preprocessor
เป็นพวกภาษา scirpting language คำสั่งต่างๆ จะถูกเก็บไว้ในไฟล์ ที่เรียกว่า สคริปต์(script)
     PHP เป็นภาษา script สามารถเขียนแทรกลงไปใน HTML ได้เลย

- **3.2 ลักษณะ PHP ที่แตกต่างจากภาษาอิ่น**
    * PHP ได้รับการพัฒนาเพื่อใช้งานในการสร้างเอกสารแบบ HTML
    * PHP เป็นภาษาที่เรียกว่า **Server-side** หรือ **HTML-embedded scirpt language**
    * สามารถสร้างเอกสารแบบ Dynamic HTML มีประสทธิภาพสูงและมีลุกเล่นเยอะ

- **3.3 ภาษา Scirpt คืออะไร**
    * Script คือ ภาษาคมพิวเตอร์ที่ถูกออกแบบขึ้นโดยมนุษย์
    * วัตถุประสงค์ : เพื่อใช้ในการแปลงความคิดและแก้ไขปัญหาแบบเป็นลำดับขั้น
    * ใช้งานง่ายและไม่ซับซ้อนเหมือนโปรแกรมอื่น

- **3.4 ความแตกต่างระหว่างภาษาโปรแกรมและภาษา Script**

    ประเภท| ภาษา Scirpt |  ภาษา program 
    :----- | ----- | ----- |
    Interpreted  | ทำได้ทีละบรรทัด| ทำได้แบบรวดเดียว |
    ชั่วโมงการทำงาน| ทำงานช้ากว่าโปรแกรม| ทำงานเร็วกว่า|
    พัฒนา | เซิร์ฟเวอร์และมัลติมีเดีย| ซอฟต์แวร์ | 
    ใช้งาน | ใช้งานง่ายตัดความซับซ้อน| ซับซ้อนกว่า | 

- **3.5 การประยุกต์ใช้ภาษา Program และ ภาษา Script**
- *ภาษา Program*
    * รันใน parent program
    * ทำงานได้ดีกว่าเมื่อใช้กับแบบจำลองทางคณิตศาสตร์
    * บางภาษา เช่น Java สามารถ complie และนำไปใช้บน platform ไหนก้ได้
- *ภาษา Script*
    * คัดแยกข้อมูลที่ไม่ต้องการออกจาก dataset
    * source code ไม่ยาวและไม่เยอะ
    * ใช้สร้างคำสั่งใดคำสั่งหนึ่งในโปรแกรม

- **3.6 CGI และ Apache Module**
    - **CGI**
        * ตัวแปลชุดคำสั่งของ PHP ถือว่าเ็นแค่โปรแกรมภายนอก
    - **Apache Module**
        * ทำงานได้เร็วกว่า CGI
        * ทำงานได้มีประสิทธิภาพมากกว่า CGI
        * Apache จะเรียกมาทำงานทุกครั้งเมื่อต้องการใช้ PHP

- **3.7 รูปแบบการเขียน PHP**
- **รูปแบบ 4 รูปแบบ**
    * แบบที่ 1 การเขียนโค้ดในรูปแบบ SGML
        <details>
        <summary>Show code</summary>

        ```ruby
            <?
                คำสั่งในภาษา PHP ;
            ?>
        ```
        </details>
    * แบบที่ 2 การเขียนโค้ดเพื่อใช้ร่วมกับ XHTML หรือ XML
        <details>
        <summary>Show code</summary>

        ```ruby
            <?php
                คำสั่งในภาษา PHP ;
            ?>
        ```
        </details>
    * แบบที่ 3 การเขียนโค้ดในรูปแบบ JavaScript
        <details>
        <summary>Show code</summary>

        ```ruby
            <Script Language="php">
                คำสั่งในภาษา PHP ;
            </Script>
        ```
        </details>
    * แบบที่ 4 การเขียนโค้ดในรูปแบบ ASP

        ใช้ได้กับ php version 3.4 ขึ้นไปและจะต้องแก้ไขไฟล์ php.ini
        <details>
        <summary>Show code</summary>

        ```ruby
        <%
            คำสั่งในภาษา PHP ;
        %>
        ```
        </details>

- **3.8 เครื่องมือที่ใช้พัฒนาเว็บ**
    * XAMPP
    * PHP
    * MySQL
    * Apache

- **3.9 การใช้ Vs code**
* ติดตั้งโปรแกรม xmapp 
* ติดตั้ง Extention ของโปรแกรม
    - PHP Intelephense(จัดรูปแบบเอกสาร)
    - PHP Server(จำลองเว็บไซต์)
    - ปิดการใช้งาน(Disable): @builtin php -> PHP Language
    - PHP Intelphense
* กำหนด path ของ Windows
    - ไปที่ **System >> About >> Advanced system settings** ของ Windows
    - หน้าต่าง System Properties จะเปิดขึ้นมา **กด Environment Variables**
    - ทำการเพิ่ม path -> C:\xampp\php\

- **3.10 การแสดงผลด้วยคำสั่ง echo และ print**
    - *echo*
        * นิยมใช้กันมาก เพราะทำงานเร็ว
        * เป็นคำสั่งที่ไม่ตรวจ Error ในการส่งผลลัพธ์
            <details>
            <summary>Show code</summary>

            ```ruby
                echo('hello, world';)
                echo''Hello,PHP';
            ```
            </details>
    - *print*
        * ไม่นิยมใช้คำสั่ง print มากนัก
        * ทำงานช้ากว่าคำสั่ง echo
        * ตรวจสอบความผิดพลาดที่เกิดขึ้น
            <details>
            <summary>Show code</summary>

            ```ruby
                print('hello, world';)
                print''Hello,PHP';
            ```
            </details>

- **3.11 Comment ในภาษา PHP**
    * (#) Comment เริ่มต้นบรรทัดที่จะอธิบาย
    * (//) Comment 1 บรรทัด
    * /**/ Comment มากกว่า 1บรรทัด

- **3.12 ชนิดของข้อมูลและตัวแปร**
    * การใช้ตัวแปรใน PHP จะขึ้นต้วยเครื่องหมาย dollar($) 
    * ไม่จำเป็นต้องกำหนดแบบของข้อมูล(data type) เพราะตัวแปลภาษาจะจำแนกเองได้โดยอัตโนมัติ

    ประเภท| ใช้งาน 
    :----- | ----- | 
    Integer | จำนวนเต็มบวก,จำนวนเต็มลบ เลขฐานสิบ ฐานแปด ฐานสิบหก| 
    Float| จำนวนจริงบวกและลบ ทศนิยมและไม่ทศนิยม| 
    String | จำนวนตัวเลข และ ข้อความ|  
    Array | ข้อมูลเป็นชุด หรือ อาร์เรย์| 
    Object | ข้อมูลในลักษณะ Object เพื่อการเรียกใช้เป็น Class Object หรือ Function | 
    Type juggling | ข้อมูลในลักษณะเฉพาะหรือที่ผู้ใช้เพิ่มเข้ามา| 

- **3.13 การประกาศตัวแปร**
    * ต้องมีเครื่องหมาย dollar($) กำกับไว้หน้าตัวแปรเสมอ เช่น $name,$value
    * อักขระที่นำมากำหนดชื่อตัวแปร คือ a-z, A-Z, 0-9 หรือ _ เท่านั้น
    * ตัวแรกของตัวแปรห้ามขึ้นต้นด้วยเลข 0-9
    * อักษรพิมพ์ใหญ่ พิมพ์เล็ก ถือว่าเป็นคนละตัวกัน

 - **3.14 การกำหนดค่าให้กับตัวแปร**
    - *ข้อมูลชนิดตัวเลข (Number)*
        <details>
        <summary>Show code</summary>

        ```ruby
            $x = 123;
        ```
        </details>
           
    - *ข้อมูลชนิดสตริง (String)*
        

        ```ruby
            $phone = "080-xxxxxxx";
        ```
        </details>
           
           
    - *ข้อมูลชนิดบูลีน (ฺBoolean)*
        <details>
        <summary>Show code</summary>

        ```ruby
            $first_time = time;
            $is_valid = false;
        ```
        </details>
    - *ตัวแปรที่มีค่า null*
        <details>
        <summary>Show code</summary>

        ```ruby
            $a;
            $b= null;
        ```
        </details>
- **3.15 การตรวจสอบตัวแปรและยกเลิกตัวแปร**
    - *isset (ตัวแปร)*
        * ตรวจสอบว่ามีตัวแปรตามที่ระบุมั้ย หรือ ได้สร้างตรวจแปรนั้นขึ้นมา แล้วหรือยัง
        * หากมีจริงและไม่เป็น null จะได้ค่าเป็น true
        * หากไม่มีตัวแปรดังกล่าวหรือตัวแปรมีค่าเป็น null จะคืนค่า false
            <details>
            <summary>Show code</summary>

            ```ruby
                $x = 123;
                $a = isset($x); //$a = true มีค่าตัวแปรจริงค่าไม่เป็น null
                $y = null; //ค่าเป็น null ส่งคืนค่า fasle
                $b = isset($y); //$b = false  b ตรวจสอบการมีตัวแปรของ y
                $c = isset($z); //$c = false เพราะยังไม่ได้กําหนดตัวแปร $z
            ```
            </details>
    - *is_null (ตัวแปร)*
        * ตรวจสอบว่าตัวแปรมีค่าเป็น null มั้ย
    - *empty (ตัวแปร)*
        * ตรวจสอบว่าตัวแปรนั้นมีค่ามั้ย (PHP จะถือว่าเป็นตัวแปรที่ว่างเปล่า)
        * ตัวแปรที่มีค่า
            * มีค่าเป็น null
            * มีค่าเป็น String
            * มีค่าเป็น 0
            * มีค่าาเป็น false
        * ถ้าตัวแปรมีค่าว่างเปล่า ฟังก์ชันนี้จะได้ผลลัพธ์เป็น true
            <details>
            <summary>Show code</summary>

            ```ruby
                $x = ‘ ‘;
                $a = empty($x); //$a = true
                $y = 0;
                $b = empty($y); //$b = true
                $c = empty($z); //$c = true เพราะยังไม่ได้กําหนดตัวแปร $z

            ```
            </details>
    - *unset (ตัวแปร_1,ตัวแปร_2)*
        * ใช้ยกเลิกตัวแปรที่ระบุ เพื่อคืนทรัพยากรให้แก่ระบบ
        * เราสามารถยกเลิกตัวแปรได้หลายตัวพร้อมกัน
            <details>
            <summary>Show code</summary>

            ```ruby
                $a = 123;
                $b = ‘php’;
                unset($a, $b);
                echo $b; //เกิดข้อผิดพลาด เพราะตัวแปร $b ถูกยกเลิกแล้ว
            ```
            </details>   
- **3.16 ค่าคงที่**
    * ตัวแปรที่ใช้เก็บข้อมูลค่าใดค่าหนึ่ง ไม่สามารถเปลี่ยนค่าได้ภายหลัง
    * ค่าคงที่ไม่ต้องเขียนเครื่องหมาย $ แต่จะกำกับด้วยคำสั่ง
    
        คำสั่ง| การใช้งาน  |
        :----- | ----- | 
        define ('ชื่อค่าคงที่',ค่าที่กำหนด)  | สร้างค่าคงที่ |
        define ('ชื่อค่าคงที่')| ใช้ตรวจสอบว่ามีค่าคงที่ตามชื่อที่ระบุไว้มั้ย| 
        constant ('ชื่อค่าคงที่')| ใช้ในการอ่านค่าคงที่เพื่อนำไปใช้|

- **3.17 โอเปอเรเตอร์**
    * โอเปอเรเตอร์สำหรับการเชื่อต่อสตริง จะใช้เครื่องหมายจุด ( . ) ในการเชื่อมต่อ
        <details>
        <summary>Show code</summary>

        ```ruby
        $str = ‘Maria’.”DB”; //$str = “MariaDB”
        echo ‘มาลี’.’ ‘.’มีลา’ //มาลี มีลา
        $fname = ‘John’;
        $lname = ‘Smith’;
        echo ‘My name is ‘.$fname.’ ‘.$lname; //My name is John Smith
        echo 1 . 2 . 3; //123 ห้ามเขียนติดกัน จะได้เป็น 1.2.3

        ```
        </details>
    * โอเปอเรเตอร์สำหรับการคำนวณ
        <details>
        <summary>Show code</summary>

        ```ruby
            1. = : กำหนดค่า เช่น $x=10;
            2. += : ค่าที่กำหนดบวกค่าเดิมตัวแปร เช่น $x=10; $x+=8; //$x=18
            3. -= : ค่าเดิมตัวแปรลบค่าที่กำหนด เช่น $x=10; $x-=8; //$x=2
            4. *= : ค่าเดิมตัวแปรคูณค่าที่กำหนด เช่น $x=10; $x*=8; //$x=80
            5. /= : หารค่าเดิมของตัวแปรด้วยค่าที่กำหนด เช่น $x=10; $x /=5; //$x=2
            6. %= : ค่าที่ระบุหารด้วยค่าของตัวแปร แต่เอาแค่ค่าที่เหลือจากการหาร เช่น $x=10; $x /=3; //$x=1
            7. **= : ยกกำลังด้วยค่าเดิมของตัวแปร เช่น $x=9; $x **=2; //$x=81
            8. .= : ใช้เชื่อมต่อ string เช่น $x = ‘PHP’; $x .= ‘/MariaDB’; //$x = ‘PHP/MariaDB’

        ```
        </details>

# **4.ch02 การจัดการข้อมูลจากฟอร์ม**
- **4.1 โครงสร้างเบื้องต้น**
    <details>
    <summary>Show Structure</summary>
        
    ```ruby
        <form แอดทริบิวต์>
            อิลิเมนต์ต่างๆ
        </form>
    ```
    </details>

- **4.2 ข้อกําหนดของ Attribute ที่สําคัญ**
    * ประเภทต่าง
        Attribute | การใช้งาน  |
        :----- | ----- | 
        method | รูปแบบในการส่งข้อมูล โโยกำหนดเป็น post หรือ get|
        action| เพจปลายทางที่จะรับข้อมูล| 
        target| เป้าหมหายการส่งข้อมูลออกไป|
    * ประเภท targrt
        ประเภท targrt | การใช้งาน  |
        :----- | -----| 
        _self| ส่งผ่านเพจปัจจุบันที่บรรจุฟอร์ม(default)|
        _blank| ส่งโดยเปิดเพจหรือเปิดแท็บใหม่| 
        _top| ส่งแบบเต็มเพจ มักใช้เมื่อฟอร์มนั้นอยู่ในเฟรม|
        <frame.>| ส่งผ่านเฟรมที่กำหนด|

- **4.3 ข้อกำหนดเบื้องต้นของ Form**
    * ถ้าส่งข้อมูลไปฝั่ง Server ควรกำหนด Attribute **method** และ **action** เสมอ
    * ถ้าไม่กำหนด Attribute method ฟอร์มจะเลือกส่งข้อมูลแบบ **get**
    * ลักษณะสำคัญของ Attribute *method=get* 
        * ข้อมูลบน Elements ของฟอร์มจะถูกแปลงให้อยู่ในรูปแบบ Qurey String แล้วแบต่อท้าย URL เพื่อส่งไปยังเพจปลายทาง
        * ข้อมูลที่แนบท้าย URL มองเห็นได้ จึงไม่เหมาะกับข้อมูลที่ต้องการความปลอดภัย
        * จำนวนอักขระ Qurey String ต้องรวมกันไม่เกิน 256 ตัว
    * ลักษณะที่สำคัญของ  Attribute *method=post*
        *  ข้อมูลบน Elements **ไม่แนบต่อท้าย URL** แบบ Qurey String จึงมีความปลอดภัยกว่า
        * สามารถส่งข้อมูลได้แบบไม่จำกัด

- **4.4 ตัวอย่างการกำหนด Attribute ของฟอร์ม**
    <details>
    <summary>Show Structure</summary>
            
    ```ruby
        <form method=“post” action=“test.php” target=“_blank”>
            ....
        </form>
        // method=post รูปแบบการส่งข้อมุลแบบ post(ส่งข้อมูลได้ไม่จำกัด ปลอดภัย)
        // action=test เพจปลายทางที่จะรับข้อมูล
        // target=_blank เป้าหมาย,ผลลัพธ์การส่งออกข้อมูล _blank(ส่งโดยเปิดเพจหรือเปิดแท็บใหม่)
    ```
    </details>

- **4.5 Elements ของฟอร์ม**
    * คำสั่ง <.INPUT Attribute.> เป็นคำสั่งในการกำหนดรูปแบบฟอร์มที่ใช้สำหรับการรับข้อมูล
        <details>
        <summary>Show Elements</summary>
            
            1.NAME : รูปแบบคำสั่ง <.INPUT NAME=Name.> , Name=ใช้กำหนดชื่อ ,Name=ชื่อไฟล์ที่ใช้เก็บข้อมูลในแต่ละรายการ
            2.SIZE : รูปแบบคำสั่ง <.INPUT SIZE=Number.> , SIZE=ใช้กำหนดขนาด , Number= ขนาดความยาวของตัวอักษรที่จะให้รับข้อมูลได้
            3.MAXLENGTH : รูปแบบคำสั่ง <.INPUT MAXLENGTH=Number.> , MAXLENGTH=ใช้กำหนดความยาวสูงสุดของข้อมูล ,Number=เลขจำนวนสูงสุดที่กำหนดให้สามารถรับข้อมูลได้
            4.VALUE : รูปแบบคำสั่ง <.INPUT VALUE=Message.> , VALUE=ใช้กำหนดค่า ,Message= ข้อความ หรือ ค่า ที่ต้องการระบุไว้ในช่องรับข้อมูล
            5.TYPE : คำสั่ง <.INPUT TYPE.> เป็นคำสั่งในการกำหนดชนิดข้อมูล
                    
        </details>
    
    * คำสั่ง <.INPUT TYPE.> เป็นคำสั่งที่ใช้ในการกำหนดชนิดข้อมูล
        
        INPUT TYPE | การใช้งาน  |
        :----- | ----- | 
        text |ช่องรับข้อความแบบบรรทัดเดียว|
        password|ช่องรับข้อมความที่เป็นรหัส| 
        checkbos| ตัวเลือกที่สามารถเลือกได้มากกว่า 1 รายการ| 
        radio|ตัวเลือกที่เลือกได้เพียง 1 รายการ| 
        file|กำหนดไฟล์ที่อัพโหลด|
        submit|ปุ่มสำหรับส่งข้อมูลจาก Form ไปยัง Server |
        reset|ปุ่มสำหรับยกเลิกข้อมูลทั้งหมดใน Form |
        hidden|ใช้สำหรับเก็บซ่อนข้อมูลที่ไม่ต้องการให้ผู้ใช้เห็น |
        image|สำหรับใช้รูปภาพเป็นปุ่มสั่งงาน|
        button|ปุ่มสั่งงานทั่วไป ส่วนใหญ่ใช่ร่วมกับ Javascript |
        number|รับข้อมูลเป็นตัวเลข |
        email|รับข้อมูลเป็นอีเมล |
        url|รับข้อมูล URL |
        date|ข้อมูลที่เป็นวันเดือนปี ในรูปแบบ:ปี-เดือน-วัน |
        datetime|ใส่วันที่และเวลา |
        month|ใส่เดือนและปี 
        color|ใส่ค่าสี |
        <.textarea.>|ช่องรับข้อความแบบหลายบรรทัด |
        <.select.>|สร้างรายตัวเลือกแบบ dropdown,list|
        
- **4.6 การอ่านข้อมูลจาก Form**
    * การอ่านข้อมูลที่ถูกส่งจากฟอร์ม
    
        method | การใช้งาน  |
        :----- | ----- | 
        $_GET ['ชื่อ'] |อ่านข้อมูลที่ถูกส่งมาด้วย method GET โดย 'ชื่อ' คือ  Attribute name ของ Elements ที่ต้องการอ่านข้อมูล  |
        $_POST ['ชื่อ']|อ่านข้อมูลด้วย method POST| 
        $_REQUEST ['ชื่อ']|อ่านข้อมูลไม่ว่าจะเป็น POST หรือ GET| 
        $_SERVER ['REQUESR_METHOD']|ตรวจสอบว่าข้อมูลถูกส่งด้วย method ใด|

    * การส่งข้อมูลแบบ **Postback**
        * การสร้างทั้งฟอร์มและส่วนสคริปต์ PHP ที่ใช้จัดการข้อมูลจากฟอร์มไว้ในเพจเดียวกัน

# 5.ch03 MySQL# Final-PHP
