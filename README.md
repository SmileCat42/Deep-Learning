<h1 align="center"><b>Deep-Learning</b></h1>
<p align="center">
การเรียนรู้เชิงลึก
<br><br></p>

![Training](https://github.com/SmileCat42/Deep-Learning/blob/main/DL1.png)

<br><br>Training Model การฝึกฝนโมเดล Login Page<br>
![Training](https://github.com/SmileCat42/Deep-Learning/blob/main/img/img/DLTrain.png?raw=true)

<br><br>Accuracy & Adaptation ความแม่นยำและการปรับตัวให้เข้ากับชุดข้อมูล
![](https://github.com/SmileCat42/Deep-Learning/blob/main/img/img/DLacc.png)

<br><br>Augmention การเจนโครงรูปใหม่
![](https://github.com/SmileCat42/Deep-Learning/blob/main/img/img/DLGen.png)

<br><br>Predict การทำนาย
![Predict](https://github.com/SmileCat42/Deep-Learning/blob/main/img/img/DL2.png)

<br><br>

[English](#english) | [ภาษาไทย](#ภาษาไทย)

<br>

<a id="ภาษาไทย"></a>

<h1 align="center"><b>COS4312</b></h1>
<h3 align="center">Deep-Learning การเรียนรู้เชิงลึก</h3>

<br><br>
<h2 style="text-indent: 2em; text-decoration: underline;">ทำไมวิชานี้ถึงสำคัญกับฉัน</h2>
&nbsp;&nbsp;&nbsp;&nbsp;ในยุคที่ AI พัฒนาอย่างรวดเร็ว กอล์ฟมองว่าการเข้าใจ “พฤติกรรมการเรียนรู้ของโมเดล” 
เป็นทักษะที่สำคัญมาก ไม่ใช่แค่การใช้งาน แต่ต้องเข้าใจว่าทำไมโมเดลถึงตัดสินใจแบบนั้น วิชานี้ทำให้กอล์ฟได้เรียนรู้วิธีสังเกตและปรับพฤติกรรมของโมเดล 
ให้เหมาะสมกับปัญหาและชุดข้อมูล เช่น การหลีกเลี่ยง overfitting หรือการทำให้โมเดล “เข้าใจ” แทนที่จะ “จดจำ”
กอล์ฟยังได้ฝึกวิเคราะห์ผลลัพธ์ของโมเดล และปรับโครงสร้าง เช่น จำนวนชั้น (layers) และความซับซ้อน เพื่อให้ได้ performance ที่ดีที่สุด
สิ่งที่กอล์ฟได้จากวิชานี้ ไม่ใช่แค่การสร้างโมเดล แต่คือความสามารถในการ “ปรับปรุงและแก้ปัญหาโมเดล” ด้วยตัวเอง
<br>
<br>

<h2 style="text-indent: 2em; text-decoration: underline;">ทักษะและความรู้ที่ได้รับ</h2>
1. สามารถใช้คำสั่งในการตรวจสอบชุดข้อมูล เช่น จำนวนมิติ รูปแบบคำตอบ จำนวนข้อมูล ชนิดของข้อมูล เพื่อสามารถกำหนดโครงสร้างของโมเดลในการฝึกให้เหมาะสมกับชุดข้อมูล 
<br><a href="Lab1.ipynb"> LAB 1 </a>
<br>2. เข้าใจความหมายของคำว่า"มิติ"ในโลกของข้อมูลดิจิทัล สามารถดัดแปลงข้อมูลให้อยู่ในรูปโครงสร้างที่โมเดลสามารถอ่านได้ 
<br><a href="Lab2_1.ipynb"> LAB 2.1 </a>, &nbsp; <a href="Lab2_2.ipynb"> LAB 2.2 </a>
<br>3. เข้าใจกระบวนการคิดของโมเดล เช่น weight หมายถึงอะไร การคำนวณของโมเดลมีขั้นตอนอย่างไร 
<br><a href="Lab3.ipynb"> LAB 3 </a>
<br>4. ทราบถึงขั้นตอนการสร้างคอมไพรเลอร์ รวมถึงการ train หรือฝึกโมเดล ว่าต้องสังเกตุค่าอะไรบ้าง accuracy กับ loss มีความสำคัญกับการประเมินผลลัพธ์ของโมเดลอย่างไร 
<br><a href="Lab5.ipynb"> LAB 5 </a>
<br>5. สามารถแก้ไขปัญหากรณีที่โมเดล Overfitting หรือโมเดลที่เก่งเกินไป รวมถึงการเกิด Underfitting หรือโมเดลที่เล็กเกินไป ทำให้โมเดลเน้นความเข้าใจมากกว่าการจำ
<br><a href="Lab6.ipynb"> LAB 6 </a>
<br>6. ใช้เทคนิค K-Fold Cross Validation เพื่อแก้ปัญหาข้อมูล validation ไม่เพียงพอ
<br><a href="Lab7.ipynb"> LAB 7 </a>
<br>7. เข้าใจถึงกลไกในการกำหนดจำนวนชั้น จำนวน neuron รวมถึง batch อย่างไรให้เหมาะสมกับชุดข้อมูล เพื่อหลีกเลี่ยงการเกิด Over/Underfitting 
<br><a href="Lab8.ipynb"> LAB 8 </a>
<br>8. สามารถใช้งาน CNN สำหรับ image processing และเข้าใจการทำงานของ MaxPooling / Flatten   
<br><a href="Lab10.ipynb"> LAB 10 </a>
<br>9. สามารถใช้ Data Augmentation เพื่อเพิ่มความหลากหลายของข้อมูล   
<br><a href="Lab13.ipynb"> LAB 13 </a>
<br><br>

<h2 style="text-indent: 2em; text-decoration: underline;">⭐ ไฮไลท์ความสามารถที่ฉันมี</h2>
10. กอล์ฟสามารถเรียกโมเดลตัวดังที่ผ่านการเทรนอย่างหนักมาแล้ว (Pretrain) มาใช้งานกับงานของตนเองได้ โดยที่ไม่ต้องเริ่มต้นจาก 0  
<br><a href="Lab13.ipynb"> LAB 13 </a>
<br>11. กอล์ฟสามารถสร้าง วิเคราะห์ ปรับเปลี่ยน ดัดแปลงโมเดลด้วยตนเอง จากบทเรียนทั้งหมด มาประยุกต์ใช้ในการสร้างโมเดลที่ดีที่สุดด้วยตนเองได้ โดยการทำนายจากรูปภาพให้ถูกต้องมากที่สุด 
<br><a href="FshionFinal.ipynb"> LAB Final </a>

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
<br>2. เปิดเว็ปเข้าลิงค์ [Colab](https://colab.research.google.com/) อาจต้องมีการ Login gmail ก่อน
<br>3. เลือกแถบ Upload แล้วเลือกไฟล์ที่ท่านโหลดไว้
<br>4. กดปุ่ม play เพื่อรันโค้ดทีละส่วน หรือกด Run all เพื่อรันทั้งหมดอัตโนมัติ
<br><br><br><br>

<a id="english"></a>

<h2 style="text-indent: 2em; text-decoration: underline;">Why This Course Matters to Me</h2>
&nbsp;&nbsp;&nbsp;&nbsp;In an era where AI is rapidly evolving, I believe that understanding how models actually learn is a crucial skill. It is not just about using AI tools, but about understanding the reasoning behind a model’s predictions. This course helped me develop the ability to observe and adjust model behavior to better fit specific problems and datasets. I learned how to prevent issues like overfitting, and how to guide models toward true understanding rather than simple memorization. I also gained experience in analyzing model performance and improving architectures, such as tuning layers and model complexity to achieve better results. What I gained from this course goes beyond building models — it is the ability to analyze, troubleshoot, and continuously improve them in a practical and meaningful way.
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
<br>2. Open the website at [Colab](https://colab.research.google.com/) (you may need to log in with your Gmail account first)
<br>3. Go to the Upload tab and select the file you downloaded
<br>4. Click the Play button to run the code step by step, or click Run all to execute everything automatically
