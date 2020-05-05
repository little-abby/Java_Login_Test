## Java Sprign Login System Test 

#### Question 
Create a  Web Login system using Java Spring boot.
Including: 
- Java API server
- Login Page
- MongoDB link
---
#### Requirement

 - Create a login page with 2 fileds to input `username` and `password` and a `submit` button.
 - Compare the username and password in MongoDB. 
 - Return the msg 
   - `Login successfully, Welcome {username}!`  when success or
   -  `Login failed.` when failed 
- Write the user guide (README.MD) for build steps and features you did
- Upload to your github.

\* Any build tools is up to you (Recommend gradle / maven) 

---
#### Configuration 

##### Java
Login page url : `http://localhost:10088/login`

##### Mongo 
| Login Page  | MongoDB Setting | 
| :-------------: | :-------------: |
| hostname* | mongo |
| databse  | test  |
| collection | candidate |
| username (field) | _id |
| password (field)** | pwdHash |

\* Don't doubt, same as `localhost`, we use name as host in microservice network.

\** `SHA256` for hashing password.

---
#### Submission 
Upload to your github and set to public.
repo name : `Spring_test1_{yourname}_{date}`
