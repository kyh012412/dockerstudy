## 도커 컴포즈 백그라운드 실행법
docker-compose up -d
## db 쿼리문
use rootdb;

create table person(
	id int primary key,
    name varchar(100)
);

insert into person(id,name) values(1,'ssar');

select * from person;