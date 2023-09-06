# AI-ANIMALS-MONITOR

AI Solution
The technologies of the Fourth Industrial Revolution (4IR), including Artificial Intelligence, Augmented Reality, Robotics, and 3-D printing, are rapidly transforming the manner in which individuals generate, share, and distribute value. In response to this transformative shift, we have taken the initiative to develop an Artificial Intelligence system known as Smart-Shepherd for the Vaal Community. It's important to note that 4IR is not merely a forecast of the future; it represents a compelling call to action. It presents a vision for the development and governance of technologies in a way that promotes a more empowering, collaborative, and sustainable framework for social and economic progress. The Smart-Shepherd system has been designed to assist in the detection and monitoring of livestock, ensuring their well-being and safety.
The Machine will perform the following tasks:
Identifying various objects, such as differentiating between types of animals and humans, while also ensuring that animals pose no threat to each other is a primary function of this robot. It's important to emphasize that the robot's intention is not to supplant human shepherds but rather to assist and collaborate with them in the responsible management and well-being of livestock.

Problem definition
Rhinos and other animals are being killed at an alarming rate, and despite the statistics, there has been no solution to this pressing issue. After conducting research in our community, we found that shepherds are just as afraid of omnivores as they are of carnivores. Therefore, it's crucial to have a robot that can take care of livestock.

While human shepherds are doing a great job, they sometimes fall sick and are unable to work in extreme weather conditions. A shepherd robot would be very useful on farms as it can easily interact with livestock and understand how animals communicate with each other. Additionally, this robot can regulate water consumption, ensuring that flocks do not consume excessive amounts of water since it will be easily maintained. 

Benefits of our solution
The following are some potential uses of technology in the agriculture industry: 
- Detecting diseases in animals 
- Counting livestock 
- Identifying misplaced livestock 
- Reducing livestock poaching 
- Ensuring the safety of human workers 
- Detecting weather patterns 
- Creating job opportunities for IT specialists 
- Reducing the risk of sickness and fatigue among workers
Type of intelligence

Our robot comprises of Linguistic and spatial intelligence, which involves the capacity to use language to accomplish the goal of detecting livestock’s. 
Machine learning:
It is worth noting that the semi-supervised learning approach can be highly effective for robots, as it provides the ability to compare datasets, reinforce mutual observations, and correct any errors or over-generation. Ultimately, this can help the humanoid to adapt and balance strategies in a more efficient manner.
Learning Approaches:
Below is a list of some important concepts that we will be using in our system:
- Kinematics: This will help our system understand the motion of objects in the body.
- Bayesian Models: This involves formulating subjective probabilities to express existing information, carefully modelling data structure, and allowing a utility function to express how the value of each alternative decision is affected.
- Support Vector Machines: This is a type of supervised machine learning that will help us analyze data for classification and regression analysis.
- Unsupervised K-Means Clustering: We will be using this to group animals into distinct categories based on their similarities and differences.


Data:
Data Wrangling:
Firstly, we are going to try and explore the data to check for missing values/erroneous 
Entries and comment on redundant features and add additional ones, if needed.
	Data types
	No null values
	Imbalanced classes of predicted variable
	Transform variables into binary 
Exploring the Data:
	Explore the distinctive features of the data
	Determine how good a feature it is for prediction
Baseline Modelling:
We are going to start modelling to learn more above our variables! For this first run we are going to use ALL our non-categorical variables.

We used following list of classifiers used to predict the model accuracy:
	Logistic Regression
	Random Forest
	Support Vector Classifier
	Class Misbalancing
	Decision Tree
 


Natural Language Processing:
NLP will be used so that it can engage carefully with the humans. We will teach it to understand the language we use to communicate by training it. The collected words, phrase or sentences will be analysed using lexical analysis. Reason for choosing lexical analysis that It will help identify and analyse the structure of words, there after there will be a division of chunk of text into paragraphs, words, phrase and sentences, then they will be documented by matching similar document of texts, content indexing and content summarization
The Google voice recognition API will be implemented for this model. Speech recognition makes communication possible between humans and computers by detecting changes in the sequence of words that make up a written text, which may then be processed and responded to spoken commands. Google speech recognition already has in-built steps used to getting text from users, decoding it, structuring it, and transforming it so that it can be understood by the machine, therefore, we do not need to worry about our model not recognizing short phrases, vocabularies, and long phrases. Limited factors would be the background sounds, but they can be avoided by limiting background noise when we interact with the machine.

Deep Learning:
Deep Learning is a branch of Machine Learning that allows machines to learn and adapt without relying on explicit instructions. This is achieved through the use of algorithms and statistical models, which analyze and draw inferences from patterns in data.

Our humanoid will use this approach to generate its own training data and improve its performance. It will capture data from close range to interpret long range sensor data and analyze rough terrain in 3D-scene analysis to identify mathematical subjects and physical science.

The machine will use sensors, cameras, and laser points to detect surroundings. A Deep Neural Network will create high-quality artistic images and separate/recombine image styles using a neural algorithm. This is because DNN is most powerful in images, and deals with pictures and faces on a daily basis.

To train the machine for object recognition, the DNN will use Convolutional Neural Networks and develop a representation of the input image. The input image is transformed into actual content compared to its detailed pixel values.

We can visualize the information from each layer of the network by reconstructing the image only from the feature maps in that layer. Higher layers in the network will capture high-level content in terms of objects and their arrangement in the input image.To obtain a representation of the style of input image, we use a feature designed to capture texture information, this feature space is built on top of this filter responses in each layer of the network. It consists of the correlations between different filter responses over the spatial extent of the feature maps by including the filter of multiple layers.
Finally, we obtain multi-scale representation of the input image, which captures its texture information but not global arrangement.
References

1.	Jeju Media. (Year not provided). "5 Benefits of Bringing Robots in the Agricultural Sector." [Online] Available at: https://www.jejumedia.com/5-benefits-of-bringing-robots-in-the-agricultural-sector/ (Accessed: September 5, 2023).
2.	Britannica. (Year not provided). "The Fourth Industrial Revolution." [Online] Available at: http://www.britannica.com/topic/The-fourth-Industrial-Revolution2119734 (Accessed: September 12, 2023).
3.	Unknown Author. (Year not provided). "How to Build a Neural Network for Voice Classification." [Online] Available at: https://towardsdatascience.com/how-to-build-a-neural-network-for-voiceclassification-5e2810fe1efa (Accessed: August 28, 2023).
4.	Grinnell, R. &. & Unrau, Y., 2008. Social Work Research and Evaluation: Foundations of Evidence-based Practice. New York: Oxford University Press.
5.	Ha, G. & Ngo, T.C.T., 2021. Challenges in learning listening comprehension via Microsoft Teams among English majors at Van Lang University. International Journal of TESOL & Education, Volume 1(3), pp. 42-175.
6.	Harris, J., Jones, M.L., Bailey, G.K. & Westbrook, R.F., 2000. Contextual control over conditioned responding in an extinction paradigm. Journal of Experimental Psychology: Animal Behavior Processes, Volume 26(2), p. 74.
7.	Johannes , K., Daniela , . J. J.-B. & Glutsch, N., 2020. Adapting to online teaching during COVID-19 school closure: teacher education and teacher competence effects among early career teachers in Germany. European Journal of Teacher Education 43:4, Volume 43:4, pp. 608-622.
8.	Keerio, M.U., et al., 2022. Evaluating Students’ Perceptions of Microsoft Teams for Online Academics Improvement. Pakistan Journal of Engineering and Technology, Volume 5(1), pp. 56-67

