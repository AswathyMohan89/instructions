#### ***<u>Steps for connecting to MySql from Python</u>***

1. In *terminal* or *git bash* and type :`conda install -c anaconda pymysql`
2. In *terminal* or *git bash* and type: `conda install -c anaconda sqlite`
3. After source activate *env*, do:`pip install pymysql`
4. In `jupyter notebook`  do the following steps:
   1. `from sqlalchemy import create_engine`
   2. `import pymysql`
   3. `pymysql.install_as_MySQLdb()`
   4. `engine = create_engine("mysql://<username>:<password>@localhost:3306/<database/schema>")`
   5. `i=engine.execute("select * from <tablename>")`
   6. *for Pandas:*
      1. `conn = engine.connect()`
      2. `data = pd.read_sql("SELECT * FROM <tablename>", conn)`