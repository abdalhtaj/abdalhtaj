- š Hi, Iām @abdalhtaj
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
abdalhtaj/abdalhtaj is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
* {
    
    padding: 0;
    margin: 0;
}


.grid {
    height: 100vh;
    display: grid;
    grid-template-columns: 1fr 500px 500px 1fr;
    grid-template-rows:35px 70px 1fr 1fr 1fr;
    grid-template-areas: 
    "title title" 
    "header header"
    "saidbar conten"
    "footer footer";
  
}



.grid div:nth-child(even){
    background-color:red;
}


.grid div:nth-child(odd){
    background-color:rgb(5, 56, 5);
}



.title {
    grid-area: title;
}

.header {
    grid-area: header;
}

.siadbar {
    grid-area: saidbar;
}



.content {
    grid-area: conten;
}

.footer {
    grid-area: footer;
}


