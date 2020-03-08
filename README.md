# Your-favorite-place-with-your-favorite-people.
<strong>Intel Edge AI Scholarship Project witih OpenVino</strong>

<strong>INTRODUCTION</strong>

The project was conceived with the safety of people in mind, so that public establishments such as cafes, bars and high quality restaurants can offer a value-added service, allowing people to know who is in the establishment at any given time.

Quite often parents of teenagers want to know where their children are at a certain time, or when a person has a date in a public place such as a bar, restaurant or cafe, they want to be sure that the person they're meeting is there so they don't have an embarrassing moment.  Other times, some people just don't want to meet someone they know and want to avoid that person.

At other times, certain groups of people who frequent an establishment do not want to meet with another group of people, for example, young people do not want to go to a place at a time when most of the people there are very mature, and at other times people simply do not want to go to very crowded places.

The project consists of an application that public establishments such as restaurants, bars and cafes would offer their customers, on a voluntary basis, allowing them to make it known that they are in the establishment at a certain time and using the security cameras of the establishments, for this purpose.  If a person doesn't accept to make it known that he or she is in the place, that information will be kept confidential.

In order to avoid that the information is seen by establishments belonging to the competition, the system will generate a temporary key and the user will have to validate his entrance in the application to avoid an undue use.  

The user will have to authenticate himself and provide his data at the time of making the query in the system.

The persons entering the establishment would give authorization to register their entry and be filmed by the security cameras, and the clients of the establishments would enter an application that would allow them to see different parameters related to the public establishment, such as the number of persons in the establishment at a given time, the gender of the persons and the age range.

The application would also allow them to infer whether a specific person is inside the facility at a given time.

In this way, young adolescents could inform their parents about their location, people could attend romantic or business appointments without having to go through embarrassing times, and people could choose the best time to attend a certain public place.  

The application would also make it possible to avoid meeting unpleasant or conflicting people.

Someone could say that the application could also be used to locate someone and hurt them, but these situations will be avoided, assuming that people who have dangerous enemies or compromising situations in their lives, will certainly avoid meeting in public places.

<strong>EXPLANATION OF THE PROJECT</strong>

Every time a person wants to go to their favorite public place (bar, restaurant, café), they can access a mobile application (Android, IOS), which will allow them to obtain demographic information about the place (number of people in the place at a given time, age range of the people and even let them know if a certain person is in the establishment).

All the information will be send to a cloud database and the application will retrieve the information at the time the customer decides to authenticate (This will prevent misuse of the application).

The moment someone makes a request to the application, the edge cameras will perform inference and send the result to a cloud database and from the database to the application.

The two types of outputs of the application will be :

<strong>OUTPUT 1:</strong>
- Number of people at a given time.
- Number of female persons.
- Number of male persons.
- Age range of the people in the place in a determined moment.

<strong>OUTPUT 2:</strong>
- Determine whether a person is in the public establishment or not.

<strong>PRETRAINED MODELS USED TO BUILD THE APP:</strong>

1) High Angle Detection 
https://docs.openvinotoolkit.org/latest/_models_intel_person_detection_retail_0013_description_person_detection_retail_0013.html

2) Age & Gender Recognition
http://docs.openvinotoolkit.org/latest/_models_intel_age_gender_recognition_retail_0013_description_age_gender_recognition_retail_0013.html

3) Face detection enhanced model
https://docs.openvinotoolkit.org/latest/_models_intel_face_detection_retail_0004_description_face_detection_retail_0004.html

4) Face Reindentification
https://docs.openvinotoolkit.org/latest/_models_intel_face_reidentification_retail_0095_description_face_reidentification_retail_0095.html

<strong>THE ARTIFICIAL INTELLIGENCE TASKS THAT THE APPLICATION WILL HAVE TO PERFORM WILL BE:</strong>
- Detection.
- Classification.
- Segmentation.

<strong>COMMAND LINE PARAMETERS:</strong>
1) model -xml (Used to specify the model)
2) model -bin (Used to specify the model)
3) target -device (Used to specify if the user is going to use the web or the mobile version of the app)
4) input - type (To specify the type of image that the program is going to accept)
5) input (Path to the input)

<strong>GETTING STARTED:</strong>

1) The user (the public establishment) will have to clone the repository with the code (Not still in the repository).
2) The user (the public establishment) will have to install OpenVino in a machine with capacity to support it.
3) The final user (the customer) will have to install the app on his/her phone.

<strong>PREREQUISITES:</strong>

1) OpenVINO
2) Python 3
3) Microsoft Visual Studio

<strong>INSTALLING OF OPENVINO:</strong>

https://github.com/opencv/dldt

<strong>PROJECT WORKING IMAGES:</strong>


