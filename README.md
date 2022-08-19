# Robot Trajectory Planning Based on a Combination of Artificial Intelligence Algorithms

   - This work is the result of the experience of reading more than 190 sources in the field of planning and determining the path of the robot, which runs from point A to point B.
   
   -هذا العمل نتيجة خبرة قراءة اكثر من 190 مصدر في مجال تخطيط وتحديد مسار الروبوت ينطلق من نقط A الى نقطة B.
- https://linktr.ee/farkadadnan
-  By:Farkad Adnan فرقد عدنان - 
 - E-mail: farkad.hpfa95@gmail.com 
- inst : farkadadnan 
- #farkadadnan , #farkad_adnan , فرقد عدنان# 
* facebook : https://www.facebook.com/profile.php?id=100002145048612
* instagram:  https://www.instagram.com/farkadadnan/
* linkedin : https://www.linkedin.com/in/farkad-adnan-499972121/
 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>

# Abstract
Mobility is one of the most important issues in the development and design of intelligent mobile robots to achieve a specific goal. To navigate locally and self-plan a path to reach a desired destination, neural networks are used to model complex relationships between inputs and outputs or to find patterns in data because they provide more convenient solutions than the traditional methods used previously. However, current neural network navigation methods are limited to one type of bot platform and range sensor, and usually cannot be extended to other types of bots with different range sensors without the need to change the network structures. In this paper we propose a general method for interpreting data from different types of 2D range sensors, where the sensors will be used to predict the distances between the robot and the wall in front of it and the neural network algorithm to perform the navigation task. Our approach can lead to a global mobility algorithm that can be applied to different
- يعد التنقل أحد أهم القضايا في تطوير وتصميم الروبوتات المتنقلة الذكية لتحقيق هدف محدد. للتنقل محليًا والتخطيط الذاتي لمسار للوصول إلى الوجهة المرغوبة ، تُستخدم الشبكات العصبية لنمذجة العلاقات المعقدة بين المدخلات والمخرجات أو للعثور على أنماط في البيانات لأنها توفر حلولًا أكثر ملاءمة من الطرق التقليدية المستخدمة سابقًا. ومع ذلك ، تقتصر طرق التنقل عبر الشبكة العصبية الحالية على نوع واحد من منصات الروبوت ومستشعر النطاق ، وعادة لا يمكن توسيعها لتشمل أنواعًا أخرى من الروبوتات ذات مستشعرات نطاق مختلفة دون الحاجة إلى تغيير هياكل الشبكة. نقترح في هذا البحث طريقة عامة لتفسير البيانات من أنواع مختلفة من مستشعرات النطاق ثنائي الأبعاد ، حيث سيتم استخدام المستشعرات للتنبؤ بالمسافات بين الروبوت والجدار أمامه وخوارزمية الشبكة العصبية لأداء مهمة الملاحة. يمكن أن يؤدي نهجنا إلى خوارزمية تنقل عالمية يمكن تطبيقها على مختلف
 ![rbfn](https://user-images.githubusercontent.com/35774039/185421297-d63eca29-9636-440c-818d-427a2f1966e8.png)

- Keywords: path planning, mobile robot, path partitioning, map, navigation ,Artificial Intelligence (AI), Finds, Findpath, VFH,RBF,PSO

 
##   Algorithm
• Path planning for a wheeled mobile robot in an unknown Out-Door environment using VFH RBFN "A *" D* Kalman filter GA PSO SAM algorithm.

![motion-equation](https://user-images.githubusercontent.com/35774039/185591931-f849f377-92c3-4336-815c-16ebfd730692.png)

 ![0_fRLfF7MTJ86eCg02_](https://user-images.githubusercontent.com/35774039/185592008-badd4a12-5b4f-4298-85b0-00c2a91f1ad5.png)


##  System Dynamics
![1](https://user-images.githubusercontent.com/35774039/185596046-9e49ef1b-5734-4c65-a620-ac8c48632a75.png)
- Robot path determination can be manipulated using search algorithms through which the robot will randomly walk a path through neural networks in learning computing with input and output pairs. The principle of synthesizing the dynamic model of a system is shown in the following figure. The behavior of the dynamic system depends not only on the external input but also on some state variables that represent the system memory every time which here is taken through the ultrasound algorithm. Under the system observation state, these state variables are assumed to be prior outputs of the process. The choice of the number of state inputs is sometimes determined by creating, when possible, linear plant models around the equilibrium points.
- يمكن التلاعب في تحديد مسار الروبوت باستخدام خوارزميات البحث التي من خلالها سوف يسير الروبوت بشكل عشوائي في المسار عبر الشبكات العصبية في تعلم الحوسبة باستخدام أزواج المدخلات والمخرجات. يظهر مبدأ تجميع النموذج الديناميكي للنظام في الشكل التالي. لا يعتمد سلوك النظام الديناميكي على المدخلات الخارجية فحسب ، بل يعتمد أيضًا على بعض متغيرات الحالة التي تمثل ذاكرة النظام في كل مرة يتم أخذها هنا من خلال خوارزمية الموجات فوق الصوتية. في ظل حالة مراقبة النظام ، يُفترض أن تكون متغيرات الحالة هذه مخرجات سابقة للعملية. يتم تحديد اختيار عدد مدخلات الحالة في بعض الأحيان من خلال إنشاء ، عند الإمكان ، نماذج نباتية خطية حول نقاط التوازن.
 
##  Calculation methods

 The calculation methods related to the fuzzy system are only convenient and easy to implement, so the minimum value for the fuzzy intersection, the maximum value for the fuzzy union, and the field implication for the ambiguous inclusion are determined, so that the process can be reduced as in the textbook, and the method for removing the puzzle is not difficult and easy in terms of difference, The effect is good or bad before you know it, so I chose to use the separate center of gravity method to implement it.
##   Code Description
  The code for this process is divided into four files in two parts, one for design and one for Python, main.py, gui_root.py, run.py, plot.py, which are used to read files, create interfaces and arithmetic operations (including those related to system fog and collision handling). 
  ![simpleLook@2x](https://user-images.githubusercontent.com/35774039/185595848-7ffb8a9b-4f62-470e-a353-3290eb0a66c9.jpg)

  
  
## 4-Dimensional Output Data Format

    InputA1 InputB1 InputC1 Output1
    InputA2 InputB2 InputC2 Output2
    ...
## 6-Dimensional Output Data Format

    InputA1 InputB1 InputC1 InputD1 InputE1 Output1
    InputA2 InputB2 InputC2 InputD1 InputE1 Output2
    ...
## Literature Review
Neural networks are one of the modern smart tools that are used in robot location path tracking applications. This is due to its simple structure and model as well as the abilities of global complex function approximation acquired through simple training algorithms. The neural networks used in manipulator path-tracking applications are designed and used in different control configurations some of them are listed as follows
![250px-Radial_funktion_network svg](https://user-images.githubusercontent.com/35774039/185596474-3953a116-79a2-4e98-bea4-501dc802d2ca.png)
##  	Path Planning 
  - Path mapping, as well as path mapping (also known as navigation problem or piano drive problem) is a computational problem to find a series of valid configurations that move an object from source to destination. The term is used in computational engineering, computer animation, robotics, and computer games.


- Path mapping can only be applied when the environment map is known. Only mobility robots can use optimal coverage path planning methods [90]-[93] in order to achieve systematic coverage of the entire free space. The full coverage path problem differs from the optimal path planning problem. If the goal in planning the optimal path is to find the optimal path between the initial point and the target point, then the goal of full coverage is to find the optimal path so that the robot covers the entire area. If the area is divided into a grid of cells (cell size depends on the dimensions of the robot), then the goal of optimal coverage is to visit each cell at least once, and ideally only once. This problem is also known as a street vendor problem. Once the optimum path is found, the robot can systematically traverse the space and thus be more efficient in time and energy.

- يعد تعيين المسار ، وكذلك تعيين المسار (المعروف أيضًا باسم مشكلة التنقل أو مشكلة محرك البيانو) مشكلة حسابية للعثور على سلسلة من التكوينات الصالحة التي تنقل كائنًا من المصدر إلى الوجهة. يستخدم المصطلح في الهندسة الحسابية والرسوم المتحركة الحاسوبية والروبوتات وألعاب الكمبيوتر.

- يمكن تطبيق تعيين المسار فقط عندما تكون خريطة البيئة معروفة. يمكن فقط لروبوتات التنقل استخدام طرق تخطيط مسار التغطية المثلى [90] - [93] من أجل تحقيق تغطية منهجية للمساحة الخالية بأكملها. تختلف مشكلة مسار التغطية الكاملة عن مشكلة تخطيط المسار الأمثل. إذا كان الهدف من تخطيط المسار الأمثل هو العثور على المسار الأمثل بين النقطة الأولية والنقطة المستهدفة ، فإن الهدف من التغطية الكاملة هو العثور على المسار الأمثل بحيث يغطي الروبوت المنطقة بأكملها. إذا تم تقسيم المنطقة إلى شبكة من الخلايا (يعتمد حجم الخلية على أبعاد الروبوت) ، فإن الهدف من التغطية المثلى هو زيارة كل خلية مرة واحدة على الأقل ، ومن الناحية المثالية مرة واحدة فقط. تُعرف هذه المشكلة أيضًا بمشكلة الباعة الجائلين. بمجرد العثور على المسار الأمثل ، يمكن للروبوت أن يجتاز المساحة بشكل منهجي وبالتالي يكون أكثر كفاءة في الوقت والطاقة.
![شسشس](https://user-images.githubusercontent.com/35774039/185596971-f662afd1-1582-43fa-9cdc-d0c009afeb91.jpg)

 
#   This is where the story begins- من هنا بدأت القصة 


https://user-images.githubusercontent.com/35774039/185595387-f0293b53-6615-4038-b8e1-9879d93bcba5.MOV
# the work


https://user-images.githubusercontent.com/35774039/185601336-1bb8bbc2-21f8-4168-a461-a2fcabb38529.mp4


## Reference
- [1]	 Latombe, J.C. (2010). Robot Motion Planning. Kluwer, ISBN 0-7923-9129-2, Boston.
- [2]	Bekey, G. A., Goldberg, K.Y. (2011). Neural Networks in Robotics. Kluwer Academic Publishers, ISBN 0-7923-9268-X, Boston.
- [3]	Vörös, J. (2001). Low-cost implementation of distance maps for path planning using matrix guadtrees and octrees. Robotics and Computer Integrated Manufacturing Vol. 17, No., pp. 447–459, ISSN
- [4]	Doug Alexander (2017) , Neural Networks – History and Applications, Nova Science Publishers, Inc, SKU: ISBN: 978-1-53617-188-4
- [5]	Jain, A.K., Mao, K., Mohiuddin, K.M. (2011). Artificial Neural Networks: A Tutorial. Computer29, No. 3, pp. 31–44, ISSN 0018-9162.
- [6]	Domany, E., Hemmen, J.L., Schulten, K. (1991). Models of Neural Networks. Springer Verlag, ISBN 3-540-51109-1, Berlin.
- [7]	Chohra, A., Sif, F., Talaoubrid, S. (1995). Neural Navigation Approach of an Autonomous Mobile Robot in a Partially Structured Environment. Proceedings of IAV'95, pp. 238–243, Espoo, June 12-14, Finland.
- [8]	Wang, J. (1998). Primal and Dual Neural Networks for Shortest-Path Planning. IEEE Trans. on Systems, Man and Cybernetics-Part A: Systems and Humans, Vol. 28, No. 6, pp. 864–869, ISSN 1083-441.
- [9]	Kim, C.N, Trivedi, M.M. (1998). A Neuro-Fuzzy Controller for Mobile Robot Navigation and Multirobot Convoying. IEEE Trans.on Systems, Man and Cybernetics-Part B: Cybernetics, Vol. 28, No. 6, pp. 829–840, ISSN 1083-4419.
- [10]	Hebert, M.H., Thorpe, Ch., Stentz, A. (1997). Intelligent Unamnned Grou nd Vehicles.Academic Publishers, ISBN 0-7923-9833-5, Boston.
- [11]	Uher, L., Kello, I. (1999). Ultrasound Scanning Range Finder. Proceedings of the 2nd Int. Conference. Measurement'99, pp. 232–235, ISBN 80-967402-4-5, Smolenice, April 26-29, Slovak Republic.
   - AND There are more than 190 other Reference.
+ three.js - [https://threejs.org/](https://threejs.org/)
+ FileSaver.js - [https://github.com/eligrey/FileSaver.js/](https://github.com/eligrey/FileSaver.js/)
+ Materialize - [http://materializecss.com/](http://materializecss.com/)
## Contributing

Please feel free to use it if you are interested in fixing issues and contributing directly to the code base.
 
