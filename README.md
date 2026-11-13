# Ex.-1-React-Lab-Exercise-Understanding-React-File-Structure
## Name: TAMIL MARUDHU K
## Roll no: 2305001033
## Department: CSE

## AIM
### To create a React application using Vite, understand its file structure, and develop reusable components.

## PROGRAM


### i) Student.jsx
```css
function Student() {
 return (
 <div>
 <h2>Student Details</h2>
 <p>Name: TAMIL MARUDHU K</p>
 <p>Register Number: 2305001033</p>
 <p>Department: CSE</p>
 </div>
 );
}
export default Student;
```
### ii) Course.jsx
```css
function Course() {
 return (
 <div>
 <h2>Course Details</h2>
 <p>Course: Web Technology</p>
 <p>Semester: VII</p>
 <p>Credits: 4</p>
 </div>
 );
}
export default Course;
```

### iii) Faculty.jsx
```c
function Faculty() {
 return (
 <div>
 <h2>Faculty Details</h2>
 <p>Name: Dr. Ajith Kumar</p>
 <p>Department: AIDS</p>
 <p>Designation: Professor</p>
 </div>
 );
}
export default Faculty;
```

### iv) App.jsx
```css
import Student from "./components/Student";
import Course from "./components/Course";
import Faculty from "./components/Faculty";
import "./App.css";
function App() {
 return ( <div className="container">
 <h1>Student Information System</h1>
 <Student />
 <Course />
 <Faculty />
 </div>
 );
}
export default App;
```

### v) App.css
```css
.container {
 text-align: center;
 padding: 30px;
 font-family: Arial, sans-serif;
}
.container h1 {
 color: #1976d2;
}
.container h2 {
 color: #333333;
}
.container p {
 color: #555555;
 font-size: 16px;
}
.container > div {
 border: 1p
x solid #cccccc;
 border-radius: 8px;
 padding: 20px;
 margin: 20px auto;
 max-width: 300px;
 background-color: #f5f9ff;
}
```
## OUTPUT
<img width="1378" height="477" alt="image" src="https://github.com/user-attachments/assets/21281309-cdee-4d0e-a3b7-4b8d117ef170" />
<img width="1016" height="528" alt="image" src="https://github.com/user-attachments/assets/a5754eb1-9246-404c-bee8-bf646cead171" />

## RESULT
### Thus, the Student Information System was successfully created using React components for student, course, and faculty details.
