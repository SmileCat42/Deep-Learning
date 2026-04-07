<h1 align="center"><b>Deep-Learning</b></h1>
<p align="center">
การเรียนรู้เชิงลึก
<br><br></p>

![Training](https://github.com/SmileCat42/Deep-Learning/blob/main/DL1.png)

<br><br>Training Model การฝึกฝนโมเดล Login Page<br>
![Training](https://github.com/SmileCat42/Deep-Learning/blob/main/img/DLTrain.png?raw=true)

<br><br>Accuracy & Adaptation ความแม่นยำและการปรับตัวให้เข้ากับชุดข้อมูล
![](https://github.com/SmileCat42/Deep-Learning/blob/main/img/DLacc.png)

<br><br>Augmention การเจนโครงรูปใหม่
![](https://github.com/SmileCat42/Deep-Learning/blob/main/img/DLGen.png)

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
&nbsp;&nbsp;&nbsp;&nbsp;เป็นวิชาที่เรียนรู้เกี่ยวกับพฤติกรรมการเรียนรู้ของโมเดล ซึ่งผู้พัฒนาต้องมีทักษะในการสังเกตุและสามารถปรับเปลี่ยนพฤติกรรมการเรียนรู้ของโมเดล ให้สอดคล้องกับปัญหาหรือชุดข้อมูลที่กำลังเทรนในขณะนั้น จุดประสงค์เพื่อให้โมเดลสามารถทำนายผลลัพธ์ให้ถูกต้อง จะทำอย่างไรให้โมเดลหลีกเลี่ยงพฤติกรรมที่เรียกว่า "การจดจำ" มากกว่า "ความเข้าใจ"
ซึ่งเป็นหัวใจหลักในการเรียนรู้ รวมไปถึงการสรุปผลของโมเดล ซึ่งขั้นตอนในการดัดแปลงหรือแก้ไขโครงสร้างโมเดลนั้น จำเป็นต้องศึกษาเกี่ยวกับระบบความซับซ้อนหรือความลึกของสมองของโมเดล จึงเป็นที่มาของคำว่า การเรียนรู้เชิงลึก
<br>
<br>

<h2 style="text-indent: 2em; text-decoration: underline;">เนื้อหาที่ได้รับ</h2>
1. รู้จักคำสั่งพื้นฐานสำหรับการตรวจสอบชุดข้อมูลว่ามีลักษณะอย่างไร เช่น จำนวนมิติ รูปแบบคำตอบ จำนวนข้อมูล ชนิดของข้อมูล เพื่อสามารถกำหนดโครงสร้างของโมเดลในการเรียนรู้ให้เหมาะสม
กับข้อมูลที่นำเข้ามา <a href="Lab1.ipynb"> LAB 1 </a>
<br>2. เข้าใจความหมายของคำว่า"มิติ"ในโลกของข้อมูลดิจิทัล สามารถดัดแปลงข้อมูลให้อยู่ในรูปของเวกเตอร์หรือโครงสร้างข้อมูลที่โมเดลสามารถอ่านได้ <a href="Lab2_1.ipynb"> LAB 2.1 </a> &nbsp; <a href="Lab2_2.ipynb"> LAB 2.2 </a>
<br>3. เข้าใจแก่นหลักของ Deep Learning ว่าโครงสร้างของโมเดลมีลักษณะเป็นอย่างไร weight หมายถึงอะไร การคำนวณของโมเดลมีขั้นตอนอย่างไร <a href="Lab3.ipynb"> LAB 3 </a>
<br>4. ทราบถึงขั้นตอนการสร้างคอมไพรเลอร์ รวมถึงการ train หรือฝึกโมเดล ว่าต้องสังเกตุค่าอะไรบ้าง accuracy กับ loss มีความสำคัญกับการประเมินผลลัพธ์ของโมเดลอย่างไร <a href="Lab5.ipynb"> LAB 5 </a>
<br>5. เข้าใจปัญหาของโมเดลที่เก่งเกินไป ว่าการเกิด Overfitting หรือใช้ความจำมากกว่าความเข้าใจ รวมถึงโมเดลที่เล็กเกินไป จะเกิดการ Underfitting นั้นส่งผลต่อการทำนายอย่างไร <a href="Lab6.ipynb"> LAB 6 </a>
<br>6. สามารถแก้ไขปัญหาข้อมูล validation ไม่เพียงพอ ได้ด้วยการทำ K-fold <a href="Lab7.ipynb"> LAB 7 </a>
<br>7. เข้าใจถึงกลไกในการกำหนดจำนวนชั้น จำนวน neuron รวมถึง batch อย่างไรให้เหมาะสมกับชุดข้อมูล เพื่อหลีกเลี่ยงการเกิด Over/Underfitting <a href="Lab8.ipynb"> LAB 8 </a>
<br>8. เข้าใจหลักการทำงานของ CNN, Maxpooling และ Flatten ว่ามีกระบวนการทำงานอย่างไร ใช้งานกับรูปภาพได้ดีเยี่ยมมากกว่าแบบปกติอย่างไร  <a href="Lab10.ipynb"> LAB 10 </a>
<br>9. ทราบความหมายของ Augmention ว่าทำไมสามารถจึงเหมาะสมสำหรับการนำมาใช้ในกรณีที่ชุดข้อมูลมีน้อย สร้างความหลากหลายให้กับชุดข้อมูลอย่างไร รวมถึงกระบวนการทำงานเป็นอย่างไร  <a href="Lab13.ipynb"> LAB 13 </a>
<br>⭐10. สามารถเรียกโมเดลตัวดังที่ผ่านการเทรนอย่างหนักมาแล้ว (Pretrain) มาใช้งานกับงานของตนเองได้ โดยที่ไม่ต้องเริ่มต้นจาก 0  <a href="Lab13.ipynb"> LAB 13 </a>
<br>⭐11. สามารถสร้าง วิเคราะห์ ปรับเปลี่ยน ดัดแปลงโมเดลด้วยตนเอง จากบทเรียนก่อนๆ มาประยุกต์ใช้ในการสร้างโมเดลที่ดีที่สุดด้วยตนเองได้ โดยการทำนายจากรูปภาพให้ถูกต้องมากที่สุด <a href="FshionFinal.ipynb"> LAB Final </a>

<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">การจดบันทึก</h2>
📄<a href="Note4312.txt" target="_blank">โน้ต 4312</a>
<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">ผลการเรียนรู้</h2>
📄 <a href="DLScore4.png" target="_blank">กลางภาค</a><br>
📄 <a href="src/score/score.pdf" target="_blank">ปลายภาค</a>
<br>
<br>

<h2 style="text-indent: 2em; text-decoration: underline;">ขั้นตอนการเปิดโปรแกรม</h2>
1. ดาวน์โหลดไฟล์ LAB ที่สนใจลงเครื่องของท่าน (ปุ่ม CODE สีเขียว)
<br>2. เปิดเว็ปเข้าลิงค์ 

[Colab](https://colab.research.google.com/) อาจต้องมีการ Login gmail ก่อน
<br>3. เลือกแถบ Upload แล้วเลือกไฟล์ที่ท่านโหลดไว้
<br>4. กดปุ่ม play เพื่อรันโค้ดทีละส่วน หรือกด Run all เพื่อรันทั้งหมดอัตโนมัติ
<br><br><br><br>

<a id="english"></a>

<h2 style="text-indent: 2em; text-decoration: underline;">Project Objective</h2>
&nbsp;&nbsp;&nbsp;&nbsp;This course focuses on understanding the learning behavior of models. Developers are expected to develop strong observation skills and the ability to adjust a model’s learning behavior to align with the given problem or dataset during training.
The main objective is to enable the model to make accurate predictions. A key challenge is ensuring that the model avoids memorization and instead develops true understanding, which is the core principle of learning.
Additionally, the course covers model evaluation and improvement. Modifying or optimizing model structures requires an understanding of model complexity and depth, which forms the foundation of what is known as Deep Learning.
<br>
<br>

<h2 style="text-indent: 2em; text-decoration: underline;">Content Received</h2>
1. Understand basic commands for inspecting datasets, including dimensions, label formats, data size, and data types, in order to design appropriate model structures <a href="Lab1.ipynb"> LAB 1 </a>
<br>2. Understand the concept of “dimensions” in digital data and be able to transform data into vectors or formats that models can process <a href="Lab2_1.ipynb"> LAB 2.1 </a> &nbsp; <a href="Lab2_2.ipynb"> LAB 2.2 </a>
<br>3. Understand the fundamentals of Deep Learning, including model structure, the meaning of weights, and how computations are performed within a model <a href="Lab3.ipynb"> LAB 3 </a>
<br>4. Learn the process of model compilation and training, including how to monitor key metrics such as accuracy and loss, and understand their importance in evaluating model performance <a href="Lab5.ipynb"> LAB 5 </a>
<br>5. Understand the problems of overfitting (memorization over understanding) and underfitting (insufficient model capacity), and how they affect prediction performance <a href="Lab6.ipynb"> LAB 6 </a>
<br>6. Be able to address insufficient validation data using techniques such as K-fold cross-validation <a href="Lab7.ipynb"> LAB 7 </a>
<br>7. Understand how to appropriately configure the number of layers, neurons, and batch sizes to avoid overfitting and underfitting <a href="Lab8.ipynb"> LAB 8 </a>
<br>8. Understand how CNNs, Max Pooling, and Flatten layers work, and why they are particularly effective for image-based tasks compared to traditional methods  <a href="Lab10.ipynb"> LAB 10 </a>
<br>9. Understand data augmentation, why it is useful for small datasets, and how it increases data diversity  <a href="Lab13.ipynb"> LAB 13 </a>
<br>⭐10. Be able to utilize pre-trained models and apply them to new tasks without training from scratch  <a href="Lab13.ipynb"> LAB 13 </a>
<br>⭐11. Be able to design, analyze, and optimize models independently by applying knowledge from previous lessons, especially for image classification tasks in the final project <a href="FshionFinal.ipynb"> LAB Final </a>

<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">Note lecture</h2>
📄<a href="Note4312.txt" target="_blank">Note 4312</a>
<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">Learning Outcomes</h2>
📄 <a href="DLScore4.png" target="_blank">Midterm</a><br>
📄 <a href="src/score/score.pdf" target="_blank">Final</a>
<br>
<br>
<h2 style="text-indent: 2em; text-decoration: underline;">How to open the program</h2>
1. Download the LAB file you are interested in to your computer (click the green CODE button)
<br>2. Open the website at 

[Colab](https://colab.research.google.com/)
 (you may need to log in with your Gmail account first)
<br>3. Go to the Upload tab and select the file you downloaded
<br>4. Click the Play button to run the code step by step, or click Run all to execute everything automatically
