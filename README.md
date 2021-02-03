### Node.js puppeteer

실습환경
node > 12.0


alter user 'root'@'localhost' identified with mysql_native_password by '비밀번호';


grant all privileges on *.* to 'root'@'localhost' with grant option;


app.js 에 있는 
dbConnection에서 
// return db.sequelize.sync();
// return db.sequelize.drop();

drop부터 주석풀고 그다음에 sync로 진행하기


============================================
puppeteer 문서 찾아보기

puppeteer는 웹브라우저를 띄워준다.