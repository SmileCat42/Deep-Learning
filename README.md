<h1 align="center"><b>Deep-Learning</b></h1>
<p align="center">
การเรียนรู้เชิงลึก
<br></p>

![Training](https://github.com/SmileCat42/Deep-Learning/blob/main/DL1.png)

<br><br>Training Model การฝึกฝนโมเดล Login Page<br>
![Training](https://github.com/SmileCat42/Deep-Learning/blob/main/DLTrain.png)

<br><br>Accuracy & Adaptation ความแม่นยำและการปรับตัวให้เข้ากับชุดข้อมูล
![](https://github.com/SmileCat42/Deep-Learning/blob/main/img/DLacc.png)

<br><br>Predict การทำนาย
![Predict](https://github.com/SmileCat42/Deep-Learning/blob/main/img/DL2.png)

<br><br>

[English](#english) | [ภาษาไทย](#ภาษาไทย)

<br>

<a id="ภาษาไทย"></a>

<h1 align="center"><b>COS4312</b></h1>
<h3 align="center">Deep-Learning การเรียนรู้เชิงลึก</h3>

<br><br>
<h2 style="text-indent: 2em; text-decoration: underline;">จุดประสงค์ของวิชานี้</h2>
&nbsp;&nbsp;&nbsp;&nbsp;เป็นวิชาที่เรียนรู้เกี่ยวกับพฤติกรรมการเรียนรู้ของโมเดล ซึ่งผู้พัฒนาต้องมีทักษะในการสังเกตุและสามารถปรับเปลี่ยนพฤติกรรมการเรียนรู้ของโมเดล ให้สอดคล้อง
กับปัญหาหรือชุดข้อมูลที่กำลังเทรนในขณะนั้น จุดประสงค์เพื่อให้โมเดลสามารถทำนายผลลัพธ์ให้ถูกต้อง จะทำอย่างไรให้โมเดลหลีกเลี่ยงพฤติกรรมที่เรียกว่า "การจดจำ" มากกว่า "ความเข้าใจ"
ซึ่งเป็นหัวใจหลักในการเรียนรู้ รวมไปถึงการสรุปผลของโมเดล ซึ่งขั้นตอนในการดัดแปลงหรือแก้ไขโครงสร้างโมเดลนั้น จึงเป็นที่มาของคำว่า การเรียนรู้เชิงลึก
<br>
<br>

<h2 style="text-indent: 2em; text-decoration: underline;">เนื้อหาที่ได้รับ</h2>
1. รู้จักคำสั่งพื้นฐานสำหรับการตรวจสอบชุดข้อมูลว่ามีลักษณะอย่างไร เช่น จำนวนมิติ รูปแบบคำตอบ จำนวนข้อมูล ชนิดของข้อมูล เพื่อสามารถกำหนดโครงสร้างของโมเดลในการเรียนรู้ให้เหมาะสม
กับข้อมูลที่นำเข้ามา <a href="Lab1.ipynb"> LAB 1 </a>
<br>2. เข้าใจความหมายของคำว่า"มิติ"ในโลกของข้อมูลดิจิทัล สามารถดัดแปลงข้อมูลให้อยู่ในรูปของเวกเตอร์หรือโครงสร้างข้อมูลที่โมเดลสามารถอ่านได้ <a href="Lab2.1.ipynb"> LAB 2.1 </a> &nbsp; <a href="Lab2.2.ipynb"> LAB 2.2 </a>
<br>3. เข้าใจแก่นหลักของ Deep Learning ว่าโครงสร้างของโมเดลมีลักษณะเป็นอย่างไร weight หมายถึงอะไร การคำนวณของโมเดลมีขั้นตอนอย่างไร <a href="Lab3.ipynb"> LAB 3 </a>
<br>4. ทราบถึงขั้นตอนการสร้างคอมไพรเลอร์ รวมถึงการ train หรือฝึกโมเดล ว่าต้องสังเกตุค่าอะไรบ้าง accuracy กับ loss มีความสำคัญกับการประเมินผลลัพธ์ของโมเดลอย่างไร <a href="Lab5.ipynb"> LAB 5 </a>
<br>5. เข้าใจปัญหาของโมเดลที่เก่งเกินไป ว่าการเกิด Overfitting หรือใช้ความจำมากกว่าความเข้าใจ รวมถึงโมเดลที่เล็กเกินไป จะเกิดการ Underfitting นั้นส่งผลต่อการทำนายอย่างไร <a href="Lab6.ipynb"> LAB 6 </a>
<br>6. สามารถแก้ไขปัญหาข้อมูล validation ไม่เพียงพอ ได้ด้วยการทำ K-fold <a href="Lab7.ipynb"> LAB 7 </a>
<br>7. เข้าใจถึงกลไกในการกำหนดจำนวนชั้น จำนวน neuron รวมถึง batch อย่างไรให้เหมาะสมกับชุดข้อมูล เพื่อหลีกเลี่ยงการเกิด Over/Underfitting <a href="Lab8.ipynb"> LAB 8 </a>
<br>8. เข้าใจหลักการทำงานของ CNN, Maxpooling และ Flatten ว่ามีกระบวนการทำงานอย่างไร ใช้งานกับรูปภาพได้ดีเยี่ยมมากกว่าแบบปกติอย่างไร  <a href="Lab10.ipynb"> LAB 10 </a>
<br>9. ทราบความหมายของ Augmention ว่าทำไมสามารถจึงเหมาะสมสำหรับการนำมาใช้ในกรณีที่ชุดข้อมูลมีน้อย สร้างความหลากหลายให้กับชุดข้อมูลอย่างไร รวมถึงกระบวนการทำงานเป็นอย่างไร  <a href="Lab13.ipynb"> LAB 13 </a>
<br>10. สามารถเรียกโมเดลตัวดังที่ผ่านการเทรนอย่างหนักมาแล้ว (Pretrain) มาใช้งานกับงานของตนเองได้ โดยที่ไม่ต้องเริ่มต้นจาก 0  <a href="Lab13.ipynb"> LAB 13 </a>
<br>11. สามารถสร้าง วิเคราะห์ ปรับเปลี่ยน ดัดแปลงโมเดลด้วยตนเอง จากบทเรียนก่อนๆ มาประยุกต์ใช้ในการสร้างโมเดลที่ดีที่สุดด้วยตนเองได้ โดยการทำนายจากรูปภาพให้ถูกต้องมากที่สุด <a href="FshionFinal.ipynb"> LAB Final </a>

<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">การทำงานของอัลกอริทึม</h2>
📄<a href="src/CodeExplanation/GHarray.pdf" target="_blank">ดูรายงานผลความเข้าใจผ่านการพิมพ์ (Array)</a>
<br>📄<a href="src/CodeExplanation/GHarraylist.pdf" target="_blank">ดูรายงานผลความเข้าใจผ่านการพิมพ์ (Array List)</a>
<br><br>    **พิมพ์มือเองทั้งหมด
<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">ผลการเรียนรู้</h2>
📄 <a href="src/CodeExplanation/exam2103.pdf" target="_blank">ข้อสอบ</a><br>
📄 <a href="src/score/score.pdf" target="_blank">คะแนนทั้งระดับชั้น</a>
<br>
<br>

<h2 style="text-indent: 2em; text-decoration: underline;">ขั้นตอนการเปิดโปรแกรม</h2>
1. ติดตั้งโปรแกรม Apache Netbeans
<br>2. ดาวน์โหลดโปรเจคนี้ลงเครื่อง (ปุ่ม CODE สีเขียว)
<br>3. เปิดโปรแกรม Netbeans เลือกที่ File > Open Project เลือกไฟล์เป็นโปรเจคนี้ที่ดาวน์โหลดไว้
<br>4. สังเกตุแถบซ้ายมือจะมีชื่อไฟล์ที่โหลดมาไอคอนถ้วยกาแฟ กดคลิ็กดรอปดาวน์ลงมา กดลงมาต่อที่ Source Packages กดลงมาต่อที่ projectarray (หรือกดที่ projectarray2 เพื่อดูฉบับอาเรย์ลิส)
<br>5. คลิ๊กขวาที่ชื่อไฟล์ Login.java แล้วเลือก Run File
<br><br><br><br>

<a id="english"></a>

<h2 style="text-indent: 2em; text-decoration: underline;">Project Objective</h2>
&nbsp;&nbsp;&nbsp;&nbsp;Since data structures such as Array, Stack, Queue, and LinkedList are not highly complex, the instructor would like students to gain a true understanding of them by expressing our knowledge through programming in Apache NetBeans. This method also serves as basic practice in using program. The project applying these structures to commonly used algorithms such as insertion, deletion, and searching, among others.
<br>
<br>

<h2 style="text-indent: 2em; text-decoration: underline;">Content Received</h2>
1. Understand how an array structure works, advantages and limitations
<br>2. Learn how to access elements in array, including its constraints and the redundancy that may occur when using arrays in algorithms
<br>3. Gain experience using various algorithms, and learn to import java.util.ArrayList to understand the differences between array and ArrayList
<br>4. Enable students to analyze and choose the most appropriate algorithm to apply effectively with different types of array operations

<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">Code Explanation</h2>
📄<a href="src/CodeExplanation/GHarray.pdf" target="_blank">open report code explanation (Array)</a>
<br>📄<a href="src/CodeExplanation/GHarraylist.pdf" target="_blank">open report code explanation (Array List)</a>
<br><br>    **manually created
<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">Learning Outcomes</h2>
📄 <a href="src/CodeExplanation/exam2103.pdf" target="_blank">Exam</a><br>
📄 <a href="src/score/score.pdf" target="_blank">Score all section</a>
<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">How to open the program</h2>
1. Install Apache NetBeans IDE
<br>2. Download this project to your computer (click green CODE button)
<br>3. Open NetBeans, go to File > Open Project, and select this downloaded project
<br>4. On the left panel, you will see the project name with coffee cup icon, click dropdown arrow to expand it, then open Source Packages → projectarray (→ projectarray2 for open util.arrayList version)
<br>5. Right-click on the file Login.java and select Run File to execute the program.
