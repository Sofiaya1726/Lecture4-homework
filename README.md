# Lecture4-homework

### 课堂作业

create table student(
sid INT PRIMARY KEY NOT NULL,
sname VARCHAR(30),
sage INT,
ssex VARCHAR(8)
);
create index index_name ON student(sname(20)); 

create table course(
cid INT PRIMARY KEY NOT NULL,
cname VARCHAR(30),
tid INT
)

create table teacher(
tid INT PRIMARY KEY NOT NULL,
tname VARCHAR(30)
)
