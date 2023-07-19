

1. Introduction

While applying for universities, a lot of students face difficulty in shortlisting and searching for those that correctly fit to their needs; it is a hassle given the myriad of information. To address this issue, we have created a web application called Gofickle, which uses AWS services. It takes an aggregation of 2100 university which contains numerous programs that a user can select from and analyze according to their profile to know if they are eligible for that specific program; this is done using machine learning. We are also analyzing user click stream data to understand the user preferences.
2. Implementation

The user can access the system with a simple Login/Signup page. We allow users to login/sign up with Facebook, Google, or our own custom login/signup. When the user signs up we get the username, gre/toefl, gpa, name, and address. With the given information we create a session of the user. We are also maintaining the user data in a tab called My Profile. The user can also choose to alter their information.

Once the user is authenticated, they are directed towards their dashboard called My University. In the dashboard, the user can shortlist programs of different university based on their liking and maintain a status of the program - Accepted or Interested.

Predict feature : Here the user can predict the reachability of a university based on their gpa and gre. We are using sagemaker to analyze the data received from the user and based on that we are predicting if the university is “Reachable” or “Not Reachable“ given the users profile.

Search Tab: Here we have provided the user with an ability to search for colleges based on the Major. For example, the user can search for “law” in the major search field. The result would be a list of programs that offer different set of law programs at different universities.
FeedBack : Here the user can send feedback to the developers.

DropDown: Here we have provided the user to see the privacy policy of the website. Also, this dropdown option provides the Logout option.


<img width="884" alt="Screen Shot 2021-06-09 at 12 37 51 PM" src="https://user-images.githubusercontent.com/12201059/121394609-848e0080-c91f-11eb-9e26-805e047fc00d.png">
